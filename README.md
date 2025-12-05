# 🎯 PlayGTM — AI-Powered GTM Planning & Pipeline Intelligence

**PlayGTM** is the GTM intelligence engine inside the **PlayHero Platform**.  
It helps SaaS teams model pipeline, align GTM strategy, identify bottlenecks, and execute faster with AI.

This public repo provides a high-level overview, architecture, and product direction.  
The full production code lives in a private monorepo while PlayGTM is in active development.

---

## 🚀 What PlayGTM Does

PlayGTM brings clarity and speed to GTM teams with:

- Pipeline modeling & forecasting  
- GTM plan generation (strategic + tactical)  
- Scenario planning (best / base / worst)  
- Funnel and conversion diagnostics  
- Anomaly detection & automated alerts  
- Budget planning and GTM investment modeling  
- AI-assisted execution through Rallyboard  
- Blitz Mode for speed-to-pipeline acceleration  

It serves CMOs, CROs, CEOs, RevOps, and GTM leaders who need a unified system to plan, execute, and adapt.

---

## 🧠 Core Modules

### **Rallyboard**  
A collaborative GTM execution canvas enabling Marketing, Sales, and RevOps to stay aligned in real time.

### **Blitz Mode**  
AI-generated acceleration sequences for when teams fall behind pipeline targets.

### **Pipeline Intelligence Engine**  
Models pipeline by segment, persona, region, and motion.

### **Anomaly Detector**  
Automatically detects unexpected drops or spikes in key GTM metrics.

### **Revenue Dashboards**  
CMO, CRO, and CEO views built for decision-making clarity.

### **AI Sidekick**  
Summaries, insights, recommendations, and GTM play generation.

---

## 📐 Architecture Overview

```txt
playgtm
├── dashboard
│   ├── cmo
│   ├── cro
│   └── ceo
│
├── rallyboard
│   ├── cards
│   ├── swimlanes
│   └── collaboration
│
├── blitz
│   ├── accelerator
│   └── play-sequencer
│
├── data
│   ├── pipeline
│   ├── forecasting
│   └── anomaly-detection
│
└── ui
    ├── components
    ├── charts
    └── layouts
````

---

## 🏗 Tech Stack

* **Next.js 15** (App Router + RSC)
* **Vercel** (deploy, edge compute, AI SDK)
* **Supabase** (DB, auth, RLS, real-time sync)
* **Tailwind CSS + shadcn/ui**
* **TypeScript**
* **pnpm monorepo**
* **Vercel AI SDK** (OpenAI-powered AI actions)

---

## 📊 Product Capabilities

* Full-funnel modeling (TOFU → Close)
* Cross-team collaboration (Marketing, Sales, Ops)
* GTM strategic plan generation
* Quarterly pipeline planning
* Customizable views by segment/motion
* Dashboards for CMO / CRO / CEO
* Auto-suggested GTM plays
* Alerts & anomaly detection
* GTM scenario modeling
* Budget + resource planning

---

## 🛠 Current Development Areas

* Rallyboard UI/UX refinements
* Blitz Mode play-sequencing engine
* Pipeline intelligence model v2
* DSv1 design system application
* Multi-agent tick loop integration
* CMO/CRO/CEO dashboard expansion

---

## 🔗 Live Link

* **PlayHero** → [https://playhero.ai](https://playhero.ai)

---

## 📬 Contact

**Mike Greeves** — Founder, PlayHero

* LinkedIn → [https://www.linkedin.com/in/michaelgreeves](https://www.linkedin.com/in/michaelgreeves)
* X → [https://x.com/mjgreeves](https://x.com/mjgreeves)
* Web → [https://www.webux.ai](https://www.webux.ai)

---

Always building, always shipping.
