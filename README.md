# Hi, I'm Suresh Kosana

**Java Backend Developer** | MCA 2025 | Hyderabad, India

I build and test Spring Boot REST APIs: JWT security, payment integration, caching, messaging and CI. I'm looking for an entry-level Java backend role.

[Portfolio](https://suresh-1219.github.io) | [LinkedIn](https://linkedin.com/in/suresh-kosana) | sureshkosana333@gmail.com

---

## Projects

### E-Commerce Order Management System
Backend for an online store: products, cart, orders and Razorpay payments.
- JWT with CUSTOMER / ADMIN roles and ownership checks
- Razorpay HMAC-SHA256 signature verification, idempotent payment creation
- Redis caching, login rate limiting (Bucket4j), async order emails
- 34 automated tests (JUnit 5, Mockito, MockMvc), GitHub Actions CI, Docker, deployed on Render

[Repository](https://github.com/suresh-1219/ecommerce-order-management-system) | [Live demo (Swagger)](https://ecommerce-order-management-system-v6mm.onrender.com/swagger-ui/index.html)

### Student Management System
Backend for students, courses, enrollments, grades and attendance.
- JWT with refresh-token rotation (hashed tokens), USER / ADMIN roles
- Optimistic and pessimistic locking to prevent course over-enrollment
- RabbitMQ notifications with a dead-letter queue, Flyway migrations, Redis caching
- 300 tests (JUnit 5, Mockito, Testcontainers on real MySQL), 86% instruction coverage, CI on every push

[Repository](https://github.com/suresh-1219/student-management-system) | [Live demo (Swagger)](https://student-management-system-sh46.onrender.com/swagger-ui.html)

### Quiver: Consistent Object Sharing System
Three-node object sync system in Java (raw TCP sockets, no framework).
- Vector clocks and a Last-Write-Wins CRDT so every node converges to the same value
- Ed25519-signed messages with replay protection, crash-safe append-only journal
- 88 JUnit 5 tests including chaos tests, 69% coverage, Docker and Kubernetes manifests

[Repository](https://github.com/suresh-1219/quiver-consistent-object-sharing-system)

---

## Skills

- **Languages and databases:** Java, SQL, MySQL, PostgreSQL, Redis
- **Backend:** Spring Boot, Spring MVC, Spring Security, Spring Data JPA, Hibernate, REST APIs, JWT, RabbitMQ, Flyway, Maven
- **Testing and DevOps:** JUnit 5, Mockito, MockMvc, Testcontainers, JaCoCo, Docker, Docker Compose, Git, GitHub Actions

## Education

MCA (2023-2025) and B.Sc. Computer Science (2020-2023), S.V.K.P & Dr. K.S. Raju Arts & Science College (A), Penugonda, affiliated to Adikavi Nannaya University.

Full Stack Java Development, Capgemini and TNS India Foundation. AI Fundamentals, IBM SkillsBuild.

*Demos run on free hosting, so the first load can take about a minute.*
