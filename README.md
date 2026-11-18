## Hi, I'm Alou (Alassane Ndour) 👋

**Master's student in Distributed Information Systems** at Université Cheikh Anta Diop (UCAD), Dakar, Senegal.
I build backend and data systems that stay **correct under concurrency**, and I'm moving step by step toward **data engineering**.

### 🔨 Currently building

**[KaaranguéPay — Mobile Money Data Platform](https://github.com/AlouCoding/kaarangepay-data-platform)**
An end-to-end data engineering project around a fictional West African mobile money platform.

- Spring Boot **double-entry ledger**: the sum of all balances is always zero, checkable at any time
- **Idempotent payments**: exactly-once enforced by a PostgreSQL `UNIQUE` constraint, tested under concurrent retries
- **26 tests** with Testcontainers, CI on GitHub Actions
- Python generator of **realistic traffic** (paydays, Tabaski, day/night cycle) and fraud scenarios
- Measured: **134,335 API calls at ~205 tx/s** on a laptop, ledger invariants still at zero
- Next: CDC with Debezium and Kafka → streaming → lakehouse → dbt

### 📂 Other projects

| Project | What it does | Stack |
|---|---|---|
| [tontine-lightning](https://github.com/AlouCoding/tontine-lightning) | Digital tontine on Bitcoin Lightning (Dakar Bitcoin Days 2026 hackathon, team project). **I owned the Lightning layer**: payment proofs, protection against double payment, Docker regtest network, **74 tests** | Python · FastAPI · LNbits/LND · Docker |
| [supervision-docker-hybride](https://github.com/AlouCoding/supervision-docker-hybride) | Hybrid network and container monitoring stack: active probing, network map, multi-channel alerts | Docker Compose · Nagios Core · Shell |
| [PharmaNPS-Alou](https://github.com/AlouCoding/PharmaNPS-Alou) | Collaborative pharmacy information system, focused on performance and software architecture | Python · Django |
| Livestock management *(Bachelor's thesis — repo coming soon)* | Web app for Senegalese breeders: herd and stock management, breeder–veterinarian chat, **automatic assignment of the nearest veterinarian to each enclosure**. Team of 2: I developed the whole application and gave the demo | Java EE · JSF · Hibernate · PostgreSQL · Maven |

### 🎓 What I study

Distributed systems · network services · distributed databases · system performance ·
data warehousing & BI · machine learning & deep learning

### 🧰 Tech I use

**Backend:** Java · Spring Boot · REST APIs
**Data:** SQL · PostgreSQL · Python · data warehousing & BI
**Tooling:** Docker · Docker Compose · Git · GitHub Actions · Testcontainers

### 📚 Learning now

- Google Data Analytics certificate (in progress)
- Data engineering: CDC, Kafka, streaming

### 🤝 Open to

Backend and data engineering **internships** — in Senegal, France, Canada or **remote**.
**Open to relocation.**

<!-- Add your LinkedIn link here once your profile is ready:
[LinkedIn](https://www.linkedin.com/in/your-profile) -->
