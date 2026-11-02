# Danylo Shelemonchak

Senior Angular developer and full-stack engineer (Node.js, Java/Spring) with six years of commercial experience.
Based in Ukraine (EET), open to remote roles.

![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=flat&logo=reactivex&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=spring&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=flat&logo=sass&logoColor=white)

## Experience

Outstaff developer for one company, remote, October 2020 to September 2026.

### Senior Frontend Developer, fintech (2022 to 2026)

A financial planning product made up of five Angular applications, a shared component library and a Java/Spring
backend.

- Designed state persistence for a long multi-step flow, so users resume where they left off.
- Co-wrote the event bus that connects features within the app.
- Built keyboard-first input across 28 forms: an on-screen keyboard, Enter-to-advance navigation and a custom Tab
  order, with workarounds for iOS focus limitations.
- Built a Canvas 2D signature-capture component from scratch.
- Extracted components into the shared library, versioned them and rolled them out to all five apps.
- Fixed bugs in the Java/Spring backend, mainly in persistence, email delivery and localisation.
- Mentored a junior developer and reviewed teammates' pull requests.

### Frontend Developer, healthcare (2021 to 2022)

A CRM for nursing homes.

- Built staff-facing interfaces for desktop and iPad, with validated forms and Jest tests.
- Owned features end to end on Spring Boot, from database tables to REST endpoints.

### Frontend Developer, education (2020 to 2021)

A CRM for language schools.

- Built chat, scheduling and attendance from scratch.
- Moved the interface from MDB to ng-bootstrap.
- Built role-based access, localisation and REST endpoints on Spring Boot.

## Open-source project: Markup Résumé

[markup-resume](https://github.com/dshelemonchak/markup-resume) is a workspace for tailoring CVs with an AI assistant.
I am the sole developer and own the architecture, database schema and security model (documented in ADRs). I build
it with AI coding assistants and review all generated code.

- Node.js 24 and PostgreSQL backend with hexagonal architecture, append-only revision history and row locks for
  concurrent edits. Unit and integration tests run in GitHub Actions.
- GitHub sign-in with server-side sessions and per-user data isolation.
- MCP server that lets AI assistants read and edit CVs.
- Angular 22 client with live updates over server-sent events.
- PDF export through headless Chrome, checked against the rendered page for missing text, reading order, fonts and
  links.

## Contact

[LinkedIn](https://www.linkedin.com/in/danylo-shelemonchak/)
