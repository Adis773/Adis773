<div align="center">
  <img src="assets/banner.png" alt="Adis Abenov — Product Engineer: AI infrastructure, web platforms, 3D" width="100%" />
</div>

<br />

<p align="center">
  <a href="https://novastep.tech"><img src="https://img.shields.io/badge/NeuroHub-AI%20Infrastructure-000000?style=for-the-badge&logo=openai&logoColor=white" alt="NeuroHub"></a>
  <a href="https://stratium-ai-landing.vercel.app"><img src="https://img.shields.io/badge/Stratium%20AI-Windows%20Agent-1A1A1A?style=for-the-badge&logo=windows&logoColor=white" alt="Stratium AI"></a>
  <a href="mailto:adis040512@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hi-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

<h3 align="center">I build products end to end — architecture, backend, interface, deploy</h3>

<p align="center">
  <em>AI infrastructure · web platforms · realtime &amp; 3D · 24 products shipped</em>
</p>

---

## In short

I'm **Adis Abenov**, a product engineer. I take an idea and carry it to "it works for real users": architecture, backend, frontend, model inference, payments, deployment and monitoring.

Two years in: **35 repositories with commits and 24 launched products** — from an AI model marketplace billed per token to a 3D browser game and a retail banking platform. Some code is closed by NDA or commercial confidentiality; in those cases I show the product and explain the engineering decisions, not the source.

> **Principle:** a working user journey first, beautiful architecture second. A product without users is just a folder of files.

---

## Selected work

### Stratium AI — an autonomous agent for Windows

<div align="center">
  <a href="https://stratium-ai-landing.vercel.app"><img src="assets/stratium.png" alt="Stratium AI landing page" width="100%" /></a>
</div>

An agent that operates a computer: plans tasks, works with apps and files, keeps context between sessions and can run autonomously for up to 10 days. I built the whole product — positioning, landing page, design system, copy, interactive demo and the Windows build.

**Stack:** TypeScript, React, Vite, hand-written CSS/Canvas animation
**Hard part:** explaining "an agent on your computer" without hand-waving — through scenarios, not feature lists

<p>
  <a href="https://github.com/Adis773/stratium-ai-landing"><img src="https://img.shields.io/badge/Source-open-2EA043?style=flat-square&logo=github&logoColor=white" alt="Source open"></a>
  <a href="https://stratium-ai-landing.vercel.app"><img src="https://img.shields.io/badge/Demo-live-0A66C2?style=flat-square" alt="Demo"></a>
  <img src="https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-555555?style=flat-square" alt="Windows 10 / 11">
</p>

### Cyberpunk Megapolis — a 3D game in the browser

<div align="center">
  <a href="https://cyberpunk-megapolis.vercel.app"><img src="assets/cyberpunk.png" alt="Cyberpunk Megapolis — 3D web-swing game" width="100%" /></a>
</div>

Web-swinging between skyscrapers: custom rope physics, procedural city, dynamic lighting and streaming of models and textures. The asset pipeline is a point of pride too — a PBR character with normals and metalness that doesn't wreck performance.

**Stack:** JavaScript, Three.js/WebGL, GLSL shaders, custom asset loader
**Hard part:** holding 60 FPS on weak laptops — polygon budget, batching, lazy sector loading

<p>
  <a href="https://github.com/Adis773/cyberpunk-megapolis"><img src="https://img.shields.io/badge/Source-open-2EA043?style=flat-square&logo=github&logoColor=white" alt="Source open"></a>
  <a href="https://cyberpunk-megapolis.vercel.app"><img src="https://img.shields.io/badge/Play-live-E4405F?style=flat-square" alt="Play"></a>
  <img src="https://img.shields.io/badge/3D-WebGL-9900EF?style=flat-square" alt="WebGL">
</p>

### AlphaBot Quantum — control room for a trading agent

<div align="center">
  <a href="https://tradinbot.vercel.app"><img src="assets/alphabot.png" alt="AlphaBot Quantum dashboard" width="100%" /></a>
</div>

A control panel for a trading agent: starting capital, analysis cycles, a live event stream, log export. The goal was not "another dashboard" but transparency — every decision step and every trade is visible.

**Stack:** TypeScript, React, realtime event stream, Firebase
**Hard part:** making the agent's reasoning legible enough for a trader to trust it

