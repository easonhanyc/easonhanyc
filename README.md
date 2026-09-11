# Yichen (Eason) Han

**MBA / MEng candidate at UC Berkeley — Haas & IEOR.** Three years at **AWS** building analytics products for an $80B sales org. Now I write the PRD, cut the roadmap, and build the thing.

📍 Berkeley, CA · 🎯 **Seeking a Summer 2027 Product Management internship**

---

## 🚗 TripMatch — shipped, live, and used by a 400-person cohort

**[tripmatch-app.github.io](https://tripmatch-app.github.io/)** · *Sole PM, designer, and engineer · PRD to public launch in 6 days*

My cohort coordinated ad-hoc rides by scrolling a 400-person WhatsApp chat, where requests get buried and matching seats go unused. I shipped a verified, Berkeley-only rides board — problem framing through production.

**The decision I'd point to:** I rebuilt my own v1 storage architecture *the day before launch*, after finding three defects that would have broken it inside its own expected load — including a race condition that let two simultaneous posts silently delete each other. The user experience of that bug is *you post, you see it appear, and on refresh it's gone* — which makes people post again, which makes the race more likely. Launch day meant a link landing in front of 400 people at once. I'd rather kill a week of my own work than ship that.

| 34 | 168 | 3 | 6 |
|:--:|:---:|:--:|:--:|
| commits in 6 days | automated checks | feedback-driven iterations | days to launch |

**[📖 Read the case study](https://easonhanyc.github.io/case-studies/tripmatch.html)** · **[📋 The PRD](https://easonhanyc.github.io/artifacts/tripmatch-prd.html)** · **[🏗 Pre-launch architecture review](https://easonhanyc.github.io/artifacts/tripmatch-infrastructure.html)** · **[💻 Source](https://github.com/tripmatch-app/tripmatch-app.github.io)**

---

## 📁 Case studies

| | What it shows |
|---|---|
| **[TripMatch](https://easonhanyc.github.io/case-studies/tripmatch.html)**<br>*0→1, shipped alone* | Scoping a one-week build with explicit non-goals, iterating on real user feedback, and killing my own architecture rather than shipping a known defect |
| **[AWS Sales Insights Platform](https://easonhanyc.github.io/case-studies/aws-insights-platform.html)**<br>*0→1 at scale* | Owning an end-to-end launch for **10,000 sellers** — user interviews, PRD, Figma, roadmap. **70% less time-to-insight**; data-request resolution **56% → 82%** |
| **[AI Code-Review Automation](https://easonhanyc.github.io/case-studies/ai-code-review.html)**<br>*AI product judgment* | Shipping an agentic tool that cut manual review time **80%** — and deciding which parts of the review it was *allowed to be wrong about* |

## 🧰 Artifacts

Working documents, not just summaries — so the reasoning is inspectable rather than asserted.

- **[TripMatch PRD](https://easonhanyc.github.io/artifacts/tripmatch-prd.html)** — problem framing, non-goals, user stories, P0/P1/P2 with acceptance criteria, success metrics, and the open questions I never closed
- **[Pre-launch architecture review](https://easonhanyc.github.io/artifacts/tripmatch-infrastructure.html)** — what would have broken, at what load, and the mitigation
- **[Prioritization framework](https://easonhanyc.github.io/artifacts/prioritization-framework.html)** — four ordered gates for cutting a roadmap, and why scoring an incomparable list is theater
- **[Metric trees & scenario forecasting](https://easonhanyc.github.io/artifacts/metric-tree.html)** — separating liquidity failure from discoverability failure; forecasting a category with no history

---

## 💭 How I work

**Non-goals are the product decision.** TripMatch shipped in six days because I wrote down what it would never do — no payments, no dispatch, no native app, no WhatsApp replacement — before writing any code.

**Distribution is a technical constraint, not just a growth decision.** TripMatch's nastiest bug: a link tapped in WhatsApp opens in that app's built-in browser, where Google's popup sign-in has no window to return a credential to and dies on a blank page. The product's entire distribution channel was also its single point of auth failure — and it was invisible in desktop testing.

**I write the limitations down.** Every case study ends with what I'd do differently, and the PRD carries its unresolved questions in the open. A portfolio of only wins isn't evidence of judgment — it's evidence of editing.

---

## 👤 Background

| | | |
|---|---|---|
| **UC Berkeley** — Haas & IEOR | MBA / M.Eng. Industrial Engineering & Operations Research | 2028 |
| **Amazon Web Services** | Business Intelligence Engineer — Global Sales Strategy & Analytics | 2023–2026 |
| **TikTok** | Ads Risk Integrity Intern — 35% reduction in high-risk ad exposure | 2021 |
| **IDG Capital** | Venture Capital Analyst Intern | 2020 |
| **University of Notre Dame** | B.B.A. Business Analytics · B.S. Applied Mathematics | 2023 |

**Product** — PRD writing, MVP definition, roadmapping, backlog prioritization, user research, metric design
**Technical** — SQL · Python · R · JavaScript · Tableau · QuickSight · Figma · Salesforce · Cloudflare Workers/D1
**Certified** — AWS AI Practitioner · AWS Data Engineer Associate · Tableau Certified Data Analyst

---

### 📬 Reach me

**[eason_han@berkeley.edu](mailto:eason_han@berkeley.edu)** · **[LinkedIn](https://www.linkedin.com/in/yichen-eason-han/)** · **[Portfolio](https://easonhanyc.github.io)**

<sub>Open to Summer 2027 PM internships — consumer, AI/GenAI, and enterprise/data products.</sub>
