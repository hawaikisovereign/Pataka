# 🏛️ Tatau AI — Architecture

_A living document to describe the structure and design of the Tatau AI app and agents platform._

---

## Purpose

**Tatau AI** is a kaupapa Māori application designed to support tattoo artists (moko and general tattooing) with:

✅ Client management  
✅ Booking and workflow tools  
✅ Stock management (supply ordering, stocktaking)  
✅ Financial services  
✅ Legal guidance  
✅ AI agents that assist in running the business and protecting cultural values  

It is developed and maintained by Charles Werahiko Olsen under **Hawaiki Sovereign Trust**.

---

## Repository Overview

- **Repository:** [Pataka](https://github.com/hawaikisovereign/Pataka)  
- **App Name:** Tatau AI  
- **Platform:** GitHub + Working Copy + Kodex + StackBlitz

---

## Folder Structure

Pataka/
├── .github/           → Workflows (Agents)
├── public/            → index.html
├── src/               → App source code
│   ├── agents/        → AI agent logic
│   ├── components/    → UI components (LogicAgent, etc)
│   ├── main.js / App.jsx → App entry points
├── docs/              → Project documentation (this file, roadmap, contributing)
├── LICENSE.md
├── README.md
├── ROADMAP.md
├── CHANGELOG.md
├── TODO.md
├── .gitignore
├── package.json
├── package-lock.json

---

## Current Agents

| Agent | Description | Location |
|-------|-------------|----------|
| 📝 ChangeLog Agent | Uses GitHub Actions and OpenAI API to maintain CHANGELOG.md automatically on commits. | `.github/workflows/update-change-log.yml` |

---

## AI Model

- Current model: `gpt-4o`  
- Connected via **OpenAI API Key (secret stored in GitHub)**

---

## Dev Environment

| Tool | Use |
|------|-----|
| **GitHub** | Repo management, workflows |
| **Working Copy (iPad)** | Git commits / push / pull |
| **Kodex (iPad)** | Code editor |
| **StackBlitz** | App live preview and UI testing |

---

## Māori Kaupapa and Cultural Protection

Tatau AI operates under the values of:

- Mana motuhake  
- Utu  
- Aroha  
- Tapu / Noa  
- Kaitiakitanga for taonga such as moko, whakapapa, and mātauranga Māori

Content, licensing and AI usage are governed by principles laid out in the Trust Deed of **Hawaiki Sovereign Trust**.

---

## Future Plans

✅ More agents to be added  
✅ API usage monitoring  
✅ Expanded test coverage  
✅ UI enhancements  
✅ Mobile-first optimisations for artists  
✅ App store release roadmap

---

© 2025 Charles Werahiko Olsen  
Hawaiki Sovereign Trust — cwtolsen@gmail.com  