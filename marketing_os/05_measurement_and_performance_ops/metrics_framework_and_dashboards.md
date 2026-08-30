# Metrics Framework & Executive Dashboards: Hard Outcomes vs. Vanity Metrics

## Document Metadata & Epistemic Status
- **Author**: Japan Global Network (JGN) Performance Operations & Analytics Team
- **Document Type**: Comprehensive Metrics Framework, Dashboard Specifications & KPI Taxonomy
- **Target Surfaces**: Executive Leadership, Japan Global Council (JGC), Marketing Lead Operations
- **Epistemic Classification**:
  - Operational Metrics & Analytics Stack: `[Confirmed Fact]`
  - Live Conversion Thresholds: `[Web-Verified]`
  - Long-Term On-Chain Protocol Metrics: `[Inference]`
- **Core Philosophy**: Reject superficial vanity metrics; anchor all performance evaluation in verifiable physical operations, community retention, and economic throughput.

---

## 1. Executive Summary & The 3-Tier Metrics Hierarchy

Marketing at Japan Global Network is not judged by viral impressions, superficial social media likes, or algorithmic noise. In alignment with *The Network State* paradigm and authentic rural Japanese revitalisation, every marketing dollar and editorial hour must compound real-world, physical outcomes.

We structure our analytics around a strict **3-Tier Metrics Hierarchy**:

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                   THE 3-TIER METRICS HIERARCHY                                   │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                  │
│   TIER 1: HARD BUSINESS & COMMUNITY OUTCOMES (Primary Executive Health - 70% Weight)            │
│   • Paid Bed-Nights Booked • Residency Applications Submitted • Gross Lodging Revenue (GMV)      │
│   • Local Economic Spend in Nagano • Signed Akiya Leases • Municipal MOUs Signed • Resident NPS  │
│                                      ▼                                                           │
│   TIER 2: PROXY & COMMUNITY ENGAGEMENT METRICS (Operational Signal - 20% Weight)                │
│   • Verified Discord Onboarding Rate • Town Hall Attendance • Open Bounty Submissions            │
│   • Bookmark/Save Rates • Email Nurture Sequence Open/Click-Through Rates                        │
│                                      ▼                                                           │
│   TIER 3: VANITY & REACH METRICS (Diagnostic & Contextual Only - 10% Weight)                     │
│   • Raw Social Impressions • Video Views • Likes / Retweets • Aggregate Follower Counts          │
│                                                                                                  │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## 2. Hard Business Outcomes vs. Vanity Metrics Matrix

The table below establishes the explicit boundaries between actionable business indicators and superficial vanity noise:

