# NestJS Service Template

Boilerplate NestJS for independent microservices.

## Structure
- src/app            → bootstrap & wiring
- src/interfaces     → HTTP controllers
- src/application    → use cases
- src/domain         → business rules
- src/infrastructure → DB, external services
- src/config         → configuration

## Run
```bash
pnpm install
pnpm start:dev
