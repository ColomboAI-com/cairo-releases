<p align="center">
  <img src="https://cairo.colomboai.com/logo.png" alt="Cairo Logo" width="100" />
</p>

<h1 align="center">CAIRO</h1>

<p align="center">
  <strong>The Platform Where Autonomous Companies Are Built.</strong><br/>
  <em>Not agents. Not copilots. Not workflows. Companies.</em>
</p>

<p align="center">
  <a href="https://cairo.colomboai.com"><img src="https://img.shields.io/badge/🌐_Launch_WebUI-cairo.colomboai.com-black?style=for-the-badge" /></a>
  &nbsp;
  <a href="https://github.com/ColomboAI-com/cairo-releases/releases/latest"><img src="https://img.shields.io/badge/⬇️_Download_Desktop-Latest_Release-black?style=for-the-badge" /></a>
  &nbsp;
  <a href="https://x.com/ColomboAI"><img src="https://img.shields.io/badge/Follow-@ColomboAI-black?style=for-the-badge&logo=x" /></a>
</p>

<p align="center">
  <a href="https://github.com/ColomboAI-com/cairo-releases/releases/latest"><img src="https://img.shields.io/github/v/release/ColomboAI-com/cairo-releases?style=flat-square&color=black&label=Latest%20Release" /></a>
  &nbsp;
  <img src="https://img.shields.io/badge/platform-macOS%20%7C%20Windows%20%7C%20Linux-555?style=flat-square" />
  &nbsp;
  <img src="https://img.shields.io/badge/WebUI-Live%20Now-brightgreen?style=flat-square" />
</p>

---

## 🧠 The Shift Everyone Missed

```
LLMs        →  you talk to AI
Agents      →  AI does one task
Assistants  →  AI helps you work
                        ↓
Autonomous Companies  →  AI IS the company  ✅
```

Cairo is the first platform where you define a company, deploy it, and let it **operate itself** — 24/7, with real actions, real integrations, and real governance.

---

## 🚀 Try It Right Now

### 🌐 No install — use the live WebUI

