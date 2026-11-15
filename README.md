# Víctor Calderón Oyarce 👋

### Senior Full Stack Engineer · TypeScript · NestJS · Angular · Google Cloud
### Founder of <img src="https://resources.gridtechnologies.cl/brand/grid-tiles.svg" alt="" height="18" align="center"> [Grid Technologies](https://gridtechnologies.cl) · Creator of <img src="https://gridradar.cl/grid-radar.svg" alt="" height="18" align="center"> [Grid Radar](https://gridradar.cl)

<p>
  <a href="https://vcalderon.dev"><img alt="Website" src="https://img.shields.io/badge/vcalderon.dev-15243b?style=flat-square&logo=googlechrome&logoColor=white"></a>
  <a href="https://gridradar.cl"><img alt="Grid Radar" src="https://img.shields.io/badge/Grid_Radar-0ea5e9?style=flat-square&logo=chartdotjs&logoColor=white"></a>
  <a href="https://gridtechnologies.cl"><img alt="Grid Technologies" src="https://img.shields.io/badge/Grid_Technologies-1f6fb2?style=flat-square&logo=icloud&logoColor=white"></a>
  <a href="https://lpsx.vcalderon.dev"><img alt="Lumen PSX" src="https://img.shields.io/badge/Lumen_PSX-003791?style=flat-square&logo=playstation&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/vcalderondev/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:mail@vcalderon.dev"><img alt="Email" src="https://img.shields.io/badge/mail@vcalderon.dev-5a6472?style=flat-square&logo=gmail&logoColor=white"></a>
</p>

