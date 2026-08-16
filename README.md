# Steven Echeverria — Backend Engineer

I've shipped production backends for three paying clients. All three are live with real users and real revenue.

> ⚙️ **How I approach a system:** constraints and failure modes first, schema second, endpoints last. The stack follows once the shape of the problem is clear.

---

## 🏗️ Production Work

| Project | Stack | What It Does |
|---------|-------|--------------|
| [Pura Vida Entertainment](https://pura-vida-entertainment.vercel.app/) | Java · Spring Boot · React · Stripe · RabbitMQ · Redis | Studio booking and music label platform. Async job processing via RabbitMQ, idempotent Stripe webhooks, TOTP 2FA, JWT + RBAC. Built for a real entertainment business with live bookings and payments. |
| [Five Star HVAC](https://ductllc.vercel.app/) | Python · FastAPI · PostgreSQL · Stripe · Docker | Full service management platform. Scheduling automation, role-based access control, live Stripe payments. Built for an active HVAC business. |
| [Original Design Dealership](https://orginal-design-dealership.vercel.app/) | Next.js · TypeScript · PostgreSQL · Stripe | Dealership inventory and contract management. Webhook-driven payment confirmation, full inventory CRUD. Built for a real dealership. |

---

## 🚧 Current Build — FitTrack Pro

Production-grade fitness and nutrition API. Designing with scalability in mind from day one, building toward that design systematically.

**What's done:**
- ✅ RFC 7807 error contracts across all endpoints — no inconsistent error shapes, no leaking stack traces
- ✅ JWT auth with single-use refresh token rotation — tokens stored hashed, short-lived access tokens (15m)
- ✅ 14-table PostgreSQL schema designed upfront with Flyway migrations — no manual schema changes, ever
- ✅ Architecture Decision Records documenting every major technology choice

**Stack:** Java 21 · Spring Boot 3 · PostgreSQL · Redis · Docker · AWS

→ [github.com/Su1kii/Calorie-Tracker](https://github.com/Su1kii/Calorie-Tracker)

---

## 🛠️ What I Know Well

**Languages:** Java · Python · TypeScript · JavaScript · SQL

**Backend:** Spring Boot · FastAPI · Node.js · REST APIs

**💳 Payments & Auth:** Stripe webhooks · idempotency · JWT · OAuth2 · RBAC · TOTP 2FA

**🗄️ Data:** PostgreSQL · Redis (cache-aside) · RabbitMQ

**Infrastructure:** Docker · Flyway · GitHub Actions CI/CD · Linux (Ubuntu/WSL2)

**☁️ Cloud:** AWS (RDS · EC2 · ElastiCache)

**Testing:** JUnit 5 · Mockito · Testcontainers

**Familiar:** Kafka · Kubernetes · GraphQL · MongoDB

---

## 🧠 LeetCode

Working through NeetCode 150 in Java — hash maps, sliding window, binary search, trees.

→ [github.com/Su1kii/neetcode-submissions](https://github.com/Su1kii/neetcode-submissions)

---

📍 Salt Lake City, UT · Open to backend roles
🔗 [steven-en.vercel.app](https://steven-en.vercel.app/) · [LinkedIn](https://linkedin.com/in/steven-echeverria) · stevennava749@gmail.com
