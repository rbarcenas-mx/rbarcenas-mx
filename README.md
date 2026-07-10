<div align="center">

# Roberto Barcenas

### Engineering Manager · Fintech Platforms · AI-Driven DevEx

**Ex Mercado Libre** · Fintech Platforms (Mercado Pago) & Credits (Mercado Crédito)

[![](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/robertobarcenas)
[![](https://img.shields.io/badge/-SkillKit-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/rbarcenas-mx/skillkit)
[![](https://img.shields.io/badge/-Mandadero-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/rbarcenas-mx/errand)
![](https://img.shields.io/badge/-Ex_MeLi_Fintech_%26_Credits-FFE600?style=flat-square&logo=mercadopago&logoColor=black)
![](https://img.shields.io/badge/-CDMX-1a1a1a?style=flat-square)

![](https://komarev.com/ghpvc/?username=rbarcenas-mx&style=flat-square&color=blue)

</div>

---

## Sobre mí · About Me

ES | Ingeniero de software y líder técnico con **16+ años construyendo plataformas financieras** que procesan cientos de millones de operaciones al día. Mi enfoque está en **hacer equipos más efectivos**: combinando liderazgo humano con automatización inteligente para eliminar fricción, acelerar entregas y mantener sistemas críticos funcionando sin interrupción.

EN | Engineering leader with **16+ years building financial platforms** processing hundreds of millions of operations daily. My focus is **making teams more effective**: combining human-centered leadership with intelligent automation to remove friction, accelerate delivery, and keep critical systems running without interruption.

> *"Engineering leadership no es solo escribir mejor código — es hacer que el equipo entero sea más efectivo."*

---

## Lo que hago · What I Do

| Área · Area | Detalle · Detail |
|---|---|
| 🏗️ **Engineering Management** | Equipos multi-disciplinarios de 8–15 personas. People leadership, technical direction, stakeholder alignment |
| 🏦 **Fintech Platforms** | Sistemas de pagos, contabilidad y data pipelines. Mercado Pago / Mercado Crédito — múltiples mercados LATAM |
| ⚡ **DevEx + AI Automation** | AI-driven code review que redujo time-to-approval **60%** y zombie PRs **73%** (+108% reviews completadas) |
| 🧠 **Hybrid AI Architecture** | 95–97% de tokens procesados localmente (Ollama + AMD ROCm), orquestación remota con modelos premium |
| 📊 **Data Pipelines** | Procesamiento de **300M+ registros/día** con requerimientos estrictos de corrección, auditabilidad y disponibilidad |

---

## Stack Tecnológico · Tech Stack

**Leadership & Methods**
![](https://img.shields.io/badge/-Engineering_Management-1a1a1a?style=flat-square)
![](https://img.shields.io/badge/-Agile-1a1a1a?style=flat-square)
![](https://img.shields.io/badge/-DevEx-1a1a1a?style=flat-square)
![](https://img.shields.io/badge/-OKRs-1a1a1a?style=flat-square)
![](https://img.shields.io/badge/-Observability-1a1a1a?style=flat-square)

**Languages**
![](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=java&logoColor=white)
![](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

**Cloud & Infrastructure**
![](https://img.shields.io/badge/-AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**AI & Productivity Ecosystem**
![](https://img.shields.io/badge/-Claude_Code-1a1a1a?style=flat-square)
![](https://img.shields.io/badge/-Ollama-1a1a1a?style=flat-square)
![](https://img.shields.io/badge/-n8n-1a1a1a?style=flat-square)
![](https://img.shields.io/badge/-Cursor_MCP-1a1a1a?style=flat-square)
![](https://img.shields.io/badge/-Gemini-1a1a1a?style=flat-square)

**Observability**
![](https://img.shields.io/badge/-Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)
![](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![](https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![](https://img.shields.io/badge/-New_Relic-008C99?style=flat-square&logo=newrelic&logoColor=white)

---

## Proyectos Destacados · Featured Projects

### [skillkit](https://github.com/rbarcenas-mx/skillkit) ![](https://img.shields.io/github/stars/rbarcenas-mx/skillkit?style=flat-square) ![](https://img.shields.io/github/languages/top/rbarcenas-mx/skillkit?style=flat-square)

**Skills + Token Budget Engine** — Framework de skills para AI coding agents (Anthropic-format) con enrutamiento inteligente de modelos según presupuesto de tokens. Skills listas para CI, QA, auditoría y revisión de PRs — orchestrator remoto + executor local vía Ollama.

**Arquitectura híbrida:** El modelo remoto (orquestador) descompone tareas y coordina ejecutores locales resueltos por `TOKEN_BUDGET` (low=Ollama gratis, medium=balance, high=premium). Degradación graceful si un modelo no está disponible.

`skillkit/` — 10 skills · Python · MIT

### [errand / Mandadero](https://github.com/rbarcenas-mx/errand) ![](https://img.shields.io/github/stars/rbarcenas-mx/errand?style=flat-square) ![](https://img.shields.io/github/languages/top/rbarcenas-mx/errand?style=flat-square)

Plataforma on-demand que conecta personas que necesitan mandados con otras dispuestas a realizarlos en Querétaro. Backend en Node.js/TypeScript con PostgreSQL + PostGIS, autenticación JWT + OTP vía SMS (Twilio), subida de imágenes (Cloudinary), CI/CD con GitHub Actions.

`src/` — Express · Prisma · PostGIS · Twilio · JWT

---

## GitHub Analytics

<div align="center">

![](https://github-readme-stats.vercel.app/api?username=rbarcenas-mx&show_icons=true&theme=dark&hide_border=true&count_private=true)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=rbarcenas-mx&layout=compact&theme=dark&hide_border=true)

</div>

---

## Contacto · Contact

📧 roberto.barcenas@gmail.com · 💼 [LinkedIn](https://linkedin.com/in/robertobarcenas) · 🐙 [GitHub](https://github.com/rbarcenas-mx)

---

<sub>Built with AI · Actualizado · Updated 2026</sub>
