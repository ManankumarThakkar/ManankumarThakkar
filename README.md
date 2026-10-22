<div align="center">

# Manankumar Thakkar

**Backend and AI engineer.** I build distributed services, and the LLM and agent tooling that runs on top of them.

<kbd> Software Engineer </kbd> • <kbd> AI / Agentic Systems </kbd>

<p>
  <a href="https://mananthakkar.dev"><img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
  <a href="resume/Manankumar-Thakkar-Resume.pdf"><img src="https://img.shields.io/badge/Resume-PDF-2E3440?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Resume"></a>
  <a href="https://www.linkedin.com/in/mananthakkar20/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:mananaiya@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://calendly.com/mananthakkar/"><img src="https://img.shields.io/badge/Book_a_call-006BFF?style=for-the-badge&logo=calendly&logoColor=white" alt="Book a call"></a>
</p>

</div>

---

## What I'm building now

**[Archwoven](https://archwoven.dev)** turns a system description or a GitHub repository into four editable architecture views: the big picture, the request sequence, the data model, and component detail. Model output passes through Zod schemas, graph checks, and bounded repair before anything renders, so a malformed answer gets caught instead of drawn. Repository analysis uses tree-sitter rather than asking a model to read the code: on Spring PetClinic it matched hand-checked ground truth exactly, 19/19 nodes and 10/10 edges. Worst-case cost is reserved before every paid model call, and the whole thing runs locally against Ollama if you would rather not call out at all. Next.js and TypeScript, MIT licensed. [Source](https://github.com/ManankumarThakkar/archwoven).

**[MCP Security Observatory](https://manankumarthakkar.github.io/mcp-observatory/)** is a static scanner for the Model Context Protocol ecosystem. AI assistants load MCP servers as plugins and run them with your own privileges, usually with no sandbox and no review; this reads them without executing a line. Five tree-sitter taint rules cover shell execution, path traversal, tool-description injection, hidden Unicode, and over-broad scope. 1,600+ servers scanned, with 800+ high and critical findings withheld pending maintainer disclosure, a gate enforced in code rather than promised in a policy. Nightly pipeline, SARIF output, public dashboard. Rule accuracy is still being labelled, and the project says so on its own front page. [Source](https://github.com/ManankumarThakkar/mcp-observatory).

**[Escalation Gate](https://github.com/ManankumarThakkar/jev-escalation-gate)** asks how much work a small, cheap model can take off an expensive one, and how you would actually know. Across 600 SQuAD 2.0 items, test-set construction alone swung accuracy 30.5 points, calibration error measured 0.047 against a 0.039 noise floor, and a routing band skipped generation for 14.5% of passages.

Alongside them:

- **Agentic systems.** MCP tool design, agent routing, and the harder half: how you evaluate these systems and decide when to trust them in production.
- **Backend at scale.** Multi-tenant service design, query-path and caching performance, and the observability to prove a change worked.

## What I'm looking for

Open to Software Engineer and AI Engineer roles, across backend, distributed systems, platform, and applied AI.

## Selected impact

- Cut API latency **60%** on production advertising microservices, eliminating **10,000+** redundant database calls a day.
- Caught a key-grain design flaw during multi-tenant international expansion across 7+ partner orgs and prevented a **6x** cardinality collision.
- Replaced a hand-assembled readiness report with an automated pipeline applying 13 business rules across **4,000+ stores** twice daily, validated to an exact match and surfacing 3 latent defects.

## Stack

**Core**

<img src="https://skillicons.dev/icons?i=java,spring,python,ts,js,nextjs,react,nodejs,tailwind,flask" alt="Java, Spring, Python, TypeScript, JavaScript, Next.js, React, Node.js, Tailwind, Flask" />

**Cloud, data and platform**

<img src="https://skillicons.dev/icons?i=gcp,azure,aws,kubernetes,docker,terraform,redis,postgres,mysql" alt="GCP, Azure, AWS, Kubernetes, Docker, Terraform, Redis, Postgres, MySQL" />

**AI / LLM** · Generative AI agents · LLM evaluation · Structured outputs with Zod · RAG · MCP and tool use · LangChain · Ollama

**Data and observability** · Kafka · BigQuery · Grafana · Prometheus · Splunk · SonarQube · Snyk

## Where I work

Software Engineer III at **Walmart Global Tech**, on the backend services behind in-store retail media: inventory reservation, store data, and device orchestration in Java and Spring Boot.

## Reach me

**[mananthakkar.dev](https://mananthakkar.dev)** · **[mananaiya@gmail.com](mailto:mananaiya@gmail.com)** · **[LinkedIn](https://www.linkedin.com/in/mananthakkar20/)** · **[book a call](https://calendly.com/mananthakkar/)** · **[WhatsApp](https://api.whatsapp.com/send?phone=16673209836&text=Hi%20Manan!)**
