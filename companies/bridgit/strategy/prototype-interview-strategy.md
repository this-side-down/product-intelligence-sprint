# Prototype + Interview Strategy — Bridgit

Session 02 artifact. Connects Product Intelligence Sprint research to job search, interview narrative, and prototype direction.

| Field | Value |
|-------|-------|
| **Author context** | Youssef — PM applicant; not pursuing Senior Backend role as identity |
| **Last updated** | 2026-06-29 |
| **Prototype gate** | Planning open — **do not build yet** |

Personal context (not Bridgit facts): Youssef applied to Bridgit PM. He also found a Senior Backend / Applied AI Developer role. Sam Safyari (Nahanni's circle) may provide hiring context. Compensation and seniority fit for PM are open concerns. Goal: demonstrate bridging PM, applied AI, architecture, discovery, workflow thinking, and light implementation — not impersonate a senior backend engineer.

---

## 1. Current state

### FACT (high confidence)

- Bridgit positions as **AI workforce planning for construction** (E005, product pages).
- Evolved from field/PM roots → Bridgit Bench (2019) → broader workforce intelligence (E002, E018, E019).
- Product story: planning, forecasting, internal resumes, Bridgit AI, integrations, communication (v0.1 seed, E006–E008).
- Public AI: Ask Bridgit, Import Roles, Smart Suggestions, explainable summaries (E005).
- Customer voice: Excel/spreadsheets, siloed systems, reporting gaps, manual planning (E020–E022).
- TechCrunch used **"workforce intelligence"** in Oct 2021 — before current AI-led homepage (E018).
- Integrations across CRM, HRIS, PM, ERP, data warehouse are strategically central (E008).

### INFERENCE (medium confidence)

- Durable wedge is **workforce intelligence**, not scheduling (H001 strengthened).
- AI value depends on **trusted connected workforce data** (H002, H008).
- **Reporting and planning artifacts** may beat generic AI chat near-term (H009, E022).
- Specialty/craft expansion is real GTM direction; product/pricing readiness uncertain (H003a/b, E024).
- **Senior Backend / Applied AI job posting** may signal investment in AI infrastructure, data pipelines, workflow agents, recommendation systems, or applied AI productization — **inference from role title/description, not verified internally**.

### SPECULATION (low confidence)

- Move toward **agentic planning workflows** (needs Bridgit "Building Agents" blog review).
- AI-generated executive narratives, staffing meeting agents, scenario explainers as product surface area.
- Suite absorption risk from Procore/ERP (H010).

### PM role — what it likely needs (inference)

- Customer workflow depth in construction workforce planning.
- Prioritization across integrations, AI, forecasting, and adoption.
- Cross-functional work with CS, sales, engineering.
- Evidence of discovery discipline and shipping judgment.

### Backend / Applied AI role — what it may signal (inference)

- Engineering is building **applied AI on workforce data**, not a generic LLM wrapper.
- Likely emphasis: data quality, recommendation/explanation pipelines, possibly agent patterns.
- PM prototype should show **respect for these boundaries** — credible system thinking without claiming to fill that seat.

---

## 2. Prototype goals

A lightweight prototype should prove:

| Capability | How |
|------------|-----|
| Product judgment | Picks a workflow Bridgit already cares about (staffing meetings, scenarios) |
| Grounded discovery | Cites E010, E011, E020–E022; states assumptions |
| Evidence reasoning | Facts vs inferences labeled in demo narrative |
| Applied AI thinking | LLM for narrative + rules/citations — not autonomous staffing |
| Backend fluency | Structured JSON in/out, clear service boundaries |
| Respect for Bridgit | Extends planning cadence; does not replace Bridgit |

Avoid:

- Generic chatbots, fake autonomy, "we built Bridgit better"
- Overbuilt microservices, ungrounded features
- Senior backend portfolio theater

**Strategic narrative:** *"I can help Bridgit figure out what AI-enabled workforce planning should become."*

---

## 3. Prototype opportunity list

### 1. Staffing Meeting Brief / Agent

| Field | Detail |
|-------|--------|
| **Problem** | Excel-heavy prep and long staffing meetings (E011, E010) |
| **Relevance** | Core planning cadence; aligns with Smart Suggestions + AI direction |
| **PM skill** | Workflow mapping, prioritization, artifact design |
| **Technical skill** | Rules + LLM narrative, structured workforce JSON, explainable recs |
| **Could include** | Mock roles, availability, conflicts, brief doc, decision log |
| **Needs** | Mock data; validation that meetings are still central |
| **Overbuild risk** | Medium — agent autonomy, real-time sync |
| **Interview value** | High — shows initiative + Bridgit-specific insight |

### 2. Scenario Explainer

| Field | Detail |
|-------|--------|
| **Problem** | Hard to see pursuit win impact on capacity (E007) |
| **Relevance** | Forecasting / go-no-go |
| **PM skill** | Scenario framing, executive communication |
| **Technical skill** | What-if simulation layer + NL explanation |
| **Could include** | Pipeline change → staffing gap narrative |
| **Needs** | Forecasting object model assumptions |
| **Overbuild risk** | High — full forecast engine |
| **Interview value** | High for COO/BD story |

### 3. Executive Workforce Health Narrative

| Field | Detail |
|-------|--------|
| **Problem** | Reporting / printable outputs weak (E022) |
| **Relevance** | H009, O010 |
| **PM skill** | Executive artifact design |
| **Technical skill** | Aggregation + narrative generation |
| **Could include** | Utilization, bench cost, pipeline risk summary |
| **Needs** | Validate downstream reporting workflow |
| **Overbuild risk** | Low-medium |
| **Interview value** | Medium-high — less differentiated than staffing brief |

### 4. Ops-to-HR Hiring Handoff Packet

| Field | Detail |
|-------|--------|
| **Problem** | Hiring requests lack context (seed, Roles for Hire) |
| **Relevance** | Bridges ops forecasting → HR |
| **PM skill** | Cross-functional workflow |
| **Technical skill** | Template generation from structured gaps |
| **Could include** | Role-for-hire → recruiter brief |
| **Needs** | HR workflow validation |
| **Overbuild risk** | Low |
| **Interview value** | Medium |

### 5. Data Quality Radar

| Field | Detail |
|-------|--------|
| **Problem** | AI/forecast trust requires clean data (H002, H008) |
| **Relevance** | Integration-heavy platform |
| **PM skill** | Trust, adoption, CS partnership |
| **Technical skill** | Validation rules, integration health checks |
| **Could include** | Stale/missing/conflict flags |
| **Needs** | Integration schema assumptions |
| **Overbuild risk** | Medium-high |
| **Interview value** | Medium — strong for eng leader |

### 6. Experience-Based Pursuit Team Builder

| Field | Detail |
|-------|--------|
| **Problem** | Hard to find relevant experience for pursuits (H005 qualified) |
| **Relevance** | Internal Resumes — but E023 suggests shallow skills model |
| **PM skill** | BD/precon workflow |
| **Technical skill** | Search/ranking over project history |
| **Could include** | Pursuit → suggested team from experience graph |
| **Needs** | Skills model depth unknown |
| **Overbuild risk** | High |
| **Interview value** | Medium |

### 7. Role Import Review Queue

| Field | Detail |
|-------|--------|
| **Problem** | Messy PDF/CSV/screenshot intake (E005, Import Roles) |
| **Relevance** | Existing AI feature to extend |
| **PM skill** | Human-in-the-loop design |
| **Technical skill** | Extraction + review UI/API |
| **Could include** | Parsed roles awaiting planner approval |
| **Needs** | Sample messy inputs |
| **Overbuild risk** | Medium |
| **Interview value** | Medium — narrower story |

### 8. Assignment Change Digest

| Field | Detail |
|-------|--------|
| **Problem** | Assignment context lost in email (Communication module, E021) |
| **Relevance** | Change management |
| **PM skill** | Comms workflow |
| **Technical skill** | Diff + digest generation |
| **Could include** | Weekly assignment change summary |
| **Needs** | Notification model |
| **Overbuild risk** | Low |
| **Interview value** | Medium-low |

---

## 4. Best 3 prototype candidates

| Rank | Opportunity | Strategy fit | Sprint believability | PM depth | AI/backend fluency | Interview value |
|------|-------------|--------------|----------------------|----------|-------------------|-----------------|
| **1** | Staffing Meeting Brief / Agent | High | High | High | High | High |
| **2** | Scenario Explainer | High | Medium | High | High | High |
| **3** | Executive Workforce Health Narrative | Medium-high | High | Medium-high | Medium | Medium-high |

**Why #1:** Direct customer pain (E011), matches AI-as-workflow-leverage (H011), buildable with mock JSON + rules + cited LLM narrative in a short sprint.

---

## 5. Suggested prototype scope

**Recommend first build (when gate opens):** Staffing Meeting Brief / Agent

**Scope — prove workflow value, not production architecture:**

| In scope | Out of scope |
|----------|--------------|
| Mock Bridgit-like JSON: projects, roles, people, availability, pipeline deltas | Real Bridgit API integration (unless access granted) |
| Rules layer: conflicts, gaps, double-bookings | Autonomous assignment |
| LLM-generated meeting brief with **citations to source fields** | Multi-tenant auth, production deploy |
| Explainable recommendations (why person X for role Y) | Full agent orchestration |
| Follow-up actions + decision log stub | Senior backend-scale infra |

**Technical shape (when approved):**

- Small backend service or local script
- Structured JSON in → brief + recommendations + actions out
- Rules before LLM; every claim traceable to input row
- Optional simple frontend later

**Gate:** Review Bridgit agent strategy content; validate staffing meetings still central; then build.

---

## 6. Interview narrative

### Recruiter

Genuine interest in construction workforce planning. Did structured research before interviews. Built research repo and identified a concrete workflow to explore — shows initiative without overselling engineering role.

### Hiring manager

Customer problem first: Excel + meetings, reporting friction, disconnected systems. Prototype idea extends existing planning rhythm. Clear on what needs validation vs what is hypothesis.

### Product leader

Strategy frame: workforce intelligence (E018, H001). AI as leverage on connected data — planning artifacts and decision workflows, not chat gimmicks (H011). Aware of craft expansion and suite risk without pretending certainty.

### Engineering leader

Honest scope: mock data, rules + LLM, citations, clear API boundaries. Not competing for senior backend seat — showing fluency to partner with applied AI team. Questions about data model, integration trust, explainability.

### Sam

Human, concise: serious interest in Bridgit's problem space; relevant background in product + applied AI; did homework; would value context on team and hiring — not asking for a favor.

### Compensation / seniority (personal)

May be overqualified for PM title; comp unknown (H007). Frame prototype as **strategic contribution sample** — helps discussion about scope and level, not just checklist fit.

---

## 7. Durable artifacts to create or update

| Artifact | Action |
|----------|--------|
| [prototype-opportunity-register.md](../registers/prototype-opportunity-register.md) | Add O011; link O001 |
| [hypothesis-register.md](../registers/hypothesis-register.md) | Add H011 |
| [research-backlog.md](../backlog/research-backlog.md) | Session 02 items |
| [current-state.md](../continuity/current-state.md) | Session 02 note |
| This file | Session 02 strategy doc |
| Later: `prototype/concept-staffing-meeting-brief.md` | When gate opens |
| Later: prototype README | When code exists |

---

## Related research

- [customer-voice.md](../research/customers/customer-voice.md)
- [competitive-positioning.md](../research/strategy/competitive-positioning.md)
- [roadmap-hypotheses.md](../research/strategy/roadmap-hypotheses.md)
- Session 01: [sessions/2026-06-29-session-01-customer-voice.md](../sessions/2026-06-29-session-01-customer-voice.md)
