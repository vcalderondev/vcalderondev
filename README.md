# Víctor Calderón Oyarce 👋

### Senior Full Stack Engineer · TypeScript · NestJS · Angular · Google Cloud
### Fundador de [Grid Technologies](https://gridtechnologies.cl) · Creador de [Grid Radar](https://gridradar.cl)

<p>
  <a href="https://vcalderon.dev"><img alt="Sitio" src="https://img.shields.io/badge/vcalderon.dev-15243b?style=flat-square&logo=googlechrome&logoColor=white"></a>
  <a href="https://gridradar.cl"><img alt="Grid Radar" src="https://img.shields.io/badge/Grid_Radar-0ea5e9?style=flat-square&logo=chartdotjs&logoColor=white"></a>
  <a href="https://gridtechnologies.cl"><img alt="Grid Technologies" src="https://img.shields.io/badge/Grid_Technologies-1f6fb2?style=flat-square&logo=icloud&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/vcalderondev/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:mail@vcalderon.dev"><img alt="Email" src="https://img.shields.io/badge/mail@vcalderon.dev-5a6472?style=flat-square&logo=gmail&logoColor=white"></a>
</p>

🇨🇱 **Constitución, Chile** — disponible para trasladarme a Santiago · **Remoto o híbrido**
💼 Empresa: **[Grid Technologies SpA](https://gridtechnologies.cl)** · 🎯 Producto Principal: **[Grid Radar](https://gridradar.cl)** · 🌐 **[vcalderon.dev](https://vcalderon.dev)**

---

## 👨‍💻 Sobre mí

**Full stack engineer con 13 años de experiencia** y **8 como responsable técnico** de plataforma. Diseño y opero plataformas distribuidas sobre **TypeScript** de punta a punta —NestJS y Node.js en backend, Angular en frontend, **Google Cloud** en infraestructura— con **arquitectura hexagonal, DDD y arquitecturas basadas en eventos**.

Integro **IA generativa en flujos de negocio reales, no en prototipos**: agentes LLM con *grounding* sobre la base de datos, *function calling* con contratos estrictos de entrada y salida, validación de esquema y control de latencia y costo.

* 🏗️ **Arquitectura:** hexagonal (puertos y adaptadores), DDD, microservicios, SSOT de contratos entre frontend y backend, eventos con idempotencia y reintentos con *backoff*.
* 🤖 **IA aplicada:** Vertex AI + Gemini en producción, agentes LLM, RAG, *embeddings*, normalización y *matching* de datos por IA.
* ☁️ **Cloud:** GCP (GKE, Cloud Run, Cloud Functions, Pub/Sub, Dataflow, Cloud Scheduler, Cloud SQL, BigQuery), Docker, Kubernetes, CI/CD.
* 🧪 **Calidad:** Clean Code, SOLID, pruebas unitarias y de integración con Jest, Vitest y Playwright como puerta previa a producción.

---

## 🏢 Grid Technologies — mi empresa

Fundé **[Grid Technologies SpA](https://gridtechnologies.cl)** (Santiago de Chile) para **modernizar negocios que aún corren en planillas y sistemas viejos**: software a medida, automatización e **IA aplicada**.

Todo el ecosistema vive en una arquitectura distribuida y desacoplada sobre una misma base técnica: **arquitectura hexagonal y DDD**, contratos compartidos como SSOT, **GCP** (Cloud Run, Cloud SQL PostgreSQL, Pub/Sub, Cloud Scheduler) y **flujos basados en eventos**.

### Plataformas & Soluciones

| Plataforma | Qué resuelve |
|---|---|
| **[Grid Radar](https://gridradar.cl)** | **Inteligencia competitiva de precios B2B (Producto Insignia).** Monitoreo cross-retailer en tiempo real, detección de quiebres de stock, auditoría MAP, recomendaciones estratégicas para e-commerce y **servidor agéntico MCP oficial** para interoperabilidad con agentes de IA. Extracción serverless resiliente bajo demanda sobre Google Cloud. |
| **[Grid Accounts](https://accounts.gridtechnologies.cl)** | **Identidad y gobernanza central (Capa Interna).** Proveedor unificado de identidad **OAuth2/OIDC** (RS256/JWKS, **WebAuthn/Passkeys** y **TOTP**), catálogo de servicios y motor central de facturación y suscripciones recurrentes que sostiene el acceso a Grid Radar. |

> **Enfoque de producto:** Grid Technologies concentra su oferta comercial exclusivamente en **[Grid Radar](https://gridradar.cl)**, respaldada por una infraestructura interna de alta fidelidad (identidad unificada con Grid Accounts, mensajería transaccional y orquestación serverless en Google Cloud).

---

## 🚀 Productos propios

### [PseudoIDE](https://pseudoide.dev) — IDE de pseudocódigo con intérprete propio
Un IDE completo para aprender a programar en español, gratuito, en web y escritorio.
Construido de principio a fin: **intérprete de pseudocódigo con soporte de POO**, capa de
**transpilación a JavaScript en Web Workers**, **depurador paso a paso** con inspección de
variables, **generación de diagramas de flujo** en vivo, editor **Monaco** con language
providers propios, integración **Git** por IPC y vigilancia de archivos en tiempo real.

Distribuido en **web, Windows, macOS y Linux** (instalador, AppImage y .deb) con
auto-updater e i18n español/inglés. 15 releases versionadas con
[changelog público](https://pseudoide.dev/es/changelog).

`Angular` · `Electron` · `TypeScript` · `Monaco` · `Web Workers` · `Cloudflare R2`

### [@vcalderondev/ukit-css](https://www.npmjs.com/package/@vcalderondev/ukit-css) — Motor JIT de CSS utility-first
Motor propio publicado en npm: escanea el código fuente, extrae solo las clases realmente
usadas y emite únicamente ese CSS. Incluye CLI, plugin de Vite y plugin de PostCSS, y
funciona con React, Vue, Angular, Svelte, Next.js, Astro y HTML plano.

En un proyecto con 46 utilidades distintas emite **~2,4 KB minificados** frente a los
~770 KB de una librería de utilidades estática. En producción dentro de PseudoIDE.

`Node.js` · `TypeScript` · `PostCSS` · `Vite`

---

## 🛠️ Tecnologías & Stack Técnico

### 💻 Arquitectura & Desarrollo
* **Arquitectura:** hexagonal (puertos y adaptadores), DDD, microservicios, SSOT de contratos, arquitecturas basadas en eventos (EDA), idempotencia y reintentos
* **Backend:** Node.js, NestJS, TypeScript, Express, TypeORM, APIs REST, OAuth2/OIDC y SSO
* **Frontend:** Angular (standalone + signals), React, Electron, Capacitor, Monaco Editor, SASS, Tailwind CSS, i18n
* **Bases de Datos:** PostgreSQL, AlloyDB, MySQL, MariaDB, BigQuery, Redis
* **Testing:** Jest, Vitest y Playwright

### 🤖 Inteligencia Artificial aplicada
* Google Cloud **Vertex AI** / Generative AI Studio · **Gemini** · *embeddings*
* **Agentes LLM con *grounding*** sobre base de datos, *function calling* y contratos estrictos de entrada/salida
* **RAG**, normalización y *matching* de datos por IA
* **Servidor MCP** propio y orquestación multi-agente

### ☁️ Cloud & DevOps
* **Plataforma:** Google Cloud Platform (GKE, Cloud Run, Cloud Functions, **Pub/Sub**, **Dataflow**, **Cloud Scheduler**, Cloud SQL, BigQuery)
* **Contenedores:** Docker, Kubernetes (GKE) · **CDN:** Cloudflare
* **CI/CD:** GitHub Actions y Google Cloud Build

---

## 📬 Conectemos

Si te interesa la arquitectura cloud, la IA aplicada a negocio real o la inteligencia de mercado con Grid Radar:

* 🌐 **Sitio personal:** [vcalderon.dev](https://vcalderon.dev)
* 🎯 **Grid Radar:** [gridradar.cl](https://gridradar.cl)
* 🏢 **Grid Technologies:** [gridtechnologies.cl](https://gridtechnologies.cl)
* 🚀 **Producto propio:** [pseudoide.dev](https://pseudoide.dev)
* 💼 **LinkedIn:** [linkedin.com/in/vcalderondev](https://www.linkedin.com/in/vcalderondev/)
* ✉️ **Correo:** [mail@vcalderon.dev](mailto:mail@vcalderon.dev)

<sub>PseudoIDE y @vcalderondev/ukit-css son productos independientes propios. Grid Radar y Grid Accounts son plataformas de Grid Technologies SpA.</sub>
