# Research & Insights

> 💡 Structured notes combining market data, competitor insights, tech feasibility, and validation plans.

---

## 🔍 Market & Industry Research

- The **resume builder market** is expanding rapidly, valued at **$8.29B in 2024**, projected to reach **$8.93B by 2025** (7.7% CAGR), and expected to top **$11.95B by 2029**.
- AI-enhanced resume optimization and ATS integration are top growth drivers.
- **66% of job seekers** report they’ll use AI to create resumes; **62% for cover letters**, and **1 in 6 workers** already landed a job through AI-generated resumes.
- Companies using AI in screening exceed **90% adoption**, accelerating time-to-hire by **73%**.
- A 2023 field study showed algorithmic writing assistance improved hire rates by ~**8%**, without hurting hiring managers’ satisfaction.

---

## 🧭 Market Signals & Trends

- Browser extensions like ResumeGPT and Teal are enabling users to **auto-tailor resumes from job listings**.
- Reddit communities (e.g., r/SideProject) share tools that “tailor your resume in 2 clicks.”
- Academic projects like *ResumeFlow* demonstrate LLM pipelines for automated resume tailoring.

---

## 🛠️ Technical Research

### Architecture & Integrations
- Use serverless backend (e.g., Vercel Functions, Supabase) + **OpenAI or similar LLM** for text generation.
- Browser extension to capture job descriptions. Leverage existing patterns from Teal’s and ResumeGPT's Chrome extensions.
- Simple front-end with Next.js or React; sequential forms + PDF generation.

### Infrastructure & Compliance
- MVP can rely on LocalStorage; later, cloud storage via Supabase.
- Minimal authentication: anonymous or optional email links.
- Be mindful of bias in AI resume evaluation—review fairness research (FAIRE benchmark).

---

## 🏆 Competitive Insights

- Tools like Huntr, Teal, ResumeGPT, and Huntr’s Tailor feature indicate adoption of **real-time job-to-resume matching**.
- Career.io and resume.io show traction with integrated, AI-guided experiences.

---

## 📈 Market Opportunity & Positioning

- The increasing demand for **skill-based hiring** puts AI-driven resume tools in strong standing.
- Position Resume AI as a **context-aware assistant** combining:
  1. Browser job-scraping.
  2. Live job-matched content generation.
  3. Motivational support.

---

## ✅ Immediate Action Items

### Market Validation
- [ ] Showcase market numbers (CAGR, $ value).
- [ ] Prepare landing page tests and waitlists.

### Feature Blocking Research
- [ ] Evaluate privacy constraints on job scraping.
- [ ] Do quick MVP flow test using LocalStorage + OpenAI API.

### Technical Proofs of Concept
- [ ] Prototype browser extraction + API resume generation.
- [ ] Test PDF formatting and styling.

### Stakeholder Readiness
- [ ] Draft simple extension UI and prompt strategy.
- [ ] Investigate anti-bias layers (e.g., name-blind resumes).

---

## 📅 To Do & Timeline

| Task                                       | ETA       |
|--------------------------------------------|-----------|
| Build first MVP flow                       | +2 weeks  |
| Launch landing page & gather 100 pre-signups | +1 week   |
| Conduct 15 user interviews                 | +3 weeks  |
| Prototype browser extension scrap + API    | +4 weeks  |
| Start design of “assistant” dialogues      | +5 weeks  |

---

## 🔗 Reference Links

- Market Size & Growth: Resume Builder Global Market Report 2025
- Browser-extension usage: ResumeGPT & Teal extension pages
- AI hiring adoption stats: Resume-now.com survey
- Academic validation: Algorithmic Writing Assistance + ResumeFlow
- Fairness/bias concerns in evaluation: FAIRE benchmark