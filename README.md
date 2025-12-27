# Hi there, I'm Mutwiri 👋

[![Follow](https://img.shields.io/github/followers/imutwiri?label=Follow&style=social)](https://github.com/imutwiri)
[![Profile Views](https://komarev.com/ghpvc/?username=imutwiri&color=brightgreen)](https://github.com/imutwiri)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=imutwiri&layout=compact&theme=radical)](https://github.com/imutwiri)
[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=imutwiri&show_icons=true&theme=radical)](https://github.com/imutwiri)

I build reliable, maintainable backend systems and scalable web applications with a strong focus on automation, testing, and observability.

---

## 🔭 Technical summary
- Primary focus: backend systems, APIs, distributed services, and DevOps automation
- Languages: TypeScript, PHP, Python, NodeJS
- Architectural patterns: microservices, event-driven design, CQRS for bounded contexts
- Infrastructure: Docker
- CI / CD: GitHub Actions (lint → test → build → publish)
- Testing: unit, integration, contract tests (and property tests where appropriate)
- Observability: structured logging, OpenTelemetry, Prometheus + Grafana

---

## 🧰 Tooling & Tech stack
- Runtimes & languages: Node.js (TypeScript), HTML, Tailwind CSS, JavaScript, Python
- Datastores: PostgreSQL, MongoDB
- Messaging & streaming: Kafka
- API: REST + gRPC
- Infra & deployment: Docker

---

## 🚀 Project showcase
Technical highlights and quickstarts for selected projects. If you want I can swap placeholder commands with each repo's exact setup.

- MyPortfolio — https://github.com/imutwiri/MyPortfolio  
  [![Stars](https://img.shields.io/github/stars/imutwiri/MyPortfolio?style=flat-square)](https://github.com/imutwiri/MyPortfolio) [![Forks](https://img.shields.io/github/forks/imutwiri/MyPortfolio?style=flat-square)](https://github.com/imutwiri/MyPortfolio)
  Top languages: HTML, CSS, JavaScript  
  Highlights:
  - SEO-optimized, server-side rendering and static exports
  - CI: lint, type-check, build, and preview deployments
  - Focus on performance and accessibility  
  Quickstart:
  - git clone https://github.com/imutwiri/MyPortfolio && cd MyPortfolio
  - npm ci && npm run dev

- PCEA Church Management System — https://github.com/imutwiri/PCEA-Church-Management-System  
  [![Stars](https://img.shields.io/github/stars/imutwiri/PCEA-Church-Management-System?style=flat-square)](https://github.com/imutwiri/PCEA-Church-Management-System)  
  Top languages: HTML, CSS  
  Highlights:
  - Role-based access control for members, leaders, and admins
  - Event and donation management, reporting exports (CSV/PDF)
  - Dockerized dev environment and DB migrations  
  Quickstart:
  - docker compose up -d
  - npm ci && npm run migrate && npm run start:dev

- SkillMatch — https://github.com/imutwiri/SkillMatch  
  [![Stars](https://img.shields.io/github/stars/imutwiri/SkillMatch?style=flat-square)](https://github.com/imutwiri/SkillMatch)  
  Top languages: HTML, JavaScript, CSS  
  Highlights:
  - Matching engine for learners and mentors (scoring + recommendations)
  - Background jobs for email notifications and match recalculation (Redis + Bull)
  - Contract tests for API clients  
  Quickstart:
  - git clone https://github.com/imutwiri/SkillMatch && cd SkillMatch
  - docker compose up -d && npm ci && npm run dev

- FarmChain — https://github.com/imutwiri/FarmChain  
  [![Stars](https://img.shields.io/github/stars/imutwiri/FarmChain?style=flat-square)](https://github.com/imutwiri/FarmChain)  
  Top languages: HTML, CSS  
  Highlights:
  - Supply-chain provenance with cryptographic proofs
  - gRPC services with protobuf contracts and backward-compatible changes
  - End-to-end integration tests using containerized infrastructure  
  Quickstart:
  - git clone https://github.com/imutwiri/FarmChain && cd FarmChain
  - make dev (starts deps + services via docker-compose)

- ElimuTech — https://github.com/imutwiri/ElimuTech  
  [![Stars](https://img.shields.io/github/stars/imutwiri/ElimuTech?style=flat-square)](https://github.com/imutwiri/ElimuTech)  
  Top languages: HTML, PHP, Hack, CSS  
  Highlights:
  - EdTech platform with course management and progress tracking
  - Async tasks for email and report generation (Celery + Redis)
  - CI with tests, linting and test coverage reporting  
  Quickstart:
  - git clone https://github.com/imutwiri/ElimuTech && cd ElimuTech
  - docker compose up -d && pip install -r requirements.txt && ./manage.py migrate && ./manage.py runserver

---

## 🧩 Architecture & engineering practices
- Design small, testable services with clear bounded contexts
- Use feature flags and progressive rollouts for risky changes
- Automate local dev, testing, and deployments
- Prioritize observability with traces, metrics, and structured logs

---

## ⚙️ Common developer quickstart (generic)
1. Clone the repo: git clone https://github.com/imutwiri/<repo> && cd <repo>
2. Start infrastructure: docker compose up -d
3. Install & run: npm ci && npm run dev (or follow repo-specific README)
4. Run tests: npm test / go test ./... / pytest

---

## 🤝 Contact & social
- Location: Murang'a, Kenya
- Email: ianmutwiri37@gmail.com
- LinkedIn: https://www.linkedin.com/in/ian-mutwiri-4a842a373/

---

## Contributing
Contributions and issues are welcome. For code changes, open a PR with tests and a clear description. Small, focused PRs are preferred.

---

