<div align="center">

  <h1>Soualmia Mohieddine</h1>
  <p><strong>Backend Engineer · Systems & API Architecture · Algeria</strong></p>

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

- 🛠️ Designing and building **asynchronous Python backends**, **transactional PostgreSQL schemas**, and **distributed worker pipelines**
- 🔒 Focused on **concurrency control**, **cache invalidation**, **payment webhooks (Stripe)**, and **containerized deployments**
- 🐧 Daily driving **Linux (CachyOS / Arch)**, **Docker**, and **GitHub Actions CI/CD**

<br />

### 🧰 Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=py,fastapi,postgres,redis,docker,linux,git,githubactions,java,c,bash&perline=6" alt="Tech Stack" />
</div>

<br />

### 🚀 Featured Architecture

<table>
  <tr>
    <td>
      <a href="https://github.com/S-madii/Ecommerce-Api"><strong>🛒 Ecommerce-Api</strong></a>
      &nbsp;
      <img src="https://github.com/S-madii/Ecommerce-Api/actions/workflows/ci.yml/badge.svg" alt="CI" />
      <p>
        High-concurrency async e-commerce engine built with <strong>FastAPI</strong>, <strong>PostgreSQL 16</strong>, <strong>SQLAlchemy 2.0 (asyncpg)</strong>, <strong>Redis</strong>, <strong>Celery</strong>, and <strong>Stripe</strong>.
      </p>
      <ul>
        <li><strong>Pessimistic Concurrency:</strong> Deadlock-free <code>SELECT ... FOR UPDATE</code> row locking with decoupled external Stripe calls and compensating inventory rollbacks.</li>
        <li><strong>Zero-Trust Payments:</strong> Stripe PaymentIntent lifecycle with raw-byte HMAC-SHA256 webhook verification and idempotency guarantees.</li>
        <li><strong>Caching & Background Workers:</strong> Non-blocking <code>redis.asyncio</code> Cache-Aside with pattern invalidation and post-commit Celery email tasks.</li>
      </ul>
    </td>
  </tr>
</table>
