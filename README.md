# Daniel Rosemann
**FISI trainee (2nd year) near Frankfurt | Infrastructure, hosting, automation**
daniel.rosemann10@gmail.com

Hands-on infrastructure generalist self-hosting since 2018. Private lab experience predates my Ausbildung; in Betrieb I work on the company stack. I run production game-server infrastructure, automate with Python, and document reliably.

## Private lab skills (pre-training)
- **Systems & virtualization:** Linux, Docker, Proxmox, KVM / libvirt, Windows client (switch to Linux planned once anticheat support improves)
- **Web & infra:** NGINX, Apache, Velocity, Cloudflare (DNS), HetrixTools (monitoring), Vercel (auto-deploys)
- **Data:** MariaDB (production experience), Supabase (cloud + self-hosted, evaluated)
- **Development:** HTML, CSS, JavaScript, Java, PHP, Python, React / TUI basics
- **Panels (experienced, now prefer pure Docker):** Pterodactyl, Coolify
- **Ops habits:** Trello + Notion for project tracking, backups with integrity checks, dev / failover / main setups
- **Focus:** cybersecurity, AI applied to ops, cloud & virtualization, Python automation

## Experience
- **ShadowUnity (since 22 Apr 2018)** — `play.shadowunity.de`, no world reset since 2022. Full stack: provisioning, Docker workloads, DNS, monitoring, backups, forum + guestbook on `shadowunity.de`. Started with CityBuild and minigames, now focused on community, technology, and events — quality over quantity.
- **Hosting path (private lab):** Aternos → Ploudos → Minehub (later closed) → DeinServerHost → Strato → Host-Unlimited → LuxVPS → Mine-Hoster → ST-Hosting (one month, LXC did not meet requirements) → HT-Hosting (provider insolvency — learned migration under time pressure) → Index Hosting (until mid-March, AMD EPYC lineup discontinued, currently searching). Tested Vercel and Kinsta for developer experience with edge + CDN; self-hosting cheaper long-term. At times ran 3–4 servers in parallel as dev / failover / main.
- **DMH Network (24 Jan 2025 – 26 Apr 2025)** — co-ran a Minecraft network with Matti and Henry; left to focus on vocational training.
- **Helpdesk internships (3x, pre-training)** — two school internships + one voluntary internship, all helpdesk support.
- **Content & community (multi-year)** — 2,000+ videos produced, hundreds of hours streamed live. Skills: community building, live ops, video production, consistency, feedback handling. Later 15 videos in fast-cut tech-take style, kept as an archive to evaluate future direction.
- **Super-app consolidation (current)** — merging years of standalone builds into one cohesive platform with shared identity/data and microservices. Phased approach: social core first (posts / follows / profiles), then chats / groups, then mini-apps. Principle: merge or archive, never delete features.