| Metric Category | Specific Indicator | Measurement Tool / Source | Benchmark Target | Warning Threshold | Critical Alert Level | Operational Action if Below Target |
|---|---|---|---|---|---|---|
| **Tier 1 (Hard Outcome)** | **Residency Application Oversubscription** | `zucity.org/en/calendar` + Typeform / Airtable | **$\ge 3.0\times$ capacity** | $1.5\times – 2.5\times$ capacity | $< 1.5\times$ capacity | Deploy targeted partner newsletter sponsorships; host emergency Discord Stage AMA. |
| **Tier 1 (Hard Outcome)** | **Bed-Nights Booked & Occupancy Rate** | Property Management System (PMS) / Stripe | **$\ge 75\%$ (Cohorts)**<br>**$\ge 55\%$ (Year-Round)** | $40\% – 54\%$ | $< 40\%$ | Trigger seasonal pricing discounts on `zucity.org/en/all`; launch seasonal paid social push. |
| **Tier 1 (Hard Outcome)** | **Gross Merchandise Value (GMV)** | Stripe Gateway + Crypto Settlement Rails | **$\ge \$45,000 / month$** | $\$25,000 – \$44,999$ | $< \$25,000$ | Audit checkout funnel friction; expand B2B corporate team offsite outbound outreach. |
| **Tier 1 (Hard Outcome)** | **Direct Local Economic Spend in Nagano** | Resident Spend Logs + Local Partner POS | **$\ge ¥150,000 / resident / mo$** | $¥100,000 – ¥149,999$ | $< ¥100,000$ | Expand curated dining partnerships and artisan workshops in the resident welcome guide. |
| **Tier 1 (Hard Outcome)** | **Signed Akiya Leases & Node Additions** | JGN Real Estate Legal Register | **$\ge 2$ New Nodes / Year** | 1 Node / Year | 0 Nodes / Year | Accelerate local Komoro town hall briefings; engage municipal vacant home bank (*Akiya Bank*). |
| **Tier 1 (Hard Outcome)** | **Municipal Partnership Agreements (MOUs)** | JGC Secretariat Legal Registry | **$\ge 1$ Formal MOU / Year** | Active Discussions | Stalled Talks | Schedule formal Keigo briefing with Nagano Prefectural / Komoro City revitalization desk. |
| **Tier 1 (Hard Outcome)** | **Resident Net Promoter Score (NPS)** | Post-Stay Survey (Email Sequence #5) | **$\ge +70$ NPS** | $+50 – +69$ NPS | $< +50$ NPS | Immediate review of physical property, Wi-Fi stability, food quality, and quiet hour compliance. |
| **Tier 2 (Proxy Signal)** | **Verified Discord Onboarding Rate** | Discord Community Insights + Bot Logs | **$\ge 60\%$ of Joins Intro** | $40\% – 59\%$ | $< 40\%$ | Redesign automated welcome bot sequence; simplify `#introductions` prompt. |
| **Tier 2 (Proxy Signal)** | **Town Hall Attendance & Retention** | Discord Stage Analytics / Luma | **$\ge 75$ Live Attendees** | $40 – 74$ Attendees | $< 40$ Attendees | Upgrade featured technical guest quality; optimize broadcast time for US/EU/Asia overlap. |
| **Tier 3 (Vanity Context)** | **Social Impressions & Video Views** | X Analytics, Instagram Insights | **$\ge 250,000 / month$** | $100,000 – 249,999$ | $< 100,000$ | Test new headline formulas; increase Reel publishing frequency from 2x to 4x weekly. |

---

## 3. The Performance Analytics Stack & Data Instrumentation

To maintain real-time visibility across all physical and digital nodes without data silos, the marketing operations team maintains the following integrated analytics architecture:

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                PERFORMANCE ANALYTICS ARCHITECTURE                                │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                  │
│   SURFACE LAYER                  TRACKING & EVENT ENGINE               REPORTING & DASHBOARDS    │
│   • zucity.org/en/all        ──► PostHog Event Tracking            ──► Executive Metabase & KPI  │
│   • zucity.org/en/calendar   ──► (Checkout clicks, stay searches)      Weekly Scorecard          │
│   • japanglobal.org/network                                                                      │
│                                                                                                  │
│   PAYMENT & COMMERCE             FINANCIAL SETTLEMENT ENGINE                                     │
│   • Stripe Billing           ──► Stripe Sigma & DePay Webhooks     ──► GMV & Monthly Cashflow    │
│   • USDC/Crypto Rails                                                  Reconciliation Sheet      │
│                                                                                                  │
│   COMMUNITY PLATFORM             COMMUNITY TELEMETRY                                             │
│   • JGN Discord Server       ──► Statbot & Custom JGN Bot Logs     ──► Contributor Retention &   │
│   • Luma Calendar Events                                               Guild Health Tracker      │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### 3.1 Instrumentation & Event Tracking Standards
- **Event: `view_listing`**: Fires when a user loads an accommodation details page on `https://zucity.org/en/all`.
- **Event: `start_booking_checkout`**: Fires when a user selects dates and enters the reservation flow.
- **Event: `complete_booking_payment`**: Server-side webhook firing upon successful Stripe/crypto charge.
- **Event: `submit_residency_application`**: Fires upon complete form submission on `https://zucity.org/en/calendar`.
- **Event: `discord_member_verified`**: Fires when a new user passes Captcha and claims the `@Verified Citizen` role.

---

## 4. Executive Dashboard Architecture (Metabase / Looker Spec)

The Marketing Lead maintains a live executive dashboard accessible by the Japan Global Council (JGC), structured into 4 real-time views:

### Dashboard View 1: The Revenue & Lodging Command Center
- **Key Widgets**:
  - Live 30-Day Trailing Gross Lodging Revenue (GMV in USD & JPY).
  - Current Month Node Occupancy Rate (% by property: Node 01, Node 02).
  - 90-Day Forward Booking Pipeline & Reserved Bed-Nights.
  - Average Daily Rate (ADR) and Revenue Per Available Room (RevPAR).

### Dashboard View 2: Residency & Cohort Admissions Pipeline
- **Key Widgets**:
  - Application Volume vs. Cohort Target (Oversubscription Gauge).
  - Stage Funnel: Visitor → Application Started → Submitted → Screened → Accepted → Deposit Paid.
  - Applicant Demographics (Country of origin, primary technical domain: AI, Web3, Architecture).

### Dashboard View 3: Community & Contributor Telemetry
- **Key Widgets**:
  - Net New Verified Discord Citizens (7-day and 30-day trailing).
  - Active Contributor Retention (% of members active 30+ days after joining).
  - Working Group Bounty Velocity (Bounties opened vs. completed).
  - Weekly Town Hall Live Attendance & Average Listen Duration.

### Dashboard View 4: Regional Revitalization & Civic Impact
- **Key Widgets**:
  - Estimated Total Resident Local Spending in Komoro/Nagano (Monthly & Cumulative).
  - Restored Square Meters of Heritage *Akiya* Real Estate.
  - Active Property Partner Inquiries & Municipal Meeting Tracker.

---

## 5. Reporting Cadence & Escalation Protocol

1. **Weekly Marketing Flash Report (Every Monday at 09:00 JST)**:
   - 1-page markdown scorecard posted in Discord `#council-briefings` highlighting weekly GMV, residency application velocity, top-performing content assets, and immediate pipeline bottlenecks.
2. **Monthly Comprehensive JGC Board Memo (First Friday of the Month)**:
   - Deep-dive analytical report reviewing unit economics, customer acquisition cost (CAC), resident NPS, and multi-node property pipeline.
3. **Emergency KPI Alert Thresholds**:
   - If residency applications fall below $1.5\times$ target with 7 days remaining in the window, or if physical occupancy drops below $40\%$, the Marketing Lead triggers an immediate **Sprint Redirection Protocol** to reallocate budget and content focus to conversion hooks.

---
*End of Metrics Framework & Executive Dashboards.*
