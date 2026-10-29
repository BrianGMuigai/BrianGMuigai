<div align="center">

# Hi there, I'm Brian Muigai 👋

### Backend Engineer · Java / Spring Boot · Python · Relational Data Systems

*I build reliable APIs and the data layers behind them.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brian-muigai/)&nbsp;
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:brianmuigai40@gmail.com)&nbsp;
[![Portfolio](https://img.shields.io/badge/Portfolio-111827?style=flat&logo=vercel&logoColor=white)](https://brianmuigai.vercel.app/)&nbsp;
![Location](https://img.shields.io/badge/Nairobi,_Kenya-374151?style=flat&logo=googlemaps&logoColor=white)

</div>

---

## 👨‍💻 About

I'm a backend engineer who builds and owns production services in **Java / Spring Boot**, with Python for supporting services and tooling. I care most about correctness under load: sound data models, deliberate transaction boundaries, and systems that are easy to test, observe and change.

## ⚙️ What I Work On

- 📡 **APIs:** RESTful services with strict request validation, cursor-based pagination and centralized exception handling
- 🗄️ **Data:** normalized schemas, compound indexes and versioned Flyway migrations on PostgreSQL and SQL Server, with isolation levels and locking (`UPDLOCK`) chosen per use case
- 📨 **Messaging & Caching:** event-driven services on Kafka, with Redis on the hot read paths
- ✅ **Quality:** unit and integration tests with JUnit and Mockito, enforced through CI on every change
- 📦 **Delivery:** multi-stage Docker builds, plus Bash and Python tooling to remove repetitive operational work

**A typical transactional pipeline:**

```text
Ingestion ──► Kafka (event queue) ──► Java service (business logic)
                                              │
                          ┌───────────────────┴───────────────────┐
                          ▼                                       ▼
                 Redis (hot cache)                  PostgreSQL / SQL Server
                                                    (ACID source of truth)
```

## 🧭 How I Work

- **Model the data first.** Most backend problems are cheaper to fix in the schema than in the code.
- **Make failure explicit.** Validate at the boundary, handle errors in one place and log with enough context to debug.
- **Automate what repeats.** If I do it twice, it becomes a script.
- **Keep code replaceable.** Simple, well-tested modules beat clever ones.

---

## 🛠️ Tech Stack

**Languages & Frameworks**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

**Data & Messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DD0031?style=for-the-badge&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)

**DevOps & Tooling**

![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Fedora](https://img.shields.io/badge/Fedora-294172?style=for-the-badge&logo=fedora&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2671E5?style=for-the-badge&logo=githubactions&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

**Terminal Environment**

![Neovim](https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white)
![Tmux](https://img.shields.io/badge/Tmux-1BB91F?style=for-the-badge&logo=tmux&logoColor=white)
![Kitty](https://img.shields.io/badge/Kitty-000000?style=for-the-badge&logo=gnometerminal&logoColor=white)
![i3](https://img.shields.io/badge/i3-333333?style=for-the-badge&logo=i3&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash&logoColor=white)

---

## 🚀 Featured Projects

<!-- Add your projects here. Example format:

### [Project Name](https://github.com/YOUR_USERNAME/project-name)
One-line description of what it does and why it matters.
`Java` `Spring Boot` `PostgreSQL` `Docker`

-->

*Projects coming soon.*

---

## 🤝 Let's Connect

I'm open to collaborating on backend projects and talking system design, Python and distributed systems.

- 💼 [LinkedIn](https://www.linkedin.com/in/brian-muigai/)
- 🌐 [Portfolio](https://brianmuigai.vercel.app/)
- 📧 [brianmuigai40@gmail.com](mailto:brianmuigai40@gmail.com)

---

<div align="center">

```text
"The most reliable code is the code you didn't have to write.
 The next best is the code that is easy to replace."
```

**⭐ If you find my work interesting, consider starring my repositories.**

<sub>Engineered with ☕ and Bash on Fedora</sub>

</div>
