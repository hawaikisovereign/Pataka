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

## Source Prioritisation — Tā Moko Practice

- **Primary source for tā moko practice content:**
  - /data/Te-Ahi-tā-moko-v2.pdf

- **Tikanga, kaupapa, cultural context:**
  - /data/He-tanga-ngutu-he-tuhoetanga.pdf
  - /docs/data-notes/ta-moko-whariki-map.md
  - /data/Waitangi-te-raki-tribunal-report.pdf
  - /data/UNDRIP.pdf
  - /data/ILO-169.pdf

- **Māori Data Sovereignty & AI Governance:**
  - /data/Taiuru-maori-data-sovereignty-compilation.pdf
  - /data/EBOR-2025-FRAMEWORK.pdf
  - /data/IAPP-AIGP-BoK.pdf
  - /data/IAPP-CIPM-BoK.pdf
  - /data/IAPP-CIPP/E-Bok.pdf

- **Hauora & client wellbeing context:**
  - /data/Te-whare-tapa-wha.pdf
  - /data/Maramataka-maori.pdf

- **Legal & Business Governance:**
  - /data/Nz-fair-trading-act-guide.pdf
  - /data/Nz-copyright-maori-ip.pdf
  - /data/Nz-consumer-guarantees-act.pdf
  - /data/Wai-262-maori-ip-report.pdf
  - /data/Customary-tattooing-guidelines-nz-moh.pdf
  - /data/Skin-piercing-guidelines-nz-moh.pdf
  - /data/EBOR-2025-FRAMEWORK.pdf
  - IRD, MBIE, Companies Office web references

---

## Reference categories:

- **/docs/data-notes/web-references.md**  
  Records trusted NZ and kaupapa Māori web resources

- **Academic and Educational References**  
  - These are for learning pathways and community resources only  
  - NOT used as primary source for moko practice content

---

## Exclusion Rules:

- AI Agents must:
  - NOT use academic institutional sources for tā moko tikanga or process  
  - NOT generate moko content from non-Māori or Western tattoo industry sources  
  - ALWAYS prioritise kaupapa-based, whānau-verified content from the sources listed above

---

_Last updated: June 2025_
---

© 2025 Charles Werahiko Olsen  
Hawaiki Sovereign Trust — cwtolsen@gmail.com  