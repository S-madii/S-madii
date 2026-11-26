## Soualmia Mohieddine

**Backend Engineer** · Algeria  
Building asynchronous Python services, transactional database systems, and real-time backend architectures.

[![Email](https://img.shields.io/badge/mohieddine.soualmia@gmail.com-181717?style=flat-square&logo=gmail&logoColor=white)](mailto:mohieddine.soualmia@gmail.com)
[![Instagram](https://img.shields.io/badge/@mohieddine__sam-181717?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/mohieddine_sam)

---

### Core Stack

```text
Languages    Python · SQL · Java · C · Bash
Backend      FastAPI · SQLAlchemy 2.0 (asyncpg) · Pydantic v2 · Alembic · Celery
Data         PostgreSQL · Redis (Cache-Aside & Message Broker)
DevOps & QA  Docker · Docker Compose · GitHub Actions CI · pytest-asyncio · Linux
```

---

### Featured Systems

**[Ecommerce-Api](https://github.com/S-madii/Ecommerce-Api)** — *Async E-Commerce Engine (`FastAPI` · `PostgreSQL 16` · `Redis` · `Celery` · `Stripe`)*
- **Concurrency & ACID Integrity:** Pessimistic row-level inventory locking (`SELECT ... FOR UPDATE`) with deterministic lock ordering and lock decoupling prior to external network calls.
- **Zero-Trust Payments:** Stripe PaymentIntent flow with integer-cent precision, raw-byte HMAC-SHA256 webhook verification, idempotency guards, and compensating stock rollbacks.
- **Caching & Async Workers:** Non-blocking `redis.asyncio` cache-aside with active pattern invalidation, fail-open resilience, and post-commit Celery task offloading.
