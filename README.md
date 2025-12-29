# GrantReady Cloud

Enterprise-grade grant management core services and SDK for compliance-driven organizations.

## Overview

GrantReady Cloud provides a secure, scalable foundation for grant management systems, designed specifically for government agencies and compliance-focused organizations. The platform offers core services for grant lifecycle management, compliance tracking, and workflow automation with mobile-first design assumptions.

## Architecture

GrantReady Cloud follows a microservices-inspired modular architecture:

- **Authentication Service**: JWT-based auth with role-based access control
- **Grant Management**: Complete grant lifecycle from application to disbursement
- **Compliance Engine**: Real-time compliance checks and audit logging
- **Workflow Orchestration**: Configurable approval workflows and task management

All services are exposed via RESTful APIs with OpenAPI 3.0 specification.

## Key Features

- **Government-Grade Security**: NIST 800-53 aligned security controls
- **Compliance Auditing**: Full audit trails for all grant operations
- **Mobile-Optimized**: API-first design for mobile client integration
- **Extensible Workflows**: Configurable approval chains and business rules
- **Open Standards**: OpenAPI, OAuth 2.0, and JWT standards compliance

## Quick Start

### Prerequisites

- Node.js 18+ 
- PostgreSQL 14+
- Redis 6+ (for session management)

### Installation

```bash
# Clone repository
git clone https://github.com/grantready/grantready-cloud.git
cd grantready-cloud

# Install dependencies
npm install

# Set up environment
cp .env.example .env
# Edit .env with your configuration

# Run services
docker-compose up -d
npm run dev
```
# GrantReady-cloud
