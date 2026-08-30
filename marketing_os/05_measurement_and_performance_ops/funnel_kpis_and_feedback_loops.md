# Full-Funnel KPI Hierarchy, Attribution Models & Learning Feedback Loops

## Document Metadata & Epistemic Status
- **Author**: Japan Global Network (JGN) Growth Engineering & Continuous Learning Team
- **Document Type**: Full-Funnel KPI Architecture, Attribution SOP & Retrospective Learning Loop Framework
- **Target Surfaces**: Marketing Lead, Campaign Operators, Community Managers, Admissions Committee
- **Epistemic Classification**:
  - Funnel Hierarchy & Learning SOPs: `[Confirmed Fact]`
  - Attribution Modeling & Live Instrumentation: `[Web-Verified]`
  - Multi-Node Predictive LTV Models: `[Inference]`
- **Core Mission**: Establish a closed-loop system where marketing data immediately refines narrative positioning, editorial pillars, and physical resident operations.

---

## 1. The Full-Funnel KPI Hierarchy (TOFU → MOFU → BOFU → Retention)

To systematically diagnose performance bottlenecks and optimize conversion velocity, the marketing engine tracks distinct Key Performance Indicators across every funnel stage:

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                 THE FULL-FUNNEL KPI HIERARCHY                                    │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                  │
│   TOP OF FUNNEL (TOFU): DISCOVERY & ATTENTION                                                    │
│   • Target: Qualified Attention & Resonance                                                      │
│   • Metrics: High-intent website visitors, Reel saves, Substack subscriber growth                │
│                                      ▼                                                           │
│   MIDDLE OF FUNNEL (MOFU): CONSIDERATION & COMMUNITY ENGAGEMENT                                  │
│   • Target: Community Trust & Intent                                                             │
│   • Metrics: Verified Discord intros, Town Hall attendance, speedtest proof page views          │
│                                      ▼                                                           │
│   BOTTOM OF FUNNEL (BOFU): CONVERSION & PHYSICAL COMMITMENT                                      │
│   • Target: Economic & Physical Traction                                                         │
│   • Metrics: Residency applications submitted, paid stay bookings, deposit conversion rate       │
│                                      ▼                                                           │
│   RETENTION & EXPANSION: ADVOCACY & CITIZENSHIP                                                  │
│   • Target: Compounding Network Density                                                          │
│   • Metrics: Resident NPS, repeat stay rate, Working Group bounty completion, alumni referrals    │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## 2. Stage-by-Stage KPI Taxonomy & Operational Benchmarks

| Funnel Stage | Primary Objective | Key Metric | Target Healthy Benchmark | Measurement Frequency | Root Cause Diagnostic if Lagging |
|---|---|---|---|---|---|
| **TOFU (Top of Funnel)** | Attract aligned builders, creators, and regional revitalizers. | **Qualified Web Traffic to `zucity.org`** | $\ge 15,000$ unique visitors / mo | Weekly | Headline hook fatigue; lack of architectural visual assets; insufficient cross-posting. |
| **TOFU (Top of Funnel)** | Build long-term intellectual subscriber base. | **Substack / Newsletter Net New Subs** | $\ge 250$ net new subs / mo | Weekly | Essays too promotional; insufficient deep-dive analysis on *The Network State* / Akiya economics. |
| **MOFU (Mid Funnel)** | Move audience from passive viewing to active community participation. | **Discord Member Verification Rate** | $\ge 60\%$ of joins post intro | Weekly | Onboarding bot friction; confusing role selection; lack of immediate moderator welcome. |
| **MOFU (Mid Funnel)** | Educate prospects on work facilities and alpine lifestyle. | **Time on Page: `zucity.org/en/all`** | $\ge 2\text{m } 45\text{s}$ average session | Monthly | Listing photography lacks detail; missing workstation specs or clear neighborhood map. |
| **BOFU (Bottom Funnel)** | Drive completed residency applications. | **Residency Form Completion Rate** | $\ge 25\%$ (Start to Submit) | Weekly during window | Application questionnaire too long (>12 questions); unclear pricing or date expectations. |
| **BOFU (Bottom Funnel)** | Capture instant stay bookings. | **Stay Booking Conversion Rate** | $\ge 2.8\%$ of listing views | Monthly | Friction in payment checkout; calendar date unavailability; lack of currency options. |
| **Retention & Expansion** | Ensure transformative resident satisfaction. | **Resident Net Promoter Score (NPS)** | $\ge +70$ NPS | Post-Cohort | Cold indoor temperatures; slow Wi-Fi in specific rooms; insufficient quiet hours enforcement. |
| **Retention & Expansion** | Convert alumni into recurring network residents. | **Alumni Repeat Booking / Referral Rate**| $\ge 30\%$ within 12 months | Quarterly | Weak post-stay alumni communication; lack of exclusive alumni booking privileges. |

---

## 3. Multi-Touch Attribution Modeling SOP

Understanding which marketing touchpoints genuinely drive high-value conversions (rather than crediting the final checkout link) is essential for capital and time allocation.

