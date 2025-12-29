grantready-cloud/
├── README.md
├── LICENSE
├── .github/
│   └── workflows/
│       └── ci.yml
├── api/
│   └── openapi.yaml
├── docs/
│   ├── architecture.md
│   └── security.md
├── src/
│   ├── auth/
│   │   ├── index.ts
│   │   ├── service.ts
│   │   ├── middleware.ts
│   │   └── types.ts
│   ├── grants/
│   │   ├── index.ts
│   │   ├── service.ts
│   │   ├── models.ts
│   │   └── validation.ts
│   ├── compliance/
│   │   ├── index.ts
│   │   ├── audit.ts
│   │   ├── checks.ts
│   │   └── standards.ts
│   ├── workflows/
│   │   ├── index.ts
│   │   ├── engine.ts
│   │   ├── templates.ts
│   │   └── tasks.ts
│   └── shared/
│       ├── config.ts
│       ├── database.ts
│       └── logging.ts
├── sdk/
│   └── typescript/
│       ├── package.json
│       ├── index.ts
│       ├── client.ts
│       └── types.ts
├── package.json
├── tsconfig.json
├── docker-compose.yml
└── .gitignore
