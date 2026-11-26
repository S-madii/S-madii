<div align="center">

  <h1>Soualmia Mohieddine</h1>
  <p><strong>Backend Developer · Software Engineering · Algeria</strong></p>

  <p>
    <a href="mailto:mohieddine.soualmia@gmail.com">
      <img src="https://img.shields.io/badge/Email-mohieddine.soualmia%40gmail.com-111111?style=for-the-badge&logo=gmail&logoColor=EA4335" alt="Email" />
    </a>
    <a href="https://instagram.com/mohieddine_sam">
      <img src="https://img.shields.io/badge/Instagram-%40mohieddine__sam-111111?style=for-the-badge&logo=instagram&logoColor=E4405F" alt="Instagram" />
    </a>
  </p>

</div>

<br />

### ⚡ About Me

- 🛠️ Building **Python backends** (`FastAPI`, `Flask`), **relational database systems** (`PostgreSQL`, `MySQL`), and **background task queues** (`Redis`, `Celery`)
- 🔒 Focused on **concurrency control**, **JWT authentication**, **payment webhooks (Stripe)**, and **automated testing (`pytest`)**
- 🐧 Daily driving **Linux**, **Docker**, and **GitHub Actions CI/CD**

<br />

### 🧰 Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=py,fastapi,flask,postgres,mysql,redis,docker,linux,git,github,githubactions,mariadb,java,c,bash,html,css,js&perline=9" alt="Tech Stack" />
</div>

<br />

### 🚀 Projects

<table>
  <tr>
    <td>
      <a href="https://github.com/S-madii/Ecommerce-Api"><strong>🛒 Ecommerce-Api</strong></a>
      &nbsp;
      <img src="https://github.com/S-madii/Ecommerce-Api/actions/workflows/ci.yml/badge.svg" alt="CI" />
      <p>
        Production-ready async e-commerce backend built with <strong>FastAPI</strong>, <strong>PostgreSQL 16</strong>, <strong>SQLAlchemy 2.0 (asyncpg)</strong>, <strong>Redis</strong>, <strong>Celery</strong>, and <strong>Stripe</strong>.
      </p>
      <ul>
        <li><strong>Pessimistic Concurrency:</strong> Deadlock-free <code>SELECT ... FOR UPDATE</code> row locking with decoupled external Stripe calls and compensating inventory rollbacks.</li>
        <li><strong>Zero-Trust Payments:</strong> Stripe PaymentIntent lifecycle with raw-byte HMAC-SHA256 webhook verification and idempotency guarantees.</li>
        <li><strong>Caching & Background Workers:</strong> Non-blocking <code>redis.asyncio</code> Cache-Aside with pattern invalidation, fail-open resilience, and post-commit Celery email tasks.</li>
      </ul>
    </td>
  </tr>
</table>
