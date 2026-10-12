# Hi, I'm David

CEO and owner of **[Breathe IT](https://breathe.no)**, a Microsoft consultancy in Stavern, Norway.

We're a small team that ships like a much larger one. That isn't because of a chatbot on the side. AI agents are part of how the company runs: humans own priorities, decisions and acceptance, and agents do a large share of the planning, coding, testing and review, under guardrails we've written down and enforce.

### How we work: agent-native delivery

- **Claude Code and Codex as teammates, with roles.** Each kind of work gets a matching model: one for architecture and hard bugs, one for everyday coding and tests, a lightweight one for exploration and log triage, and a deep-planning model only when someone explicitly asks for it. Every workstation runs the same shared defaults through our own plugin and managed org settings.
- **GitHub is the shared memory.** Issues, Projects and PRs are the record, not the chat. Every handoff between humans, Claude and Codex includes the issue, the exact commit, the scope, the acceptance criteria, the test evidence and any blockers.
- **A bounded review budget.** At most two reviewers per round and two rounds per task. Claude and Codex review each other's code, and findings are verified before anyone sees them. This keeps review rigorous without endless loops.
- **Bounded autonomy.** Agents work issue queues in isolated worktrees with task, time and cost limits. A real blocker gets marked `needs-human`. Agents never push to `main`, never touch production secrets and never treat a generated PR as "done".
- **Quality gates before UAT.** A ten-gate framework covers code review, security, GDPR, environment parity, observability, backup/DR, performance, accessibility, operational readiness and sign-off.
- **Evidence over claims.** Tests have to fail before a fix. Load-bearing guarantees are mutation-checked. A skipped or failed check is never reported as passing.

### What we build

- **Dynamics 365**: Finance & Operations, Sales and Customer Service
- **Power Platform & Dataverse**: apps, automation and data models
- **Azure integrations**: APIs, messaging, and public-sector integrations (Maskinporten/Altinn)
- **AI on Azure**: Microsoft Foundry model deployments, Copilot Studio agents, and Claude-based tooling in client environments
- **Our own platform**: a model-driven, Dataverse-style application engine (Next.js, TypeScript, Azure SQL, Entra ID) with versioned modules for CRM, service, field service, subscriptions, HR and projects

### What I'm working on

- **Breathe AI Launchpad**: a customer-installed AI delivery environment on Azure, with model choice per role and agent workers running inside the client's own tenant
- **An open-source Claude skill for Dynamics 365 / Dataverse** that lets you query and update CRM data in plain language, with each user acting under their own D365 security roles
- **Lead generation on the Brønnøysund registry**: pipelines built on Norwegian business data
- **Productized consulting**: fixed-scope packages and Expert-as-a-Service, delivered with the same agent-native engine

### Talk to me about

Agentic software delivery in a real consultancy · Dynamics 365 / Dataverse architecture · putting AI into regulated or public-sector environments safely · turning client work into reusable IP

### Reach me

- [david@breathe.no](mailto:david@breathe.no) · +47 413 82 965
- [breathe.no](https://breathe.no)