🇨🇱 **Constitución, Chile** — open to relocating to Santiago · **Remote or hybrid**
💼 Company: **[Grid Technologies SpA](https://gridtechnologies.cl)** · 🎯 Main product: **[Grid Radar](https://gridradar.cl)** · 🌐 **[vcalderon.dev](https://vcalderon.dev)**

---

## 👨‍💻 About me

**Full stack engineer with 13 years of experience**, **8 of them as technical lead** of a platform. I design and operate distributed platforms on end-to-end **TypeScript** —NestJS and Node.js on the backend, Angular on the frontend, **Google Cloud** for infrastructure— with **hexagonal architecture, DDD and event-driven architectures**.

I put **generative AI into real business flows, not prototypes**: LLM agents grounded on the database, function calling with strict input and output contracts, schema validation, and control over latency and cost.

* 🏗️ **Architecture:** hexagonal (ports and adapters), DDD, microservices, SSOT contracts between frontend and backend, idempotent events and retries with backoff.
* 🤖 **Applied AI:** Vertex AI + Gemini in production, LLM agents, RAG, embeddings, AI-driven data normalization and matching.
* ☁️ **Cloud:** GCP (GKE, Cloud Run, Cloud Functions, Pub/Sub, Dataflow, Cloud Scheduler, Cloud SQL, BigQuery), Docker, Kubernetes, CI/CD.
* 🧪 **Quality:** Clean Code, SOLID, unit and integration tests with Jest, Vitest and Playwright as the gate before production.

---

## <img src="https://resources.gridtechnologies.cl/brand/grid-tiles.svg" alt="" height="18" align="center"> Grid Technologies — my company

I founded **[Grid Technologies SpA](https://gridtechnologies.cl)** (Santiago, Chile) to **modernize businesses that still run on spreadsheets and legacy systems**: custom software, automation and **applied AI**.

The whole ecosystem lives in a distributed, decoupled architecture on one shared technical foundation: **hexagonal architecture and DDD**, shared contracts as SSOT, **GCP** (Cloud Run, Cloud SQL PostgreSQL, Pub/Sub, Cloud Scheduler) and **event-driven flows**.

### Platforms & Solutions

| Platform | What it solves |
|---|---|
| <img src="https://gridradar.cl/grid-radar.svg" alt="" height="18" align="center"> **[Grid Radar](https://gridradar.cl)** | **B2B competitive price intelligence (flagship product).** Real-time cross-retailer monitoring, stock-out detection, MAP auditing, strategic recommendations for e-commerce and an **official agentic MCP server** for interoperability with AI agents. Resilient, on-demand serverless extraction on Google Cloud. |

> **Product focus:** Grid Technologies concentrates its commercial offering exclusively on **[Grid Radar](https://gridradar.cl)**, backed by high-fidelity internal infrastructure (unified identity with Grid Accounts, transactional messaging and serverless orchestration on Google Cloud).

---

## 🚀 My own products

### <img src="https://pseudoide.dev/favicon.svg" alt="" height="18" align="center"> [PseudoIDE](https://pseudoide.dev) — Pseudocode IDE with its own interpreter
A complete IDE for learning to program in Spanish, free, on web and desktop.
Built end to end: a **pseudocode interpreter with OOP support**, a
**transpilation layer to JavaScript running in Web Workers**, a **step-by-step debugger** with
variable inspection, live **flowchart generation**, a **Monaco** editor with custom language
providers, **Git** integration over IPC and real-time file watching.

Distributed on **web, Windows, macOS and Linux** (installer, AppImage and .deb) with an
auto-updater and Spanish/English i18n. 15 versioned releases with a
[public changelog](https://pseudoide.dev/en/changelog).

`Angular` · `Electron` · `TypeScript` · `Monaco` · `Web Workers` · `Cloudflare R2`

### [@vcalderondev/ukit-css](https://www.npmjs.com/package/@vcalderondev/ukit-css) — Utility-first JIT CSS engine
My own engine, published on npm: it scans the source code, extracts only the classes actually
in use and emits just that CSS. It ships a CLI, a Vite plugin and a PostCSS plugin, and
works with React, Vue, Angular, Svelte, Next.js, Astro and plain HTML.

In a project with 46 distinct utilities it emits **~2.4 KB minified**, against the
~770 KB of a static utility library. In production inside PseudoIDE.

`Node.js` · `TypeScript` · `PostCSS` · `Vite`

---

## 🎮 Open source

### <img src="https://lpsx.vcalderon.dev/brand/favicon.svg" alt="" height="18" align="center"> [Lumen PSX](https://lpsx.vcalderon.dev) — 3D game frontend for the PlayStation Classic
A fast, lightweight frontend written in C for Sony's PlayStation Classic: a **3D jewel-case
carousel in OpenGL ES 3.0** with spring physics, lighting and floor reflections, in a
**single ~75 KB binary**. It launches games in RetroArch and returns to the same game
afterwards, with favourites, folders, profiles, themes and a UI translated into six languages.

It brings its own modern system stack, built from upstream sources by
[psc-platform](https://github.com/vcalderondev/psc-platform) (cross toolchain included):
**Wayland 1.26, Weston 16 and RetroArch 1.22** on a console that ships with Wayland 1.12 and
Weston 1.11. It runs from a USB stick on any stock console and **writes nothing to internal
memory**: the stack is unpacked to RAM at every boot and overlaid on `/usr`.

Source on [GitHub](https://github.com/vcalderondev/lumen-psx) (GPLv3), with animated
backgrounds contributed through [lumen-scenes](https://github.com/vcalderondev/lumen-scenes).

`C` · `OpenGL ES` · `SDL2` · `Wayland` · `Embedded Linux` · `ARM cross-compilation`

---

## 🛠️ Technologies & Tech Stack

### 💻 Architecture & Development
* **Architecture:** hexagonal (ports and adapters), DDD, microservices, SSOT contracts, event-driven architectures (EDA), idempotency and retries
* **Backend:** Node.js, NestJS, TypeScript, Express, TypeORM, REST APIs, OAuth2/OIDC and SSO
* **Frontend:** Angular (standalone + signals), React, Electron, Capacitor, Monaco Editor, SASS, Tailwind CSS, i18n
* **Databases:** PostgreSQL, AlloyDB, MySQL, MariaDB, BigQuery, Redis
* **Testing:** Jest, Vitest and Playwright
* **Systems:** C, OpenGL ES, SDL2, embedded Linux, cross-compilation for ARM

### 🤖 Applied Artificial Intelligence
* Google Cloud **Vertex AI** / Generative AI Studio · **Gemini** · embeddings
* **LLM agents grounded** on the database, function calling and strict input/output contracts
* **RAG**, AI-driven data normalization and matching
* Custom **MCP server** and multi-agent orchestration

### ☁️ Cloud & DevOps
* **Platform:** Google Cloud Platform (GKE, Cloud Run, Cloud Functions, **Pub/Sub**, **Dataflow**, **Cloud Scheduler**, Cloud SQL, BigQuery)
* **Containers:** Docker, Kubernetes (GKE) · **CDN:** Cloudflare
* **CI/CD:** GitHub Actions and Google Cloud Build

---

## 📬 Let's connect

If you are interested in cloud architecture, AI applied to real business, or market intelligence with Grid Radar:

<table>
  <tr><td align="center">🌐</td><td><strong>Personal site</strong></td><td><a href="https://vcalderon.dev">vcalderon.dev</a></td></tr>
  <tr><td align="center"><img src="https://gridradar.cl/grid-radar.svg" alt="" width="20" height="20"></td><td><strong>Grid Radar</strong></td><td><a href="https://gridradar.cl">gridradar.cl</a></td></tr>
  <tr><td align="center"><img src="https://resources.gridtechnologies.cl/brand/grid-tiles.svg" alt="" width="20" height="20"></td><td><strong>Grid Technologies</strong></td><td><a href="https://gridtechnologies.cl">gridtechnologies.cl</a></td></tr>
  <tr><td align="center"><img src="https://pseudoide.dev/favicon.svg" alt="" width="20" height="20"></td><td><strong>PseudoIDE</strong></td><td><a href="https://pseudoide.dev">pseudoide.dev</a></td></tr>
  <tr><td align="center"><img src="https://lpsx.vcalderon.dev/brand/favicon.svg" alt="" width="20" height="20"></td><td><strong>Lumen PSX</strong></td><td><a href="https://lpsx.vcalderon.dev">lpsx.vcalderon.dev</a></td></tr>
  <tr><td align="center">💼</td><td><strong>LinkedIn</strong></td><td><a href="https://www.linkedin.com/in/vcalderondev/">linkedin.com/in/vcalderondev</a></td></tr>
  <tr><td align="center">✉️</td><td><strong>Email</strong></td><td><a href="mailto:mail@vcalderon.dev">mail@vcalderon.dev</a></td></tr>
</table>

<sub>PseudoIDE and @vcalderondev/ukit-css are my own independent products. Lumen PSX is a personal open-source project, not affiliated with Sony. Grid Radar is a platform of Grid Technologies SpA.</sub>
