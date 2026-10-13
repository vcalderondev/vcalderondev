# Víctor Calderón Oyarce 👋

### Senior Full Stack Engineer · TypeScript · NestJS · Angular · Google Cloud
### Fundador de [Grid Technologies](https://gridtechnologies.cl)

<p>
  <a href="https://vcalderon.dev"><img alt="Sitio" src="https://img.shields.io/badge/vcalderon.dev-15243b?style=flat-square&logo=googlechrome&logoColor=white"></a>
  <a href="https://gridtechnologies.cl"><img alt="Grid Technologies" src="https://img.shields.io/badge/Grid_Technologies-1f6fb2?style=flat-square&logo=icloud&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/vcalderondev/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:mail@vcalderon.dev"><img alt="Email" src="https://img.shields.io/badge/mail@vcalderon.dev-5a6472?style=flat-square&logo=gmail&logoColor=white"></a>
</p>

🇨🇱 **Constitución, Chile** — disponible para trasladarme a Santiago · **Remoto o híbrido**
💼 Empresa: **[Grid Technologies SpA](https://gridtechnologies.cl)** · 🌐 **[vcalderon.dev](https://vcalderon.dev)**

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

Todo el ecosistema vive en un **monorepo de más de 30 repositorios** sobre una misma base técnica: **arquitectura hexagonal y DDD**, contratos compartidos como SSOT, **GCP** (Cloud Run, Cloud SQL PostgreSQL, Pub/Sub, Cloud Scheduler) y **flujos basados en eventos**.

### Productos

| Producto | Qué resuelve |
|---|---|
| **[Grid Flow](https://gridflow.cl)** | **El agente de ventas por WhatsApp para distribuidores B2B.** Responde con el catálogo real, calcula el IVA del 19 % en el backend, envía el link de pago y **emite la boleta o factura ante el SII**. WhatsApp Business oficial, 24/7. |
| **[Grid Forge](https://gridforge.cl)** | **Del prompt al software desplegado.** Entorno de desarrollo autónomo con **orquestación multi-agente**: modela arquitecturas en un *canvas* visual (Topology Canvas), genera código de producción verificado y lo lanza a la nube. |
| **Grid Radar** | **Inteligencia competitiva de precios** con extracción resiliente (ejecuciones programadas, detección de cambios y segmentación geográfica) y **servidor MCP propio** para que los agentes consulten los datos. |
| **Grid Accounts** | **Identidad y cobro** para todo el ecosistema: proveedor **OAuth2/OIDC** (RS256/JWKS, **WebAuthn** y **TOTP**), catálogo de servicios y facturación recurrente en CLP y USD, con eventos de cobro en Cloud Pub/Sub. |
| **Motor DTE (SII)** | **Emisión de documentos tributarios electrónicos** chilenos: boleta 39 y factura 33 con firma **XML-DSIG**, manejo de **CAF** y generación de **TED**. |

> **Ecosistema en construcción:** Grid Flow, Grid Forge, Grid Radar, Grid Accounts, Grid Teams, Grid Payments, Grid Mail y Grid Lex comparten la misma plataforma, el mismo sistema de identidad y el mismo motor tributario.

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

Si te interesa la arquitectura cloud, la IA aplicada a negocio real o los productos de Grid:

* 🌐 **Sitio personal:** [vcalderon.dev](https://vcalderon.dev)
* 🏢 **Grid Technologies:** [gridtechnologies.cl](https://gridtechnologies.cl) · [Grid Flow](https://gridflow.cl) · [Grid Forge](https://gridforge.cl)
* 🚀 **Producto propio:** [pseudoide.dev](https://pseudoide.dev)
* 💼 **LinkedIn:** [linkedin.com/in/vcalderondev](https://www.linkedin.com/in/vcalderondev/)
* ✉️ **Correo:** [mail@vcalderon.dev](mailto:mail@vcalderon.dev)

<sub>PseudoIDE y @vcalderondev/ukit-css son productos propios. Grid Flow, Grid Forge, Grid Radar, Grid Accounts y el motor DTE son productos de Grid Technologies SpA.</sub>