<p>
  <a href="https://github.com/Adis773/Tradinbot"><img src="https://img.shields.io/badge/Source-open-2EA043?style=flat-square&logo=github&logoColor=white" alt="Source open"></a>
  <a href="https://tradinbot.vercel.app"><img src="https://img.shields.io/badge/Demo-live-0A66C2?style=flat-square" alt="Demo"></a>
</p>

---

## Closed products

> Source code here is private: NDA, commercial development or pre-release. I'm happy to demo the product and walk through the architecture on a call.

### NeuroHub — AI model infrastructure

<div align="center">
  <img src="assets/neurohub.png" alt="NeuroHub — AI model catalog, chat and OpenAI-compatible API" width="100%" />
</div>

A platform where authors upload model weights and inference runs on first-party GPUs: a catalog with per-million-token pricing, a web chat billed by usage, an OpenAI-compatible API and one invoice across all models. The flagship: billing, inference orchestration, response streaming, multi-tenancy.

**Role:** architecture, backend, frontend, infrastructure
**Status:** in private development, demo on request

<p>
  <img src="https://img.shields.io/badge/NeuroHub-live-000000?style=flat-square" alt="NeuroHub live">
  <img src="https://img.shields.io/badge/Source-closed%20(NDA)-555555?style=flat-square&logo=lock&logoColor=white" alt="Source closed">
</p>

### BankFlow — retail digital banking

<div align="center">
  <img src="assets/bankflow.png" alt="BankFlow — accounts, payments, cards, investments" width="100%" />
</div>

A modular monolith on FastAPI plus a Next.js customer app: accounts, transfers, cards, lending, budgets and goals, investments, analytics. Plus extraction of high-traffic domains into services behind an API gateway and Kubernetes manifests.

**Stack:** Python/FastAPI, Next.js, PostgreSQL, Kubernetes
**Status:** commercial work, source closed

### GameViki — a video game encyclopedia

<div align="center">
  <img src="assets/gameviki.png" alt="GameViki — game catalog, reviews, ratings, collections" width="100%" />
</div>

A game catalog with reviews, ratings and collections: an editorial admin, full-text search, a media pipeline and moderation. A content product, not "one more site with cards".

**Stack:** React, Node.js, PostgreSQL, Redis
**Status:** private development

---

## Also in progress

| Project | What it is | Status |
| :-- | :-- | :-- |
| **Easgik** | Customer portal for a land-survey and cadastre service: requests, documents, account area | Commercial client, [demo](https://v0-easgikcabinet-l5.vercel.app) |
| **SmartLearnix** | AI learning platform with personal tracks, gamification and analytics | [Open source](https://github.com/Adis773/SmartLearnix) |
| **ABEBA Bank** | Zero-fee meme bank — a product experiment in brand and virality | [Open source](https://github.com/Adis773/Abeba-bank-) |
| **TgClone** | React messenger client: chats, media, realtime updates | [Open source](https://github.com/Adis773/Tgclone) |
| **freeGPT** | A zero-setup interface to language models | [Open source](https://github.com/Adis773/freeGPT) |
| **AirOS** | A browser "operating system": windows, files, apps | [Open source](https://github.com/Adis773/AirOs) |

---

## Stack

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white" alt="Three.js">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
</p>

I also handle everything around the code: product decisions, interface design, copy, analytics, deployment and production support.

---

## GitHub in numbers

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Adis773&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&include_all_commits=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Adis773&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" />
</p>

---

## How I work

| Step | What happens |
| :--: | :-- |
| **01** | I turn the task into a user journey: who, why, what the outcome must be |
| **02** | I build the skeleton: data model, API, key screens — validated on real data, not mockups |
| **03** | I ship it: tests on critical paths, logs, metrics, error handling, deploy |
| **04** | I stay after release: iterations, handover of code and documentation |

---

<div align="center">

### Have something that needs to become a working product?

Write to me — you'll get a solution, not an hourly-rate quote.

<a href="mailto:adis040512@gmail.com"><img src="https://img.shields.io/badge/adis040512@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://github.com/Adis773"><img src="https://img.shields.io/badge/github.com/Adis773-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>

<sub>Open to ambitious projects · 2026</sub>

</div>
