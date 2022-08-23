# coppit

It's an educational project, a copy of Reddit, so... **coppit**!

### Specification
I'd like to create a basic version of Reddit with the following specification:
- Microservice backend architecture written in Kotlin
- Frontend in React with TypeScript
- Event driven (Kafka, AWS SNS / SQS)
- Hosted on the cloud (AWS / Azure)
- Cached with Redis
- Both relation (PostgreSQL) and non relational databases present
- On Kubernetes, with Service Discovery and Kubernetes
- JWT based authentication
- Workflow automation with github actions
- IaaS with Terraform

---

### MVP
- Stage 1
    - Registering and logging in
    - No user data change
    - Five boards set up beforehand
    - Posts only with text
    - No comments
    - No voting
    - Only sorting by date added
    - Mobile friendly

---
### Log
- [22.08.2022] First draft. Initiating React frontend app.
- [23.08.2022] Chose **Authelia** as an identity and access management solution. Set up a simple docker compose
  with PostgreSQL, pgAdmin, Authelia, and Redis
