# Architecture

Cook Book uses a monorepo structure.

## Backend

The backend will use Clean Architecture:

- Domain
- Application
- Infrastructure
- API

The backend will use CQRS with MediatR.

## Frontend

The frontend will use React, TypeScript and Vite.

## Database

The database will be PostgreSQL.

## Deployment

The project will first run locally with Docker Compose. Kubernetes may be added later.
