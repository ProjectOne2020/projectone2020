<div align="center">
  <h1>Hola, soy Alejandro Gutiérrez 👋</h1>
  <h3>Software Architect | Solo Founder | AI Systems & Cryptographic Protocol Researcher (PoHI)</h3>
  <p><b>Ponente Oficial en GDG Monterrey DevFest 2026</b> · Autor Publicado en <b>Revista Editorial K. Nexus (2026)</b> · Fundador de <b>Claude Code en Español</b></p>
  
  <p>Construyo plataformas SaaS B2B/B2B2C en producción, herramientas de optimización de contexto para agentes de IA, infraestructuras de verificación criptográfica y arquitecturas backend de alta concurrencia para videojuegos y mundos virtuales.</p>

  <br />

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/alejandro-gutierrez-ai/)
  [![Radar IA](https://img.shields.io/badge/Radar_IA-Plataforma_GEO-10B981?style=for-the-badge&logo=googlechrome&logoColor=white)](https://radar.omniflowcreator.com)
  [![ctxopt](https://img.shields.io/badge/ctxopt-CLI_&_Kit_de_Gu%C3%ADas-7C3AED?style=for-the-badge&logo=github)](https://github.com/ProjectOne2020/ctxopt)
  [![Email](https://img.shields.io/badge/Email-Contactar-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alejandro.gutierrezb31@gmail.com)

  <br />
  <br />

  🌐 *Read this in [English](README-en.md)*

</div>

---

### 🚀 Ecosistemas SaaS y Productos en Producción

#### 🌐 [Radar IA — Plataforma GEO (Generative Engine Optimization) para LATAM](https://radar.omniflowcreator.com)
*Founder & Lead Architect (En Producción)*
- Plataforma SaaS B2B y para agencias que mide y optimiza la visibilidad de marcas en motores generativos (**ChatGPT, Claude, Gemini y Perplexity**) mediante una metodología propia de **8 pilares** (técnicos, semánticos y de citación real).
- **Cobertura regional nativa:** 18 países de Latinoamérica, 43 rubros comerciales y un banco calibrado de **25,688+ preguntas reales** en español y portugués, con precios localizados en moneda local vía Stripe.
- **Stack:** Next.js (App Router), TypeScript, Supabase (PostgreSQL + RLS), Inngest (orquestación asíncrona multi-LLM), Stripe, Resend.

#### ⚡ [ctxopt — Context Optimizer para Agentes de Programación con IA](https://github.com/ProjectOne2020/ctxopt)
*Autor & Creador (Open Source MIT + Kit de Guías Paso a Paso)*
- CLI que unifica la configuración de contexto (`AGENTS.md`, `CLAUDE.md`), instala hooks de filtrado de salidas verbosas de tests/builds, memoria persistente entre sesiones (`.agents/memory.md`) y subagentes con ruteo de modelos para **Claude Code, Google Antigravity, Codex y Cursor**.
- **Evidencia medida en producción:** Reducción de **64.5% en tokens de contexto nuevo** procesados en tareas de exploración de código sobre un repositorio real de ~220 archivos.
- 📚 **Kit de Guías Paso a Paso:** Disponible en **[Hotmart (Español)](https://alejandro-gutierrezb31.hotmart.host/ctxopt-kit-de-optimizacion-de-contexto-para-agentes-de-ia-claude-code-codex-cursor-a58f8b26-fea9-41bc-a45a-a756384b4b9d)** y **[Gumroad (English)](https://aagb.gumroad.com/l/wkivk)**.

#### 🐾 [MaskotIA — Sistema Operativo de Salud Animal B2B2C](https://github.com/ProjectOne2020/maskotia-public)
*Founder & Lead Architect (En Producción)*
- Infraestructura B2B2C que procesa historiales médicos SOAP por voz, triaje clínico asistido, telemedicina y transacciones multi-party para el sector veterinario.
- **Arquitectura:** Next.js 16 (App Router), Supabase (PostgreSQL + RLS), Llama 3.3 (vía Groq), arquitectura *offline-first* (Dexie/IndexedDB), Stripe Connect y facturación electrónica CFDI 4.0 (Facturapi).
- **Innovación:** Motor de seguridad clínica determinista (*Hardcoded Safety Rules*) que audita las inferencias generadas por IA en tiempo real antes de mostrarlas al usuario.

#### 🛡️ [Protocolo PoHI (Proof of Human Intent) & Escrow P2P](https://github.com/ProjectOne2020/pohi-protocol-poc)
*Autor e Investigador*
- Protocolo criptográfico *open-source* diseñado para mitigar el fraude algorítmico y los ataques Sybil en redes P2P utilizando biometría conductual sin recolectar datos personales identificables (PII).
- Combina el tercer momento estadístico (**Asimetría de Fisher-Pearson**) en la dinámica de tecleo con **Pruebas de Conocimiento Cero (zk-SNARKs Groth16 sobre curva BN254 y circuitos R1CS en Circom)** para condicionar la liberación de contratos inteligentes (*Smart Contracts*).

#### 📄 Otros Sistemas B2B Desarrollados
- **ContractaFácil / CuentasClaras:** Plataforma SaaS de generación ágil de presupuestos y contratos comerciales con seguimiento en tiempo real y cobros vía Stripe para contratistas en EE. UU. y LATAM.
- **Proyecto Saluid (Fintech P2P Internacional):** Plataforma de transferencias transfronterizas P2P (NestJS, Prisma, React 18, Socket.io) cuyo motor de validación algorítmica de riesgo sirvió como caso de estudio para publicación editorial científica.
- **NeuroVoz / Copiloto IC & OmniFlow Control Center:** Asistente conversacional de voz de ultrabaja latencia (<185ms vía Groq) y suite local-first de orquestación multi-agente con validación determinista.

---

### 🎮 Ingeniería de Backend para Videojuegos & Mundos Virtuales (Roblox & Second Life)

- **⚔️ Arquitectura Backend Battle Royale en Roblox (15 Módulos Server-Authoritative en Luau):**
  - Diseño y desarrollo de un backend multijugador en tiempo real (estado distribuido a 60 ticks/s) compuesto por **15 subsistemas interconectados**: sistema de lobbys y matchmaking, gestión de 5 portales de partida simultáneos en distintas fases, motor autoritativo de daño/vida/muerte, tormenta dinámica, detección automática de último superviviente, recolección de basura sin *memory leaks*, **Anti-Cheat Server-Side** (validación de hitboxes, teletransportes y *rate-limiting* de eventos remotos) y persistencia transaccional en `DataStores`.
- **🛠️ ProfileSafe — Visual Data Editor & Session Unlocker (Plugin para Roblox Studio en Luau):**
  - Herramienta B2D nativa (`DockWidgetPluginGui`) para desarrolladores de Roblox que detecta automáticamente estructuras `ProfileService` / `ProfileStore` frente a DataStores genéricos, aísla y protege claves críticas (`MetaData`, `ActiveSession`, `GlobalUpdates`), ofrece edición visual recursiva con vista previa de diferencias (*Diff Modal*) antes de `UpdateAsync` e incorpora desbloqueo de emergencia de sesiones colgadas (*Emergency Force-Release Session Lock*).
- **📡 [Sentinel — Discord Parcel & Visitor Radar v1.0](https://marketplace.secondlife.com/p/Sentinel-Discord-Parcel-Visitor-Radar-v10/28749960) (Second Life Marketplace — LSL Mono):**
  - Sistema autónomo de telemetría parcelaria en tiempo real programado en LSL (Mono) con detección poligonal exacta (`llGetAgentList`), memoria flash no volátil en *Linkset Data (LSD)* inmune a reinicios de simulador, algoritmo *debounce* anti-spam de 180s en bordes de parcela y cola HTTP con *throttling* directo a Webhooks de Discord sin servidores externos.

---

### 📚 Publicaciones Científicas, Conferencias y Comunidad

- **📰 Artículo Publicado en Revista Digital — *Revista Editorial K. Nexus (2026)*:**
  - **Título:** *"Validación de riesgo financiero en P2P con IA"*
  - **Resumen:** Investigación técnica y caso de estudio sobre la mitigación algorítmica de fraude en transferencias financieras descentralizadas y validación de riesgo en tiempo real mediante modelos de Inteligencia Artificial.
- **🎤 Ponente Oficial — GDG Monterrey DevFest 2026:** Ponencia *"De la idea al producto: Construyendo software real con agentes de IA"*.
- **👥 Fundador de "Claude Code en Español":** Comunidad técnica hispanohablante enfocada en ingeniería de contexto, flujos de desarrollo defensivo asistido por IA y agentes autónomos de codificación.

---

### 💻 Stack Tecnológico Principal

*   **Arquitectura & Core:** Next.js (App Router), React, TypeScript, Node.js, NestJS, Python, Luau (Roblox), LSL Mono (Second Life), WebAssembly (WASM).
*   **Infraestructura & Datos:** Supabase (PostgreSQL, RLS, Edge Functions), Inngest, Cloudflare Workers/D1, Prisma, Dexie.js (Offline-First), Roblox DataStoreService, Vercel.
*   **Inteligencia Artificial & Agentes:** Ingeniería de Contexto (`AGENTS.md` / `ctxopt`), Orquestación Multi-LLM (Claude Code, Google Antigravity, OpenAI, Anthropic, Gemini, Perplexity, Groq), copilotos de voz de baja latencia.
*   **Finanzas, Legal & Web3:** Stripe & Stripe Connect, Facturación CFDI 4.0 (Facturapi), Criptografía ZK-SNARKs (Circom / Groth16 / BN254 / R1CS), Solidity Smart Contracts.

---

<div align="center">
  <i>"El software no solo debe resolver un problema; debe alterar los incentivos económicos a favor del usuario."</i>
</div>
