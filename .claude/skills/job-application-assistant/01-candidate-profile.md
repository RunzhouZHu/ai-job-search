---
framework_version: 1.1.1
---

# Candidate Profile

<!-- SETUP: This file is populated by running /setup -->
<!-- After running /setup, all sections will be filled with your actual information -->

## Identity
- **Name:** Runzhou Zhu
- **Location:** Kauniainen, Uusimaa, Finland
- **Phone:** +358 41 577 1470
- **Email:** runzhouzhu66@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/runzhou-zhu-4ba50b286
- **GitHub:** https://github.com/RunzhouZHu
- **Status:** IT student at Metropolia University of Applied Sciences, expected graduation September 2027
- **Work authorization:** Finnish residence permit for studies. Paid work in any field averages max 30 h/week (120 h/month, 1,560 h/year); internships and thesis work that are part of the degree are exempt if the credits are agreed beforehand (Migri). See the Eligibility Gate in `04-job-evaluation.md`.
- **Constraints:** [YOUR_COMMUTE_OR_LOCATION_CONSTRAINTS]

### Languages
<!-- Every language you can work in professionally, with your honest level. Used by the
Language Gate in 04-job-evaluation.md and by job-scraper/search-queries.md's query-language
generation. Omit any language you don't actually work in - an undeclared language is treated as
a hard no, not a gap to smooth over. -->

| Language | Level | Notes |
|----------|-------|-------|
| Chinese (Mandarin) | Native | |
| English | Fluent, professional working proficiency | Working language in all Finnish roles to date |
| Finnish | Basic | Not a working language; postings requiring Finnish fail the Language Gate |

## Education

| Degree | Period | Institution | Key Topics |
|--------|--------|-------------|------------|
| Bachelor's degree, Information Technology (**in progress, expected September 2027**) | Aug 2023 - Sep 2027 | Metropolia University of Applied Sciences | GPA 4.75/5 (self-reported on LinkedIn; no transcript on file) |
| Bachelor of Engineering (BE), Mechanical Engineering | Aug 2015 - Sep 2019 | University of Science and Technology Beijing | |

### Certifications
- **AI Agents and Agentic AI with Python & Generative AI** - Vanderbilt University via Coursera (Dr. Jules White) - completed 24 Jul 2026. Verify: https://coursera.org/verify/MMX34IW81HTG

## Professional Experience

### AI-Driven Full-Stack Developer (Trainee) - Design Leaders Finland Oy (Jun 2026 - Aug 2026)
Helsinki. 10-week traineeship, 1 June - 7 August 2026 (per CEO certificate). Wording below follows the certificate: "participated in", not "led".
- Participated in planning, development, testing and delivery of mobile applications built for publication in their app stores
- Used AI-assisted software development and productivity tools in daily development
- Sprint planning, task management and project tracking with GitHub Issues and GitHub Projects in an Agile workflow
- Continuous Integration and automation workflows with GitHub Actions
- Version control best practices, code reviews and collaborative development workflows; modern DevOps practices

**Geowall** (user-confirmed 2026-10-26): mobile app where users pin messages to a GPS location, readable only within a chosen radius. Private repository (code walkthrough / live demo only, with employer permission).
- Main author of the Rust backend: 10 of the 11 backend commits by team members (excluding automated dependency updates)
- Set up the Rust REST API architecture with axum and tokio: configuration, typed error handling (thiserror), structured tracing, health endpoint, pinned toolchain
- Designed the PostgreSQL/PostGIS schema and SQL migrations, accessed from Rust through sqlx; docker-compose local database
- Wrote the OpenAPI 3.0 specification for the message API and implemented its endpoints: radius-based access control, password-locked messages, replies, per-user message lists
- Built Firebase JWT authentication middleware, an event broadcast service for real-time message delivery over WebSockets, a geo-distance service, and a background task that expires old messages
- Wrote integration tests for the HTTP and WebSocket endpoints, the Dockerfile, and a GitHub Actions pipeline running rustfmt, clippy, build and tests on every pull request
- Built Flutter/Dart frontend features (email sign-in flow, message data model and UI) and fixed map-screen bugs
- Used Claude Code for AI-assisted development