## Archived private builds (full detail, pre-training)
- **VPS management tooling + dashboard** — TypeScript, Python, React/Express, Docker. Internal control plane for own VPS and container fleet: management panel, Python orchestrator agent with GitOps reconciliation, Typer-based CLI, optional Discord and monitoring profiles. Grew out of earlier hosting-network experiments. Planned base for a future hosting company.
- **Game-server plot system (Java/Maven, Paper 1.16.5)** — first commit 01 Feb 2025, 28 files. Randomly scattered protected plots in a normal world instead of a grid, connected by auto-generated paths, with districts, clans, market, plot upgrades, YAML + SQLite storage. Inspired by city-build gameplay.
- **Blog CMS (Flask + MariaDB, Docker)** — auth, draft / scheduled / published / archived workflow, Markdown, media uploads, single-server and multi-instance behind NGINX. Intended for portfolio and server news once an Impressum is available (held back in Germany due to Abmahn risk).
- **Local AI chat UI (pure JS, no framework)** — privacy-focused Ollama WebUI, `index.html` against `http://localhost:11434`. Started Mar 2025 from three files, grew into a workspace with projects, tasks, memory, multiple chats, and user accounts on self-hosted Supabase. For sensitive local use; cloud models for everything else.
- **Browser survival game (vanilla HTML/CSS/JS, Canvas)** — wave survival with WASD + mouse aim, coin-funded upgrades, localStorage highscore. No backend, no build step. Only project with Vercel auto-deploys. Next experiment: parallel agents for audio/UI, gameplay, and balancing with automated browser tests.
- **Cross-device screen sharing (Flutter, WebRTC, Node.js signaling)** — multi-user control and app-level sharing instead of plain desktop mirroring, with browser web client and Docker-ready signaling. Idea from a family vacation; briefly renamed, then reverted.
- **Offline-first docs workspace (React TUI, Vite)** — Markdown workspace with ed/vi habits (`i`, `a`, `Esc`, `:w`). No account, server, or sync; documents in browser localStorage, app shell cached by service worker, `.md` export as backup. History: 2013 ed sources, modernized May 2026, rebranded Oct 2026.
- **Stock explanations (stdlib Python + SQLite)** — SEC EDGAR filings, prices, optional earnings transcripts for 100 US companies into plain German explanations. Server-rendered pages + JSON API, optional local Ollama explanations. No investment advice.
- **Satire programming language (C, libc + GCC only)** — compiles its own files to C, with explain mode and a rewriter. Deliberately endless enterprise constructs, documented as jokes.
- **Forum + blog merge (Next.js, SQLite dev / MariaDB prod, Docker)** — merged ten earlier forum/blog attempts into one self-hosted codebase. Ten dead forums in, one nerd forum out.
- **Small self-hosted services** — URL shortener (PHP, MariaDB, NGINX, Docker), encrypted notes API (Node.js, MariaDB, AES-256, REST), event planner (React + Node/Express + MariaDB, JWT + bcrypt).
- **Other lab work** — VPS hardening automation (SSH, firewall, fail2ban, web stack, SSL, monitoring, backups), chat-ops server automation via panel API, sensor + AI plant-monitoring prototype, hardware hacking and applied AI-security work.
- **Game plugins** — free plugins published under an earlier alias; full history preserved in the super-app monorepo.
- **Long-term game project** — roleplay server contribution since Sep 2023 (police, SWAT, paramedic, fire, wanted/economy/vehicle systems).

## Server name history (ShadowUnity, since 2018)
1. Pocket-edition server inspired by smaller PE servers and large city-build networks
2. First Java server, CityBuild only
3. Named after my in-game name at the time
4. Personal-brand phase
5. Inspired by a minigames network
6. **ShadowUnity** — stable final name (earlier gaming alias + community)

## Video archive (15 tech-take videos, former gaming channel)
Topics included cloud security, IT trends, cloud models, short-form platform drama, browser-company decline, cloud gaming, AI agents, 3D + AI, multimodal models, open-source AI, AI advertising, AI safety, ransomware in healthcare, AGI timelines, and robotaxis. Seven files were compressed to fit hosting upload limits (25 MB browser / 100 MB push).

| Video | Before | After |
| :--- | ---: | ---: |
| Cloud security | 26.1 MB | 23.8 MB |
| IT trends | 32.3 MB | 23.7 MB |
| Short-form platform drama | 30.6 MB | 23.8 MB |
| Browser decline | 25.5 MB | 24.1 MB |
| Cloud gaming | 41.3 MB | 23.8 MB |
| AI agents | 30.8 MB | 24.2 MB |
| 3D + AI | 25.9 MB | 23.7 MB |

## Domains & presence
- `d5niel.de` — Portfolio domain
- `shadowunity.de` — game-server project
- `hosting-club.de` — former hosting forum, closed after one year to focus on training

## Open to
Junior sysadmin / hosting ops / DevOps support roles, Frankfurt or remote. Happy to share runbooks, monitoring setups, and migration notes on request.
