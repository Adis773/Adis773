<div align="center">
  <img src="assets/banner.png" alt="Adis Abenov — product engineer: AI infrastructure, web platforms, 3D" width="100%" />
</div>

<p align="center">
  <sub><b>EN</b> · <a href="README.ru.md">RU</a></sub>
</p>

<p align="center">
  <a href="https://novastep.tech"><img src="https://img.shields.io/badge/NeuroHub-live-000000?style=for-the-badge&logo=openai&logoColor=white" alt="NeuroHub"></a>
  <a href="https://x.com/qwer_GenZ"><img src="https://img.shields.io/badge/X-@qwer__GenZ-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"></a>
  <a href="mailto:adisabenov2@gmail.com"><img src="https://img.shields.io/badge/Email-say%20hi-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://adis-portfolio.vercel.app"><img src="https://img.shields.io/badge/Portfolio-website-7C3AED?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
</p>

<h3 align="center">I build products end to end — architecture, backend, interface, inference, deploy</h3>

<p align="center"><em>AI infrastructure · web platforms · realtime &amp; 3D · 30+ launches</em></p>

---

## Hey, I'm Adis

I'm a product engineer. I take an idea and carry it to "it works for real users": I design the architecture, write the backend and the frontend, wire up model inference, payments and monitoring, then keep it alive in production.

**30+ shipped products in two years** — an AI model marketplace billed per token, an autonomous Windows agent, a 3D browser game, an AR building tool, a retail banking platform, client portals and brand sites. Some source code is closed by NDA or commercial confidentiality: there I show the product and explain the engineering decisions, not the code itself.

> **Principle:** a working user journey first, beautiful architecture second. A product without users is just a folder of files.

<p align="center">
  <a href="https://adis-portfolio.vercel.app"><b>→ Full portfolio site</b></a>
</p>

---

## Featured launches

### NeuroHub — AI model infrastructure

<div align="center">
  <a href="https://novastep.tech"><img src="assets/neurohub.png" alt="NeuroHub — AI model catalog, chat and OpenAI-compatible API" width="100%" /></a>
</div>

A marketplace where authors upload model weights and inference runs on first-party GPUs: a catalog with per-million-token pricing, a web chat billed by actual usage, an OpenAI-compatible API and one invoice across every model. Billing, inference orchestration, response streaming, multi-tenancy — all built from scratch.

**Role:** architecture, backend, frontend, infrastructure
**Status:** live, closed source — demo on request

<p>
  <a href="https://novastep.tech"><img src="https://img.shields.io/badge/Open-live-2EA043?style=flat-square" alt="Live"></a>
  <img src="https://img.shields.io/badge/Source-closed%20(NDA)-555555?style=flat-square&logo=lock&logoColor=white" alt="Source closed">
</p>

### Stratium AI — an autonomous agent for Windows

<div align="center">
  <a href="https://stratium-ai-landing.vercel.app"><img src="assets/stratium.png" alt="Stratium AI landing page" width="100%" /></a>
</div>

An agent that operates a computer: plans tasks, works with apps and files, keeps context between sessions and runs autonomously for up to 10 days. I built the whole product — positioning, landing page, design system, copy, interactive demo and the Windows build.

**Stack:** TypeScript, React, Vite, hand-written CSS/Canvas animation
**Hard part:** explaining "an agent on your computer" without hand-waving — through scenarios, not feature lists

<p>
  <a href="https://stratium-ai-landing.vercel.app"><img src="https://img.shields.io/badge/Open-live-0A66C2?style=flat-square" alt="Live"></a>
  <a href="https://github.com/Adis773/stratium-ai-landing"><img src="https://img.shields.io/badge/Source-open-2EA043?style=flat-square&logo=github&logoColor=white" alt="Source"></a>
  <img src="https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-555555?style=flat-square" alt="Windows">
</p>

### Cyberpunk Megapolis — a 3D game in the browser

<div align="center">
  <a href="https://cyberpunk-megapolis.vercel.app"><img src="assets/cyberpunk.png" alt="Cyberpunk Megapolis — 3D web-swing game" width="100%" /></a>
</div>

Web-swinging between skyscrapers: custom rope physics, a procedural city, dynamic lighting and streaming of models and textures. The asset pipeline is a point of pride too — a PBR character with normals and metalness that doesn't wreck performance.

**Stack:** JavaScript, Three.js/WebGL, GLSL shaders, custom asset loader
**Hard part:** holding 60 FPS on weak laptops — polygon budget, batching, lazy sector loading

<p>
  <a href="https://cyberpunk-megapolis.vercel.app"><img src="https://img.shields.io/badge/Play-live-E4405F?style=flat-square" alt="Play"></a>
  <a href="https://github.com/Adis773/cyberpunk-megapolis"><img src="https://img.shields.io/badge/Source-open-2EA043?style=flat-square&logo=github&logoColor=white" alt="Source"></a>
  <img src="https://img.shields.io/badge/3D-WebGL-9900EF?style=flat-square" alt="WebGL">
</p>

---

## More launches

<table>
<tr>
<td width="50%" valign="top">
  <a href="https://tradinbot.vercel.app"><img src="assets/alphabot.png" alt="AlphaBot Quantum dashboard" width="100%" /></a>
  <b>AlphaBot Quantum</b> — control room for a trading agent: capital, analysis cycles, live event stream, log export.<br />
  <sub>React · TypeScript · Firebase</sub><br />
  <a href="https://tradinbot.vercel.app"><b>Live</b></a> · <a href="https://github.com/Adis773/Tradinbot">Code</a>
