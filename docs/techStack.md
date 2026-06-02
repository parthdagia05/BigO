# 0001 — Why java over other languages

Java 21 because it's the LTS the industry uses, and virtual threads + records make modern Java productive.

---

# 0002 — Springboot framework

Spring Boot because it's the industry-standard Java framework with the biggest ecosystem and the most learning resources.

---

# 0003 — Maven over Gradle
Maven because it's explicit and beginner-friendly, and it matches the tutorials I'm learning from.

---

# 0004 — Postgresql
Postgres because my data is relational and transactional; a document store like Mongo would be the wrong tool here.

---

# 0005 — Redis
Redis because sorted sets give me instant leaderboards and atomic counters give me rate limiting things Postgres would do slowly

---

# 0006 — RabbitMQ
RabbitMQ because judging is slow async work, a queue decouples submission from execution and gives me retries/acks. Kafka would be overkill for a solo job queue

---

# 0007 — Docker
Docker because I'm running untrusted code and need cheap, disposable, resource-limited isolation — running it directly would be a security disaster, and a VM per run would be too slow.

---

# 0008 — JWT auth
JWT because stateless tokens scale horizontally and teach real token security; sessions would tie me to server-side state

---

# 0009 — React + Vite + Monaco
React because it's the dominant frontend skill, and Monaco gives me a real in-browser code editor for free.

---

# 0010 — React + Vite + Monaco
WebSockets because verdicts should be pushed the instant they're ready; polling would be wasteful and laggy

---

# 0011 — Hetzner VPS - deployment
A bare VPS because it forces me to learn Linux, Nginx, and production ops managed platforms would hide exactly the skills I want


