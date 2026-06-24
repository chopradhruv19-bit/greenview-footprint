# 🌿 Greenview High — School Footprint Tracker

> **USAII Global AI Hackathon 2026 | Challenge 2 | High School Track | Direction B**
> *Make Climate Action Local and Real*

---

## 🎯 What This Project Does

This is an AI-powered web dashboard that helps **Greenview High School, Bengaluru** (a fictional school representing a typical Indian urban school with 1,200 students) understand and act on its hidden environmental footprint.

Most schools want to be sustainable — but they have no idea how much CO₂ they actually produce every week. This tool makes that footprint **visible, measurable, and actionable**.

**Live Demo → [Click here to open the dashboard](https://chopradhruv19-bit.github.io/greenview-footprint)**

---

## 🌍 The Problem

Climate action feels too global and abstract for schools to act on locally. Schools lack tools that:
- Show their real environmental impact in plain numbers
- Detect patterns and anomalies in energy, water, and transport data
- Tell them exactly what to fix first — ranked by impact

---

## ✅ What We Built

A single-page web dashboard that tracks three footprint categories:

| Category | What it tracks |
|---|---|
| ⚡ Energy | Weekly kWh usage across classrooms, labs, cafeteria, admin |
| 💧 Water | Weekly litres across toilets, cafeteria, labs, garden |
| 🚗 Transport | How 1,200 students commute — CO₂ per mode |

### Key features:
- **Total weekly CO₂** shown with real-world equivalents (car km, trees needed)
- **8-week trend charts** — click any category to switch the chart
- **AI anomaly alerts** — 4 AI-detected patterns flagged in plain English
- **Live AI chat** — ask any question, Claude AI reads the school data and answers
- **Ranked action plan** — top 4 actions with CO₂ savings, cost, and effort
- **Responsible AI panel** — risk, mitigation, and human-in-the-loop explained

---

## 🤖 How the AI Works

```
Input data → Claude AI → Insight → Ranked Action
```

1. **Input** — Synthetic weekly data (energy kWh, water litres, transport modes)
2. **AI reasoning** — Claude (claude-sonnet-4-6) detects patterns, flags anomalies, estimates CO₂, ranks actions
3. **Insight** — Plain-English findings like *"Energy is 22% above 8-week average this week"*
4. **Action** — Prioritised steps like *"Get 10% of car users onto the school bus → saves 210 kg CO₂/week"*

---

## 🛠️ Tools Used

| Tool | Purpose | Cost |
|---|---|---|
| Claude AI (Anthropic) | Core AI engine — pattern detection, Q&A, recommendations | Free tier |
| HTML / CSS / JavaScript | Entire website — single file, no framework | Free |
| Chart.js v4.4.1 | 8-week bar charts for energy, water, transport | Free |
| Google Fonts (Inter) | Clean, readable typography | Free |
| GitHub Pages | Free hosting for the live demo | Free |
| Claude.ai | Used to help design and build this project (disclosed) | Free |

---

## 📊 Data Used

All data is **synthetic** — created to represent a realistic Bengaluru urban school. No real private school data was used.

- **Energy**: 8 weeks of kWh data split across classrooms, labs, cafeteria, admin (878–1,105 kWh/week)
- **Water**: 8 weeks of litre data split across toilets, cafeteria, labs, garden (36,200–46,100 L/week)
- **Transport**: Commute split for 1,200 students across 5 modes
- **CO₂ factors**: India electricity grid 0.82 kg CO₂/kWh (CEA 2023) · Water 0.000298 kg CO₂/L · Transport via IPCC AR6

---

## 🔒 Responsible AI

| | |
|---|---|
| ⚠️ **Risk** | Synthetic data may not match a real school's situation |
| 🔍 **Mitigation** | All assumptions and emission factors are shown transparently on every insight |
| 👩‍🏫 **Human in the loop** | The AI never takes action — every recommendation requires teacher or staff approval |

---

## 👤 Built By

**Dhruv Chopra**
BBA student at IGNOU · Fashion campaign photographer at Dash & Dot

---

*USAII Global AI Hackathon 2026 · Challenge 2 · Direction B · High School Track*
