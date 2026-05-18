# Hi, I'm Daniel 👋

I'm a software engineer specialising in **event-driven microservice architecture**.I design distributed systems around asynchronous messaging, bounded contexts, and domain events rather than direct coupling. I care about building services that are independently deployable, resilient to failure, and performant at scale.

Day-to-day I work in ed-tech, leading integration architecture and data pipeline work for student information systems. Outside of that I'm usually building something that scratches an itch: Electron desktop apps, game server tooling, self-hosted infrastructure, or SaaS ideas I want to validate quickly.

---

## What I work with

| Layer | Stack |
|---|---|
| **Architecture** | Event-driven microservices · async messaging · saga orchestration · CQRS |
| **Languages** | TypeScript / JavaScript · C# / .NET · Rust · Currently learning Python |
| **Backend** | Node.js · Express · .NET Core |
| **Frontend** | React · Vite · Next.js · Tailwind CSS · Blazor |
| **Desktop** | Electron · WPF · Avalonia |
| **Databases** | MSSQL Server · PostgreSQL · MySQL · SQLite · Redis |
| **Messaging** | Azure Service Bus · RabbitMQ |
| **Infra / DevOps** | Docker · Coolify · Hetzner · Nginx · Azure DevOps · Application Insights |
| **Game Server & Mods** | Oxide / uMod (C#) · SteamCMD · Dedicated server ops (ARK, Rust, Enshrouded, Minecraft, Conan Exiles) |

---

## Projects (Public & Private)

### ARK Mod Manager (ARKForge)
Full-stack web application for managing ARK: Survival Ascended mods. You can browse the CurseForge catalogue, build, share and browse ordered mod lists/collections with drag-and-drop, and export server configs. React 18 + Vite frontend, Express + Sequelize + MySQL backend, JWT auth, bcrypt, rate limiting, and admin scraping controls.

### Crimson Desert UI Editor
Electron desktop toolkit that extracts, decrypts, and repacks ~1.5 million files from Crimson Desert's proprietary `.paz` archives. Implements ChaCha20 decryption and LZ4 decompression in pure JavaScript (no native bindings), handles DDS texture assets, and surfaces everything through an Electron GUI with an IPC-bridged Node.js core.

### Alternaleaf Repeat Browser
npm workspace monorepo for browsing medical cannabis products with terpene-based recommendations. Three packages share a single Drizzle ORM schema: an Express + PostgreSQL API, a Vite + React frontend, and a separate Electron admin tool with a Puppeteer scraper. OAuth2 login (Google + Discord), JWT auth, and product data syncing from a third-party store.

### Stratum
Early-stage SaaS for validating startup ideas by continuously monitoring Reddit, GitHub Issues, App Store reviews, Product Hunt, and X for recurring complaints and unmet needs. Event-driven ingestion pipeline feeding NLP clustering (OpenAI embeddings / sentence-transformers), with problems ranked by frequency, engagement, and monetisation signal across configurable workspaces.

### Duckov Mod Manager
Cross-platform Electron desktop app for managing Escape from Duckov mods with offline-first translation (most Duckov mod creators are Chinese). Downloads and runs local ML models (~500MB–1GB) so all translation happens on-device with no internet dependency. This works against a downloaded copy of the Duckov mods available in Steam Workshop.

### Mod Suite for Rust
Rust game server plugin suite (Oxide/C#) built around a RuneScape-inspired RPG framework. Fourteen cooperating modules cover character progression (XP, 10 skills, 28 perks, skill milestones), a custom HUD, a unified in-game admin panel, server configuration, and wipe protection (players, blueprints, player locations, and bases all persist after a forced wipe). All modules communicate through a shared core. Designed for private Rust servers where long-term player investment matters.

### FourTwenty.Games
Self-hosted gaming community infrastructure running on a Hetzner root server. Services include a forum, blog, and various game servers. All orchestrated via Coolify with Nginx reverse proxies and Let's Encrypt TLS. Built and maintained as a personal platform for gaming, writing, and server experimentation.

---

## A bit more about me

- Based in **Liverpool, UK**
- Neurodivergent (autism + ADHD) — I tend to hyperfocus hard on interesting problems and build things end-to-end before moving on
- I run game servers for fun and have done for years; the line between hobby and side project is blurry.
