# CROO Suite Infrastructure

Single-host Docker Compose deployment for PostgreSQL, Redis, and the six independently deployable CROO workers.

Before deployment, create all Dashboard identities and services, fund requester-capable AA wallets with controlled USDC, create `env/*.env`, and run:

```bash
docker compose config
docker compose up -d --build
docker compose ps
```

Production acceptance requires real negotiate, pay, deliver, complete, restart-recovery, dependency-failure, and degraded-source evidence. These cannot be truthfully completed without CROO Dashboard credentials and funded wallets.
