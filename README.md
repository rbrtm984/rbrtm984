# Rob Mayo

**Full-stack engineer building K-12 education software in TypeScript, Node, and Angular.**

I work on identity and access management at ClassLink, where I'm a top contributor to MyApps, the SSO dashboard about 20 million students and teachers log into daily. I also built the internal agentic development practice our team runs on, a library of custom Claude Code skills plus a self-correcting context-memory system that other engineers adopted as standard workflow.

Before engineering I taught in NYC public schools for four years, including the full COVID remote transition. The classroom side of education software isn't abstract to me.

New York, NY · rbrtm984@gmail.com · [LinkedIn](https://www.linkedin.com/in/robertcmayo/)

---

## Currently

- Building **[agent-skills repo name]**, an open set of Claude Code skills and a memory pattern for keeping agents honest across long sessions
- Writing up the architecture behind the production systems I've shipped → **[selected-work](https://github.com/rbrtm984/selected-work)**
- Finishing a BS in Computer Science at WGU, expected 5/2027

---

## What I've shipped

**Production scale.** MyApps serves 20M+ daily users across SAML, OAuth2, OpenID, LTI, and OneRoster. I authored the universal app-launch endpoint that unified launch behavior across 40+ applications and SSO types, and I share ownership of the backend surface.

**AI in a product, not just in my editor.** Icon Builder is a full-stack tool that lets school administrators generate custom icon artwork through the Gemini API. Angular frontend with signal-based undo/redo and a canvas export pipeline, Node/Express/PostgreSQL backend, S3 storage. It replaced a manual support workflow end to end. 31 test files, 302 test cases, including a Playwright e2e suite.

**Agentic development as a team practice.** A size-triaged ticket orchestration spec, a pre-commit review rubric, commit and branch standards, and a memory system that corrects itself when it drifts. The interesting problem wasn't prompting. It was building enough structure that other engineers could get consistent results without babysitting the agent.

**Testing that didn't exist before.** Migrated MyApps from Karma/Jasmine to Vitest, removed about 100 broken legacy specs, and wrote the team's testing documentation.

---

## Stack

**Languages** TypeScript · JavaScript · Python · SQL

**Frontend** Angular (signals, RxJS, standalone components, Module Federation) · React (Vite, Tailwind, TanStack Query, Zustand, Next.js, Redux) · PWA · i18n · WCAG/ARIA

**Backend** Node · Express · Inversify DI · FastAPI · REST/OpenAPI

**Data & infra** PostgreSQL · MySQL · Redis · AWS (Lambda, S3, EventBridge, SNS, ECS, CodeBuild, IAM) · Docker

**Auth** OAuth2 · SAML · OpenID · LTI · OneRoster · JWT · multi-tenant isolation

**Testing** Vitest · Playwright · Jest · Mocha/Chai/Sinon · React Testing Library

**AI** Claude Code · MCP · Gemini API · agentic workflows · custom skills

---

Open to full-time roles, remote or NYC. Reach me at rbrtm984@gmail.com.

Elsewhere: horror movies, mostly.
