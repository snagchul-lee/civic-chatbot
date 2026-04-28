# Civic AI Chatbot — Urban Planning Communication Platform

> AI-powered chatbot portals for citizen-government communication, currently under active development across 3 Korean municipalities

**Status:** 🔄 In Development — City portals are live; AI chatbot integration in progress
**Type:** Government R&D Project · URBAN AI Lab, KOREATECH
**Funding:** Ministry of Land, Infrastructure and Transport (국토부) / KAIA

---

## Live City Portals

The following city portals are deployed and live. AI chatbot features are currently being integrated.

| City | URL | Portal Status | Chatbot Status |
|---|---|---|---|
| 🏙️ Busan | [busan.civicurbanplanning.com](https://busan.civicurbanplanning.com/) | 🟢 Live | 🔄 In Development |
| 🏘️ Cheonan | [cheonan.civicurbanplanning.com](https://cheonan.civicurbanplanning.com/) | 🟢 Live | 🔄 In Development |
| 🌿 Damyang | [damyang.civicurbanplanning.com/damso](https://damyang.civicurbanplanning.com/damso) | 🟢 Live | 🔄 In Development |

---

## Project Overview

Part of the national R&D project:
**"Big Data-Based AI Urban Planning Technology Development"**
*(빅데이터 기반 인공지능 도시계획 기술개발)*

### Problem
Citizens face barriers when communicating urban planning concerns to local governments.
Traditional complaint channels (Korea e-People) are one-directional and slow to respond.

### Solution
An interactive AI chatbot portal that allows citizens to:
- Ask urban planning questions in natural language
- Receive instant AI-generated responses
- Submit structured feedback to local governments

Powered by GPT API and trained on city-specific urban planning data and civic complaint datasets.

---

## My Contributions

| Area | What I Did |
|---|---|
| **Data Collection** | Collected nationwide civic complaint data from Korea e-People (국민신문고) and public open data APIs |
| **Chatbot Development** | Developing GPT API-based chatbot backend with city-specific system prompts |
| **API Integration** | Building REST API backend connecting frontend interface to GPT API |
| **Portal Deployment** | Contributed to production deployment of all 3 city portals |

---

## System Architecture

```
User (Citizen)
      ↓
Web Frontend (City Portal UI)  ← Currently Live
      ↓
REST API Backend               ← In Development
      ↓
GPT API (OpenAI)               ← In Development
      +
City-specific System Prompt
      +
Civic Complaint Dataset (RAG)  ← Planned
```

---

## Current Progress

- [x] City portal deployment (Busan, Cheonan, Damyang)
- [x] Nationwide civic complaint data collection (Korea e-People)
- [x] Public open data API integration
- [x] GPT API connection setup
- [ ] City-specific system prompt optimization
- [ ] Frontend-chatbot integration
- [ ] RAG implementation with civic complaint dataset
- [ ] User testing & iteration

---

## Tech Stack

| Category | Tools |
|---|---|
| LLM | GPT API (OpenAI) |
| Backend | REST API (Python) |
| Frontend | Web (HTML/CSS/JS) |
| Data | API crawling, Korea e-People open data |
| Dev Tools | Git, VS Code, Cursor AI |

---

## Data Sources

- **Korea e-People** (국민신문고) — National civic complaint portal
- **Public Open Data APIs** — City-specific urban planning and administrative data
- **City-specific knowledge bases** — Busan / Cheonan / Damyang urban planning documents

---

## Research Context

This project is part of **URBAN AI Lab** at KOREATECH, led by Prof. Geon-cheol Park.
[Lab Homepage](https://ucil90525.github.io/ucil-homepage/index.html)

The goal is to apply AI to urban planning participatory processes,
making civic engagement more accessible and data-driven.

---

*Note: Full source code is partially restricted due to government R&D confidentiality.
This repository documents the project architecture, my contributions, and key technical decisions.*

*For inquiries: andy26566242@gmail.com*
