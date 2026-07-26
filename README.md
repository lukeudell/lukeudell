<div align="center">

# Luke Udell

**Data Engineer · Rust & Python · M.S. Software Engineering**

[![Portfolio](https://img.shields.io/badge/Portfolio-lukeudell.com-2563EB?style=for-the-badge&logo=Web)](https://lukeudell.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=LinkedIn)](https://linkedin.com/in/luke-udell/)

Data engineer at IBM. Retired U.S. Army Major. I build things at work and on my own time, and I hold both to the same standard.

</div>

---

### What I do

I build data pipelines and the systems around them: ETL/ELT in Python and SQL, dimensional models in PostgreSQL and dbt, and the platforms that serve what comes out of them. At IBM that work is for a Department of Veterans Affairs program. On my own time it is usually Rust.

Before this, eighteen years as an Army officer, most of it spent turning four or five enterprise systems that did not talk to each other into something a commander could actually act on. Nobody called that data engineering. It was the same job with a different output format.

Everything I ship has tests, documentation, and architecture the next person can pick up cold. That is not a preference. It is the whole point.

---

### Tech

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![dbt](https://img.shields.io/badge/dbt_Core-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white)

---

### Public projects

Each of these is a complete, runnable argument for one technique, built on synthetic data so anyone can clone it and reproduce every number in it from cold.

| Project | What it is | Stack |
| :--- | :--- | :--- |
| **[andvari](https://github.com/lukeudell/andvari)** | Star schema versus snowflake, measured rather than argued. Synthetic LLM telemetry through Postgres and dbt, with a Streamlit cost forecaster on top. The trade-off is the deliverable, not the opinion. | Python, dbt, PostgreSQL, Streamlit |
| **[draupnir](https://github.com/lukeudell/draupnir)** | Metrics design for an ad-supported streaming service: synthetic telemetry, dbt dimensional models, and a campaign pacing monitor. Every published number is reproducible from a cold clone. | Python, dbt, PostgreSQL, Streamlit |
| **[midgard](https://github.com/lukeudell/midgard)** | The sanitised architecture record for my home network: nine VLANs enforcing seven trust zones, default-deny between them, local recursive DNS. Documentation treated as a deliverable. The architecture, not the addresses. | Shell, Mermaid, UniFi |
| **[signal-lens](https://github.com/lukeudell/signal-lens)** | Interactive Signal Protocol simulator running real cryptography: X3DH and the Double Ratchet with actual X25519, HKDF and AES-256-GCM. Every hex value on screen is the real output of the real operation. Nothing is mocked. | TypeScript, FastAPI, React |
| **[resume-forge](https://github.com/lukeudell/resume-forge)** | Privacy-first resume generator with a hexagonal Rust core. Strips every piece of personally identifiable information before any AI call and shows you the exact payload before it is sent. | Rust, Axum, React, PostgreSQL |
| **[nexus](https://github.com/lukeudell/nexus)** | Multi-vendor AI chat platform (Claude, GPT, Gemini) with group conversations and personas. Nine Rust crates, field-level AES-256-GCM, 450+ tests, three OWASP audits. Self-hosted, and I use it daily. | Rust, Axum, Astro, React, Keycloak |

---

### Most of what I build is private

Production systems with real users, work with commercial intent, and a lot of things I simply never got around to publishing. I have been building since my twenties and I put very little of it out there.

So the repos above are not an inventory. They show *how* I work; they are not a list of *what* I have built. A few of the private ones:

| Project | What it is |
| :--- | :--- |
| **Civic advocacy platform** | The platform for a non-partisan advocacy organization in my hometown. Rust/Axum API with Keycloak auth, 11-role RBAC, a tamper-proof audit database, rate limiting with device fingerprinting, GeoIP and Tor screening, and a documented threat model. 500+ frontend tests, 400+ on the API. In production, serving real users. I maintain it for free because I live there. |
| **Mimir** | Self-hosted personal-finance platform: a normalized ledger and a Kimball warehouse, double-entry enforced at three layers, forward-only migrations with audit companions. It is what my family's money actually runs on. |
| **lukeudell.com** | The portfolio itself. Spring Boot and JTE over one shared Postgres with a database per showcased demo, dbt models surfaced through Metabase and live Streamlit apps, a hidden capture-the-flag arcade, and the engineering standards document it is built to. |

Deeper access on request.

---

### How I work

I keep a [written standards document](https://lukeudell.com/standards/) so that what I believe is checkable rather than implied. The short version:

- **Documentation you would not use yourself is not documentation.** If your docs cannot get me from zero to running in a reasonable amount of time, write better docs or ship less code.
- **Constrain your dependencies.** Pin versions, watch CVEs, own what you import. Boring engineering is how you ship things that do not rot.
- **Segment before you scale.** Nine VLANs at home, three schemas in every warehouse, cleanly separated crates in every Rust project. The architecture is the part you do not have to rewrite later.
- **Build it for the next person.** If I got hit by a bus tomorrow, could someone pick up what I was doing? If not, I am not finished.

---

<div align="center">

More at **[lukeudell.com](https://lukeudell.com)**, including [the projects in depth](https://lukeudell.com/projects) and [the longer story](https://lukeudell.com/story).

</div>
