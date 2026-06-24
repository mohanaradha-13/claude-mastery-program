# 🧠 Claude Ecosystem Mastery Program

> **An 8-month self-paced curriculum to master Claude AI, prompt engineering, Claude Code, GitHub, MCP servers, and AI engineering — from beginner to professional.**

[![Status](https://img.shields.io/badge/status-active-28c840?style=flat-square)](.) [![License](https://img.shields.io/badge/license-Open%20Source-7c3aed?style=flat-square)](.) [![Built With](https://img.shields.io/badge/built%20with-Vanilla%20HTML%2FJS-2563eb?style=flat-square)](.) [![MCQs](https://img.shields.io/badge/MCQs-640%20questions-ea580c?style=flat-square)](.) [![Progress](https://img.shields.io/badge/progress-saved%20locally-059669?style=flat-square)](.)</

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Live Demo](#-live-demo)
- [Features](#-features)
- [Curriculum Structure](#-curriculum-structure)
- [MCQ Assessment System](#-mcq-assessment-system)
- [How to Use](#-how-to-use)
- [Progress Tracking](#-progress-tracking)
- [Technical Details](#-technical-details)
- [File Structure](#-file-structure)
- [Author](#-author)

---

## 🎯 Overview

The **Claude Ecosystem Mastery Program** is a fully self-contained, single-file HTML curriculum tracker and assessment platform. Built for learners who want a structured, measurable path through the entire Claude AI ecosystem — from understanding what an LLM is all the way to deploying production AI systems and launching an AI engineering career.

**No server. No login. No dependencies.** Open the HTML file in any browser and start learning.

| Metric | Value |
|--------|-------|
| Duration | 8 months |
| Daily commitment | 2 hours/day, 5 days/week |
| Total topics | 192 daily lessons |
| Weekly projects | 32 (one per week) |
| Weekly quizzes | 32 × 10 MCQs = **320 questions** |
| Monthly exams | 8 × 40 MCQs = **320 questions** |
| Total MCQs | **640 unique questions** |
| Cost | Free |

---

## 🚀 Live Demo

This is a **single-file application** — no build step, no server required.

```bash
# Option 1 — just open in browser
open claude_mastery_complete.html

# Option 2 — serve locally for best experience
npx serve . -p 3000
# then visit http://localhost:3000/claude_mastery_complete.html
```

---

## ✨ Features

### 🗺️ Curriculum Roadmap
- **8 months of structured content** organized by phase, month, and week
- Expandable week cards showing daily topics (6 per week)
- Per-week project briefs displayed inline
- Month-level progress rings with live percentage
- Color-coded phases matching the program's learning arc
- Month timeline navigation bar for quick switching

### 🧪 MCQ Assessment Engine
- **640 total MCQs** — 320 weekly + 320 monthly, zero duplicates
- Weekly quizzes: **10 scenario-based questions** per week
- Monthly exams: **40 applied/scenario questions** per month (harder, distinct pool)
- Instant visual feedback after any option click:
  - ✅ Correct answer → **green highlight** with ✓ checkmark
  - ❌ All other options → **red highlight** with ✕ mark
- **💡 Show Answer** button — explanation hidden by default, revealed on click
- **👁 Show All Answers** — reveals all explanations at once
- Live score pill tracking `correct / total` in real time
- Scores persist across sessions — green badge shows your best attempt

### 🖥️ macOS-Style Quiz Modal
- Authentic Mac window chrome with traffic light dots (🔴🟡🟢)
- Spring-pop open animation with backdrop blur
- Filename in titlebar: `WeeklyQuiz.js` / `MonthlyExam.js`
- Close via: red dot button / ESC key / click outside the window

### 💾 Progress Tracking
- Topic completion checkboxes saved to `localStorage`
- Quiz scores (per-question answers + final score) persisted
- Export progress as JSON for backup
- Import progress JSON to restore or transfer
- Reset all progress with confirmation guard

### 📊 Overview Dashboard
- Full 8-month grid view with per-month progress bars
- Click any month card to jump directly to that month
- Monthly exam score shown on each card when completed

### 📅 Daily Plan & Resources
- 120-minute daily breakdown with visual time bar
- 8-step lesson format for every topic
- Assessment calendar showing weekly and monthly rhythm
- Curated resource list organized by category

---

## 📚 Curriculum Structure

| Month | Phase | Focus Area |
|-------|-------|------------|
| **Month 1** 🧠 | Beginner Foundation | Claude AI basics, Projects, Artifacts, Memory |
| **Month 2** ✍️ | Prompt Engineer | Prompt engineering, context, agent prompting |
| **Month 3** 💻 | Claude Code Specialist | CLI, code generation, debugging, testing |
| **Month 4** 🔧 | Dev Tools Professional | Git, GitHub, VS Code, AI-assisted development |
| **Month 5** 🔗 | Integration Specialist | Connectors, MCP architecture, building MCP servers |
| **Month 6** ⚙️ | AI Engineer | Python + API, RAG systems, AI agents |
| **Month 7** 🚀 | Portfolio Builder | 3 production projects, GitHub portfolio |
| **Month 8** 🎯 | Career Ready | Interview prep, LinkedIn, freelancing, career plan |

### Daily Schedule (120 min/day)

```
📖 Concept Learning     30 min   Read docs, watch tutorials
⚡ Hands-on Practice    40 min   Build mini-projects, experiment  
📝 Exercises            25 min   Complete challenges
🔄 Revision & Notes     15 min   Summarize in your own words
🧪 Quick Quiz           10 min   5-question self-check
```

### Lesson Format (Every Topic)

Every lesson follows an 8-step structure:

1. **Concept Explanation** — First-principles breakdown
2. **Why It Matters** — Real-world relevance
3. **Live Example** — Working demo or walkthrough
4. **Hands-on Practice** — You build it
5. **Homework** — Extended practice
6. **Common Mistakes** — Pitfalls to avoid
7. **Interview Questions** — Real job prep
8. **Summary Notes** — Quick-reference card

---

## 🎓 MCQ Assessment System

### Weekly Quizzes (10 Questions Each)
- Appear as a **🧪 Weekly Quiz** button inside each expanded week card
- Cover that week's specific topics at **beginner to intermediate** level
- Immediate feedback on every answer
- Score saved with green badge: `✓ 9/10`

### Monthly Exams (40 Questions Each)
- Appear as a **🏆 Monthly Exam** button inside the **last week** of each month
- **100% different questions** from weekly quizzes — no duplicates
- Applied and scenario-based: "You are building X, what do you do?"
- Harder difficulty — tests integration of the month's concepts
- Score saved with badge on both the week card and the overview grid

### Answer Behavior

```
Before answering:     [ A ] [ B ] [ C ] [ D ]   (neutral, all clickable)

After clicking B:     [ A ✕]  [✅ B ✓]  [ C ✕]  [ D ✕]
  ↳ If B was wrong:   [ A ✕]  [ B ✕]   [✅ C ✓]  [ D ✕]
                       ← all wrong options red → ← correct always green →

Show Answer button:   [hidden by default] → click to reveal explanation
```

---

## 🛠️ How to Use

### Getting Started

1. **Download** `claude_mastery_complete.html`
2. **Open** in any modern browser (Chrome, Firefox, Safari, Edge)
3. Click **Month 1** in the timeline
4. Expand **Week 1** to see daily topics
5. Check off topics as you complete them
6. Take the **Weekly Quiz** at the end of each week
7. Take the **Monthly Exam** at the end of each month

### Navigation

| Element | Action |
|---------|--------|
| Month timeline (M1–M8) | Click to switch months |
| Week card header | Click to expand/collapse |
| Topic checkbox | Click to mark complete |
| 🧪 Weekly Quiz button | Opens 10-question modal |
| 🏆 Monthly Exam button | Opens 40-question modal (last week only) |
| 📍 Roadmap tab | Full curriculum view |
| ⏰ Daily Plan tab | Schedule and lesson format |
| 📚 Resources tab | Curated tools and links |

### Quiz Modal Controls

| Control | Action |
|---------|--------|
| Red dot `●` / ESC | Close quiz, save score |
| Click outside window | Close quiz, save score |
| 💡 Show Answer | Toggle explanation for one question |
| 👁 Show All Answers | Reveal all explanations at once |
| Option A / B / C / D | Click to answer — locks immediately |

---

## 💾 Progress Tracking

All progress is stored in your browser's `localStorage` — no account or server needed.

### Export / Import

**Export:** Click **⬇ Export** in the nav bar → downloads `claude-mastery-progress.json`

```json
{
  "v": 3,
  "exported": "2025-06-24T10:30:00.000Z",
  "progress": {
    "topics": {
      "m1w1t0": 1703001600000,
      "m1w1t1": 1703001660000
    },
    "quizzes": {
      "m1w1": { "score": 9, "total": 10, "answers": {...} },
      "m1":   { "score": 36, "total": 40, "answers": {...} }
    }
  }
}
```

**Import:** Click **⬆ Import** → select your `.json` file → progress restored.

**Reset:** Click **⌫ Reset** → confirm → all progress cleared.

> ⚠️ **Tip:** Export your progress before clearing browser data or switching devices. Import it back anytime.

---

## 🔧 Technical Details

### Stack

| Layer | Technology |
|-------|-----------|
| Structure | Vanilla HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, blur, gradients) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Inter (body) + JetBrains Mono (code elements) via Google Fonts |
| Storage | Browser `localStorage` |
| Dependencies | **Zero** — fully self-contained |

### Architecture

The entire application is a **single HTML file** (~201 KB):

```
[CSS]           ~300 lines   — variables, layout, components, quiz modal styles
[HTML]          ~100 lines   — hero, nav, quiz overlay, main sections, footer
[JavaScript]
  ├── CURRICULUM        ~200 lines   — 8 months × 4 weeks × 6 topics + projects
  ├── DAILY / FORMATS   ~40 lines    — schedule and lesson format data
  ├── RESOURCES         ~40 lines    — curated links by category
  ├── WEEKLY_MCQS       ~360 lines   — 320 questions (32 weeks × 10)
  ├── MONTHLY_MCQS      ~380 lines   — 320 questions (8 months × 40)
  └── Engine            ~400 lines   — state, render functions, quiz, events
```

### Browser Support

Works in all modern browsers. Requires:
- CSS `backdrop-filter` (Chrome 76+, Safari 9+, Firefox 103+)
- CSS custom properties
- `localStorage`
- ES6+ JavaScript

### Storage Key

```javascript
localStorage key: 'claude-mastery-v3'
```

---

## 📁 File Structure

```
claude_mastery_complete.html   ← The entire application (single file)
README.md                      ← This file
```

**Optional companion files** (source data, for reference):
```
part2_data_m1_m2.js    ← Weekly MCQ source data (months 1–2)
part3_data_m3_m4.js    ← Weekly MCQ source data (months 3–4)
```

---

## 🎨 Design System

The UI uses a **light theme with multicolor syntax-inspired palette** and macOS design language:

| Token | Color | Used For |
|-------|-------|----------|
| `--accent` | `#7c3aed` | Purple — primary, keywords |
| `--blue` | `#2563eb` | Blue — functions, links |
| `--green` | `#059669` | Green — strings, success |
| `--amber` | `#d97706` | Amber — numbers, highlights |
| `--red` | `#e11d48` | Red — types, danger, errors |
| `--cyan` | `#0891b2` | Cyan — variables, Month 7 |
| `--orange` | `#ea580c` | Orange — Month 8, exports |
| Mac red | `#FF5F57` | Traffic light close button |
| Mac yellow | `#FEBC2E` | Traffic light minimize button |
| Mac green | `#28C840` | Traffic light maximize button |

---

## 🗓️ Suggested Study Timeline

```
Month 1  🧠  Jan    — Claude Foundations
Month 2  ✍️  Feb    — Prompt Engineering
Month 3  💻  Mar    — Claude Code & CLI
Month 4  🔧  Apr    — GitHub & VS Code
Month 5  🔗  May    — Connectors & MCP
Month 6  ⚙️  Jun    — AI Engineering
Month 7  🚀  Jul    — Projects & Portfolio
Month 8  🎯  Aug    — Career Launch
```

> **Recommended pace:** 5 days/week × 2 hours/day. Weekends for review and projects.

---

## 🙏 Credits & Acknowledgements

| Resource | Purpose |
|----------|---------|
| [Anthropic](https://anthropic.com) | Claude AI — the subject of this curriculum |
| [Claude Documentation](https://docs.anthropic.com) | Primary reference material |
| [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook) | Code examples and patterns |
| [JetBrains Mono](https://www.jetbrains.com/legalnotices/terms-of-use/) | Monospace font (via Google Fonts) |
| [Inter](https://rsms.me/inter/) | Body font (via Google Fonts) |

---

## 📄 License

**Open Source** — free to use, share, and modify for personal learning and non-commercial education purposes.

If you adapt this for your own curriculum or institution, please credit the original.

---

## 👩‍💻 Author

**A. Mohanaradha**  
Corporate Relations Coordinator · AI Educator · PhD Scholar  
📍 Pondicherry, India

> *"Built not for certificates, but for capability. The goal is not to finish — it's to become."*

---

<div align="center">

**Claude Ecosystem Mastery Program** · Open Source · 2025

*Your progress is saved locally. Your future is built daily.*

</div>