We utilize a **Hybrid Attribution Model** across our digital surfaces:

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                   HYBRID ATTRIBUTION FRAMEWORK                                   │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                  │
│   [FIRST TOUCH: 40% Weight] ──► [MID-FUNNEL NURTURE: 20% Weight] ──► [LAST TOUCH: 40% Weight]    │
│   • Identifies the discovery     • Identifies the trust-building      • Identifies the closing   │
│     source (X Thread, Reel,        catalyst (Discord Town Hall,         urgency trigger          │
│     Substack Essay)                Substack Newsletter, Friend DM)      (Calendar Link, Email #4)│
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### 3.1 Attribution Data Capture Protocol
1. **UTM Persistence**: PostHog automatically persists UTM parameters (`utm_source`, `utm_medium`, `utm_campaign`, `utm_content`) across subdomains (`japanglobal.org` → `zucity.org`).
2. **Qualitative Self-Report Verification**: Every residency application questionnaire includes a mandatory single-choice field:
   - *"How did you first discover ZuCity / Japan Global?"* (Options: X/Twitter Thread, Instagram Reel, Substack Essay, Friend/Alumni Referral, Discord Town Hall, Press Article).
3. **Attribution Reconciliation**: In weekly reviews, if quantitative last-click data conflicts with qualitative self-report data, qualitative founder/alumni referral data is given primary weighting.

---

## 4. The 3-Tier Learning Feedback Loop SOP

Data without systematic action is useless. The Marketing Lead operates three structured learning loops to continuously optimize performance:

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                    THE 3 LEARNING LOOPS                                          │
│                                                                                                  │
│   1. WEEKLY EDITORIAL SPRINT REVIEW (Every Monday 09:30 JST)                                     │
│   • Analyze top 20% and bottom 20% content assets; adjust weekly publishing weights              │
│                                      ▼                                                           │
│   2. MONTHLY CAMPAIGN RETROSPECTIVE (First Friday of the Month)                                  │
│   • Audit full-funnel conversion rates, CAC, GMV, and property unit economics                    │
│                                      ▼                                                           │
│   3. POST-COHORT RESIDENT DEBRIEF (Within 7 Days of Cohort Departure)                           │
│   • Review NPS qualitative feedback; update physical amenities and onboarding guides             │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### 4.1 Loop 1: Weekly Editorial Performance Loop
- **Trigger**: Every Monday at 09:30 JST.
- **Process**:
  1. Pull top 3 highest-converting and bottom 3 lowest-performing posts from the preceding 7 days.
  2. Identify the winning narrative variable: Was it the headline hook? The visual aesthetic? The technical specificity?
  3. Update the `copy_swipe_files/social_hook_and_post_templates.md` catalog with verified high-performing patterns.
  4. Deprecate angles or formats that generated high vanity impressions but zero click-throughs to `zucity.org`.

### 4.2 Loop 2: Monthly Campaign & Funnel Optimization Loop
- **Trigger**: First Friday of every month.
- **Process**:
  1. Calculate month-over-month changes in BOFU metrics: Total GMV, average stay length, application volume, and cost-per-application.
  2. Identify funnel drop-off points (e.g., if 500 users viewed `/en/all` but only 12 started checkout, diagnose pricing or UX friction).
  3. Deploy A/B test variations for hero headlines, room package inclusions, and CTA button copy.

### 4.3 Loop 3: Post-Cohort Resident Experience Loop
- **Trigger**: Within 7 days of cohort completion.
- **Process**:
  1. Compile all quantitative scores from the Post-Stay Survey (Wi-Fi rating, bed comfort, kitchen utility, onsen access, community vibe).
  2. Extract all verbatim negative or constructive comments.
  3. If any physical friction is reported (e.g., "Wi-Fi in Room 201 dropped during heavy rain" or "Kitchen lacked sharp knives"), dispatch immediate work orders to local property ops before the next cohort arrives.

---

## 5. Qualitative Feedback Harvesting Framework

Quantitative numbers tell you *what* happened; qualitative feedback tells you *why*. We harvest qualitative feedback through three structured channels:

1. **The Post-Stay 5-Question Resident Survey**:
   - *Q1*: On a scale of 0–10, how likely are you to recommend ZuCity to a fellow builder?
   - *Q2*: What was the single most productive or meaningful moment of your stay?
   - *Q3*: What was the biggest friction point or inconvenience you experienced?
   - *Q4*: How did the 1 Gbps fiber and workstation setup compare to your expectations?
   - *Q5*: What project or code did you ship during your residency? (With GitHub link).
2. **The Bi-Weekly Local Komoro Merchant Check-In**:
   - The Local Bridge Lead meets briefly with partner soba restaurants, Nakadana onsen staff, and grocery managers to ensure residents are being respectful neighbors (*Wa*).
3. **Discord `#feedback-and-ideas` Channel**:
   - An open community channel where members suggest features for the website, propose new Working Group bounties, or suggest future cohort themes.

---
*End of Full-Funnel KPI Hierarchy, Attribution Models & Learning Feedback Loops.*
