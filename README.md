<h1 align="center">Manankumar (Manan) Thakkar</h1>

<p align="center">
  <strong>Software Engineer III</strong> · Walmart Global Tech · Bentonville, AR
</p>

<p align="center">
  <a href="resume/Manankumar-Thakkar-Resume.pdf"><img src="https://img.shields.io/badge/Resume-PDF-2E3440?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="Resume"></a>
  <a href="https://www.linkedin.com/in/manan-t-93239a151/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:mananaiya@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://calendly.com/mananthakkar/"><img src="https://img.shields.io/badge/Book_a_call-Calendly-006BFF?style=flat-square&logo=calendly&logoColor=white" alt="Calendly"></a>
</p>

---

I build scalable backend systems and the AI tooling that sits on top of them. At Walmart Global Tech I work on the services behind in-store retail media — inventory reservation, store data, and device orchestration — in Java and Spring Boot, at a scale where a single design decision propagates across thousands of stores and multiple international markets.

My work tends to land in two places: making existing systems measurably faster and more correct, and building LLM- and agent-based tools that put operational context directly in engineers' hands.

**Open to Software Engineer, AI Engineer, and Forward Deployed Engineer roles.** U.S.-based, currently on H-1B (transfer-eligible).

## Focus areas

| | |
|---|---|
| **Distributed backend** | Java, Spring Boot, microservices, REST APIs, Kafka, multi-tenant data modeling |
| **Applied AI** | LLM integration, agentic systems, MCP servers and tool use, retrieval-grounded QA |
| **Cloud & data platforms** | GCP (BigQuery, GCS), Azure SQL, AWS, Kubernetes, Redis, automated data pipelines |
| **Reliability** | Performance diagnosis, observability, CI/CD, static analysis and security scanning |

## Experience

### Walmart Global Tech — Software Engineer III
*February 2025 – Present · Bentonville, AR*

- **Architected the Vision Center feature** in Java/Spring Boot so the Inventory Reservation Service could set loop policy per location, and led the migration from percentage- to seconds-based loop metrics — expanding advertiser booking flexibility by 40%.
- **Cut API latency 60%** by diagnosing a production N+1 query bottleneck in the in-store advertising microservices and fixing it with concurrent caching, eliminating 10,000+ redundant database calls per day.
- **Prevented a 6x cardinality collision** during multi-tenant international expansion across 7+ partner orgs: caught a key-grain design flaw during integration and drove a durable country-scoped key rather than a regional patch.
- **Automated store-readiness reporting** with a Python pipeline over Azure SQL, Redis, BigQuery, and Tableau, applying 13 business rules across 4,000+ stores twice daily — replacing a hand-assembled report, validated to an exact match, and surfacing 3 latent defects in the process.
- **Built an LLM-powered operations assistant** (Python, Flask, LangChain) on Walmart's internal LLM Gateway, letting engineers query operational context conversationally with session-scoped memory and response caching.

### Walmart Global Tech — Software Engineer
*July 2024 – January 2025 · Bentonville, AR*

- Shipped Java/Spring Boot features for Store Department Hours and Sam's Club Plus operating hours, extending the store data model to Deli, Bakery, and Service Deli schedules across 1,000+ locations.
- Implemented location-to-screen-group mapping for new retail formats (Grab-N-Go, Sam's Club Cafe) and cross-entity filtering across the stores, inventories, and device-commands REST APIs, enabling more precisely targeted ad placements.

### Earlier

| Role | Organization | Period | Focus |
|---|---|---|---|
| AI Research Assistant | George Mason University | 2023 – 2024 | LLM-based research tooling; research infrastructure as code with Terraform |
| Test Automation Engineer (Co-op) | Nokia | 2022 – 2023 | Python automation for high-throughput systems (−50% manual effort); Jenkins CI/CD integration (−20% defect density) |
| Full Stack Developer | Let It Wag | 2019 – 2020 | Node.js services and REST APIs serving 13K+ users; React UI across 100+ user journeys |

## Selected AI work

**AuthForge** — *Python, MCP, Spring Boot, Istio*

An MCP server that remediates missing-authentication findings in Java services through configuration alone, with no application code changes. Nine tools spanning diagnosis, endpoint scanning, consumer discovery, config generation, and validation.

**Wayfinder** — *Python, LLM orchestration, agent routing* · Walmart Global Tech Hackathon

An agentic system that triages Slack, email, and calendar by intent and routes work to specialized sub-agents. I owned the routing layer, query sanitization, and the extensibility framework, with one-click human approval gates on every action.

*Both were built internally; the descriptions above are the publicly shareable summaries.*

## Technical skills

| | |
|---|---|
| **Languages** | Java · Python · SQL · JavaScript · TypeScript |
| **Backend** | Spring Boot · Microservices · REST APIs · Kafka · Flask · Node.js · React · Liquibase · JUnit |
| **AI / LLM** | LLM integration · Agentic systems · MCP / tool use · LangChain · Retrieval-grounded QA · Prompt engineering |
| **Cloud & Data** | GCP (BigQuery, GCS) · Azure SQL · AWS · Kubernetes · Docker · Redis · Terraform · Tableau |
| **DevOps & Quality** | CI/CD · Grafana · Prometheus · Splunk · OpenObserve · SonarQube · Snyk |

## Education

**George Mason University** — M.S. Computer Science, 2021 – 2023 · Fairfax, VA

*Relevant coursework:* Data Structures and Algorithms · Software Modeling and Architectural Design · Data Mining · Advanced NLP

## Get in touch

The fastest way to reach me is **[mananaiya@gmail.com](mailto:mananaiya@gmail.com)** or a direct message on **[LinkedIn](https://www.linkedin.com/in/manan-t-93239a151/)**. If it's easier to just talk, [book a time](https://calendly.com/mananthakkar/) or [message me on WhatsApp](https://api.whatsapp.com/send?phone=16673209836&text=Hi%20Manan!).