> **[https://cairo.colomboai.com](https://cairo.colomboai.com)**

Open your browser. Sign in. Start building.

### 💻 Or download the desktop app

| Platform | Download |
|----------|----------|
| 🍎 macOS | [Download `.dmg`](https://github.com/ColomboAI-com/cairo-releases/releases/latest) |
| 🪟 Windows | [Download `.exe`](https://github.com/ColomboAI-com/cairo-releases/releases/latest) |
| 🐧 Linux | [Download `.AppImage` / `.deb`](https://github.com/ColomboAI-com/cairo-releases/releases/latest) |

> Cairo auto-updates. When a new version ships, you'll be notified in-app — one click to upgrade.

---

## 🏗️ What You Can Build in Minutes

Cairo ships with a real **AI Marketing Agency** template out of the box. Here's what it does autonomously:

```
payment_received event fires
        ↓
billing_operator validates payment  (autonomous, LOW risk)
        ↓
outreach_operator composes email    (requires your approval)
        ↓
Gmail sends via Composio            (100+ app integrations)
        ↓
KPI dashboard updates               (emails_sent++)
```

No code. No infrastructure. No team. **One company definition file.**

Other companies you can build today:

| Company Type | What It Does |
|---|---|
| AI Legal Company | Reviews contracts, flags risks, drafts responses |
| AI Sales Org | Qualifies leads, sends outreach, tracks pipeline |
| AI Marketing Agency | Runs campaigns, processes payments, sends emails |
| AI Recruiting Firm | Screens candidates, schedules interviews, sends offers |
| AI Accounting Company | Processes invoices, tracks spend, generates reports |
| AI Customer Support | Handles tickets, escalates issues, closes loops |
| AI SaaS Operator | Manages onboarding, billing, and retention automatically |

---

## ⚙️ How Cairo Works

Cairo turns AI into **operational systems** — not chat windows.

```
Skills → Plugins → Operators → Departments → Autonomous Company
```

| Layer | What it is |
|---|---|
| 🧩 **Skills** | Atomic capabilities: generate contracts, analyze data, send emails, query APIs |
| 🔗 **Plugins** | Domain orchestration: legal plugin, marketing plugin, finance plugin |
| 🤖 **Operators** | Active AI workers running 24/7: sales operator, legal operator, support operator |
| 🏢 **Departments** | Coordinated execution layers: Sales, Marketing, Ops, Finance, Legal |
| 🌍 **Autonomous Company** | Full org that takes actions, responds to events, coordinates internally, operates continuously |

---

## 🔥 The Engine Under the Hood

### ACDL — Agentic Cognitive Design Language
Define companies like code. Human-readable, machine-validated, diff-friendly.

```yaml
---
type: company
id: ai_marketing_agency
version: "1.0"
departments:
  - billing_department
  - outreach_department
policies:
  - payment_approval_policy
kpis:
  - payments_processed
  - emails_sent
---
```

### ACE — Autonomous Company Engine
Executes your company. Manages operator lifecycle, workflow orchestration, governance enforcement, kill switches, and KPI monitoring.

```python
# Every operator runs this loop — continuously
while operator.status == "active":
    signals  = observe()
    context  = load_memory(signals)
    decision = decide(signals, context)
    action   = policy_guard(decision)   # governance check
    result   = act(action)
    write_memory(result)
    emit_events(result)
```

### EIL — Event Intelligence Layer
Makes your company reactive to the real world.

```
IF payment_received    → trigger billing workflow
IF lead_created        → trigger sales outreach
IF churn_risk_detected → trigger retention campaign
IF support_ticket      → trigger resolution operator
```

### Memory + State
Your company remembers every interaction, adapts to patterns, and improves over time — powered by Mem0 long-term memory.

### Governance Built In
Every action passes through OPA policy checks before execution. Destructive actions (send email, delete, payment) require explicit human approval. Kill switches stop everything in under 2 seconds.

---

## 🤖 Multi-Model. Any AI. Full Power.

Cairo connects to every major AI provider — you're never locked in.

| Provider | Models |
|---|---|
| OpenAI | GPT-4o, GPT-4, GPT-3.5 |
| Anthropic | Claude 3.5 Sonnet, Claude 3 Opus |
| Google | Gemini 1.5 Pro, Gemini Flash |
| DeepSeek | DeepSeek-V3, DeepSeek-R1 |
| OpenRouter | 100+ models via unified API |
| Ollama / LM Studio | Local models, fully private |
| AWS Bedrock | Enterprise-grade cloud models |

---

## 🔌 100+ App Integrations via Composio

Cairo operators can take real actions across your entire stack:

**Communication** — Gmail, Slack, Telegram, DingTalk, Lark (Feishu)

**Productivity** — Notion, Google Docs, Google Sheets, Jira, Linear

**Sales & CRM** — Salesforce, HubSpot, Pipedrive

**Dev Tools** — GitHub, GitLab, Jira, Linear

**Finance** — Stripe, QuickBooks

**And 90+ more** — if it has an API, Cairo can use it.

---

## 🛠️ Built-In Skills — Ready to Use

Cairo ships with a full skill library. No setup required.

| Skill | What it does |
|---|---|
| 🌐 Web Search | Real-time web research |
| 🧠 Memory | Persistent cross-session knowledge |
| 📊 Excel / BI | Analyze and generate spreadsheets |
| 📄 PPTX Generator | Create presentations from prompts |
| 📝 DOCX | Generate formatted Word documents |
| 🖼️ Image Generation | AI image creation |
| 🔍 Browser Automation | Control web UIs autonomously |
| 📋 PDF Processing | Extract, analyze, convert PDFs |
| 📈 Mermaid Diagrams | Auto-generate flowcharts and diagrams |
| 🛒 Form Fill | Autonomously fill web forms |

---

## 📡 Access Cairo From Anywhere

Cairo isn't just a desktop app. It's a platform you can reach from any device.

- **WebUI** — [cairo.colomboai.com](https://cairo.colomboai.com) — use from any browser, any device
- **Desktop App** — native Electron app for macOS, Windows, Linux
- **Telegram** — chat with your Cairo operators directly from Telegram
- **DingTalk** — AI Card streaming with automatic fallback
- **Lark / Feishu** — enterprise collaboration via Feishu bots
- **REST API** — integrate Cairo into your own products via `/v1/cairo/chat`

---

## ⚔️ Cairo vs Everything Else

| | ChatGPT / Claude | AutoGPT / CrewAI | **Cairo** |
|---|---|---|---|
| What you get | Chat interface | Agent framework | **Autonomous company platform** |
| Runs 24/7 | ❌ | Partial | ✅ |
| Real app integrations | Limited | Manual setup | ✅ 100+ via Composio |
| Governance & approval gates | ❌ | ❌ | ✅ Built-in OPA |
| Memory across sessions | ❌ | ❌ | ✅ Mem0 long-term memory |
| Multi-department coordination | ❌ | ❌ | ✅ |
| Kill switch | ❌ | ❌ | ✅ Stops in <2 seconds |
| Desktop + WebUI + API | ❌ | ❌ | ✅ |
| Human approval gates | ❌ | ❌ | ✅ |

---

## 🌍 Why This Matters

For the first time in history:

👉 **Anyone can build a company** — no hiring, no infrastructure, no ops team  
👉 **Anyone can operate a company** — define it once, it runs itself  
👉 **Anyone can scale a company** — add operators, not headcount  

```
Before Cairo:  build product → hire team → manage ops → scale manually
With Cairo:    define company → deploy → operate autonomously → scale infinitely
```

---

## 🏪 Marketplace — Coming Soon

- Skills marketplace — install atomic capabilities
- Plugin marketplace — domain-level integrations
- Operator marketplace — pre-built AI workers
- **Autonomous Company marketplace — install entire companies like apps**

---

## 🔒 Security & Governance

Cairo is built for production from day one:

- Every action passes through **OPA (Open Policy Agent)** policy checks
- **Destructive actions** (send email, delete, payment) require explicit human approval
- **Kill switches** halt all operator loops within 2 seconds
- **Tenant isolation** — cross-tenant event routing is architecturally impossible
- **Audit trail** — every decision, action, and outcome is logged
- **Rate limiting** — Redis token bucket with in-memory fallback
- **Local data** — desktop app stores all data in local SQLite, nothing uploaded without your consent

---

## 📦 Tech Stack

| Layer | Technology |
|---|---|
| Desktop | Electron + React 19 + TypeScript |
| WebUI | Next.js (live at cairo.colomboai.com) |
| Backend | FastAPI (async Python) |
| AI Brain | MC-1 by ColomboAI (OpenAI-compatible) |
| Memory | Mem0 + ChromaDB |
| App Integrations | Composio (100+ apps) |
| Policy Engine | OPA (Open Policy Agent) |
| Code Execution | E2B cloud sandboxes |
| Browser Automation | browser-use |
| Observability | OpenTelemetry + Prometheus + Sentry |
| Deployment | Docker + GCP Cloud Run |

---

## ⭐ If Cairo is useful to you

**Star this repo** — it helps more builders discover Cairo and join the movement.

Every star tells us: *keep building*.

---

## 📬 Stay in the Loop

- **Website**: [cairo.colomboai.com](https://cairo.colomboai.com)
- **Twitter/X**: [@ColomboAI](https://x.com/ColomboAI)
- **Contact**: [colomboai.com/contact](https://colomboai.com/contact)
- **ColomboAI**: [colomboai.com](https://colomboai.com)
- **Releases**: [All versions](https://github.com/ColomboAI-com/cairo-releases/releases)

---

<p align="center">
  <a href="https://cairo.colomboai.com"><strong>→ Launch Cairo Now</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/ColomboAI-com/cairo-releases/releases/latest"><strong>→ Download Desktop App</strong></a>
</p>

<p align="center">
  <strong>Build companies that build themselves.</strong>
</p>

<p align="center">
  © 2026 ColomboAI Inc. All rights reserved.
</p>