</td>
<td width="50%" valign="top">
  <a href="https://vilis.vercel.app"><img src="assets/vilis.png" alt="VILIS premium AI glasses" width="100%" /></a>
  <b>VILIS</b> — launch site for premium AI glasses: 1080p capture, 8 hours of battery, built-in assistant.<br />
  <sub>Brand site · conversion · motion</sub><br />
  <a href="https://vilis.vercel.app"><b>Live</b></a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
  <a href="https://fg-self.vercel.app"><img src="assets/ar3d.png" alt="AR 3D Builder" width="100%" /></a>
  <b>AR 3D Builder</b> — hand-tracked AR editor: pinch to place blocks, gesture to delete, scene export to JSON.<br />
  <sub>WebXR · MediaPipe · Three.js</sub><br />
  <a href="https://fg-self.vercel.app"><b>Live</b></a>
</td>
<td width="50%" valign="top">
  <a href="https://abebabank.vercel.app"><img src="assets/abeba.png" alt="ABEBA Bank" width="100%" /></a>
  <b>ABEBA Bank</b> — zero-fee meme bank: a product experiment in brand voice, virality and conversion.<br />
  <sub>React · landing · Web3</sub><br />
  <a href="https://abebabank.vercel.app"><b>Live</b></a> · <a href="https://github.com/Adis773/Abeba-bank-">Code</a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
  <a href="https://v0-easgikcabinet-l5.vercel.app"><img src="assets/easgik.png" alt="Easgik customer portal" width="100%" /></a>
  <b>Easgik</b> — customer portal for a land-survey and cadastre service: requests, documents, account area.<br />
  <sub>Commercial client · Next.js · Postgres</sub><br />
  <a href="https://v0-easgikcabinet-l5.vercel.app"><b>Live</b></a>
</td>
<td width="50%" valign="top">
  <a href="https://barber2-eight.vercel.app"><img src="assets/barber.png" alt="Barber Boss barbershop site" width="100%" /></a>
  <b>Barber Boss</b> — premium barbershop in Astana: services, interior, booking flow, Telegram notifications.<br />
  <sub>Client site · booking · brand</sub><br />
  <a href="https://barber2-eight.vercel.app"><b>Live</b></a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
  <a href="https://github.com/Adis773/GameViki"><img src="assets/gameviki.png" alt="GameViki encyclopedia" width="100%" /></a>
  <b>GameViki</b> — video game encyclopedia: catalog, reviews, ratings, collections, editorial admin.<br />
  <sub>React · Node · Postgres · Redis</sub><br />
  <sub>Closed source · private beta</sub>
</td>
<td width="50%" valign="top">
  <img src="assets/bankflow.png" alt="BankFlow banking platform" width="100%" />
  <b>BankFlow</b> — retail digital banking: accounts, payments, cards, lending, investments, analytics.<br />
  <sub>FastAPI · Next.js · Kubernetes</sub><br />
  <sub>Closed source · commercial</sub>
</td>
</tr>
</table>

---

## Also shipped

| Product | What it is | Link |
| :-- | :-- | :-- |
| **AInvest Terminal** | Investment terminal: portfolio, daily yield, auto-invest 10% into stocks, insights feed | [Live](https://assistent-nine.vercel.app) |
| **SmartLearnix** | AI learning platform: personal tracks, gamification, analytics | [Code](https://github.com/Adis773/SmartLearnix) |
| **TgClone** | Messenger client on React: chats, media, realtime updates | [Code](https://github.com/Adis773/Tgclone) |
| **freeGPT** | Zero-setup interface to language models | [Code](https://github.com/Adis773/freeGPT) |
| **AirOS** | Browser "operating system": windows, files, apps in a tab | [Code](https://github.com/Adis773/AirOs) |
| **CryptoMain** | Crypto portfolio tracker with auth and live rates | [Live](https://cryptomain.vercel.app) |
| **Stranger Things Shop** | Fandom merch store: catalog, cart, checkout | [Live](https://strangerthings-shop.vercel.app) |
| **Alpha Barbershop** | Second barbershop brand site with online booking | [Live](https://barber-delta-five.vercel.app) |

---

## About closed source

Six products run with private repositories — **NeuroHub**, **BankFlow**, **GameViki**, **AInvest**, plus two client systems under NDA. That's a normal part of commercial work: the product is public, the code is the client's asset.

If you need to see engineering depth rather than a landing page, I'm happy to walk through architecture, data models and trade-offs on a call — or show the open-source ones above, which are real and complete.

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
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
</p>

I also handle everything around the code: product decisions, interface design, copy, analytics, deployment and production support.

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

### Have something that should become a working product?

Write to me — you'll get a solution, not an hourly-rate quote.

<a href="mailto:adisabenov2@gmail.com"><img src="https://img.shields.io/badge/adisabenov2@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://x.com/qwer_GenZ"><img src="https://img.shields.io/badge/@qwer__GenZ-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"></a>
<a href="https://github.com/Adis773"><img src="https://img.shields.io/badge/Adis773-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>

<sub>Open to ambitious projects · 2026</sub>

</div>