### UI/UX Systems Designer & Frontend Engineer - VAA1 project, University of Helsinki (Nexus Incubator) (Oct 2025 - Jan 2026)
Helsinki. 23.10.2025 - 28.1.2026. VAA1 (Video Analysis Automation 1.0) is an open-source, EU-compliant R&D software initiative for automated large-scale video analysis (computational social science, media research, creative industries). Responsible for product interaction design, frontend architecture and workflow design.
- Designed an interactive Figma prototype and iterated it throughout the project lifecycle to align with evolving system requirements
- Developed the frontend with Next.js, TypeScript, Tailwind CSS and Golden Layout, including login interface, dashboard, and result visualization and download workflows
- Implemented an advanced multi-window interactive layout comparable to professional creative software, enabling modular and configurable analytical views
- Designed the core product workflow with user-centered design methods, including use cases and sequence diagrams
- Supported frontend-backend integration planning and API interaction design
- Communicated product concepts and usage to stakeholders

### Game Developer (Intern) - BlendIn Kids (May 2025 - Aug 2025)
Helsinki
- Built a web game in Unity combining language learning, problem solving and town/house building; covered UI design, asset creation and coding
- Built multiple mini-game scenarios and created 2D game assets
- Implemented save/load via HTTP API calls, storing game data online
- Added real-time text-to-speech with an AI plugin so in-game characters speak

### Engineering Blueprint Designer - 上海嘉德环境能源科技有限公司 (Sep 2019 - Jul 2023)
Beijing, China
- [BULLETS_TO_BE_PROVIDED]

## Independent Projects
<!-- Projects outside of employment: freelance, open source, personal -->
- **[PROJECT_NAME]**: [DESCRIPTION]

## Technical Skills

### Programming & ML
- **Rust** (Geowall backend, 10-week traineeship): axum, tokio, sqlx, WebSockets, thiserror, tracing, cargo test, clippy, rustfmt
- **PostgreSQL/PostGIS** (Geowall): schema design, SQL migrations; OpenAPI 3.0; Firebase JWT auth
- **Flutter/Dart** (Geowall frontend features)
- **TypeScript** ([PROFICIENCY]): Next.js, Tailwind CSS, Golden Layout
- **Unity** ([PROFICIENCY]): web game development, HTTP API integration, AI text-to-speech plugin
- **Python** (agentic AI coursework, Vanderbilt/Coursera certificate)
- AI-assisted software development
- UML use cases and sequence diagrams, API interaction design
- [OTHER_SKILLS]

### Domain Expertise
- [DOMAIN_1]
- [DOMAIN_2]

### Software & Tools
- Figma, GitHub (Actions, Issues, Projects), Git, CI/CD, Unity
- [TOOL_LIST]

## Publications
<!-- List peer-reviewed publications, if any -->
1. [AUTHOR_LIST] ([YEAR]). [TITLE]. [JOURNAL]. [DOI_LINK]

## Awards
- [AWARD] - [EVENT] ([YEAR])

## References
- **Petteri Laine**, Founder & Project Lead, Video Analysis Automation 1.0 (VAA1), University of Helsinki (Nexus Incubator) (MarkusPetteriLaine@gmail.com)
  - Job certificate, 28.1.2026: "Mr. Zhu assumed responsibilities typically associated with senior-level technical, product, and research roles and carried them out with composure, professionalism, and intellectual independence." Also: "strong design-engineering integration capability, structured product thinking, and a collaborative working style"; "reliable and capable of delivering high-quality design and frontend engineering outputs under evolving project conditions."
- **Jukka Paasonen**, CEO, Design Leaders Finland Oy (contact details not on file)
  - Traineeship certificate, 7.8.2026: "Runzhou demonstrated a professional attitude, strong commitment to learning, and the ability to adapt to modern development methodologies and technologies."

More references available upon request.
