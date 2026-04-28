# Civic AI Chatbot — Urban Planning Communication Platform

> AI-powered chatbot portals for citizen-government communication, deployed across 3 Korean municipalities

**Status:** 🟢 Live in Production (3 cities)
**Type:** Government R&D Project · URBAN AI Lab, KOREATECH
**Funding:** Ministry of Land, Infrastructure and Transport (국토부) / KAIA

---

## Live Deployments

| City | URL | Description |
|---|---|---|
| 🏙️ Busan | [busan.civicurbanplanning.com](https://busan.civicurbanplanning.com/) | Busan Civic AI Portal |
| 🏘️ Cheonan | [cheonan.civicurbanplanning.com](https://cheonan.civicurbanplanning.com/) | Cheonan Interactive Channel |
| 🌿 Damyang | [damyang.civicurbanplanning.com/damso](https://damyang.civicurbanplanning.com/damso) | Damyang Interactive Channel |

---

## Project Overview

Part of the national R&D project:
**"Big Data-Based AI Urban Planning Technology Development"**
*(빅데이터 기반 인공지능 도시계획 기술개발)*

### Problem
Citizens face barriers in communicating urban planning concerns to local governments.
Traditional complaint channels (Korea e-People) are one-directional and slow.

### Solution
An interactive AI chatbot portal that allows citizens to ask urban planning questions,
receive instant responses, and submit structured feedback — powered by GPT API and
trained on city-specific urban planning data and civic complaint datasets.

---

## My Contributions

| Area | What I Did |
|---|---|
| **Data Collection** | Collected nationwide civic complaint data from Korea e-People (국민신문고) and public open data APIs |
| **Chatbot Development** | Developed GPT API-based chatbot backend with city-specific system prompts |
| **API Integration** | Built REST API backend connecting frontend interface to GPT API |
| **Deployment** | Contributed to production deployment of all 3 city portals |

---

## System Architecture

```
User (Citizen)
      ↓
Web Frontend (City Portal UI)
      ↓
REST API Backend
      ↓  ↑
GPT API (OpenAI)
      +
City-specific System Prompt
      +
Civic Complaint Dataset (RAG - in development)
```

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

The chatbot system contributes to the broader research goal of applying AI to urban planning participatory processes, making civic engagement more accessible and efficient.

---

*Note: Full source code is partially restricted due to government R&D confidentiality.
This repository documents the project architecture, my contributions, and key technical decisions.*

*For inquiries: andy26566242@gmail.com*
