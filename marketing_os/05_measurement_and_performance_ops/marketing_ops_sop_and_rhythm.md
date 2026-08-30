# Marketing Operations SOP, Operating Rhythms & Incident Escalation

## Document Metadata & Epistemic Status
- **Author**: Japan Global Network (JGN) Marketing Operations & Governance Team
- **Document Type**: Operational Cadence SOP, Team Rituals & Crisis Incident Protocol
- **Target Audience**: Marketing Lead, Content Creators, Community Moderators, JGC Council
- **Epistemic Classification**:
  - Operating Cadence & Meeting SOPs: `[Confirmed Fact]`
  - Incident Escalation Thresholds: `[Confirmed Fact]`
  - Long-Term Decentralized Working Group Scaling: `[Inference]`
- **Core Mission**: Establish a dependable, high-velocity operational heartbeat that maintains brand excellence, prevents burnout, and handles crises swiftly.

---

## 1. Executive Summary & Weekly Operating Rhythm

The Japan Global Network marketing engine operates on a synchronized weekly rhythm designed to maintain a consistent publishing cadence, enforce the 5-point gatekeeper review rubric, and rapidly iterate based on hard conversion data.

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                   THE WEEKLY MARKETING RHYTHM                                    │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                  │
│   MONDAY: STRATEGY & SCHEDULING (09:00–10:30 JST)                                                │
│   • Review weekend conversion data, audit weekly content queue, assign working group assets       │
│                                      ▼                                                           │
│   TUESDAY: PRODUCTION & ASSET HARVESTING (Async)                                                 │
│   • Capture photo/video from Komoro nodes, record builder interviews, draft copy swipe assets   │
│                                      ▼                                                           │
│   WEDNESDAY: MID-WEEK PIPELINE & GATEKEEPER REVIEW (14:00–14:45 JST)                             │
│   • Run 5-Point Binary Review on all scheduled assets; verify live URL endpoints                 │
│                                      ▼                                                           │
│   THURSDAY: COMMUNITY BROADCAST & TOWN HALL (22:00 JST / 13:00 UTC)                              │
│   • Host live Discord Stage Town Hall AMA; amplify builder showcases; distribute recaps         │
│                                      ▼                                                           │
│   FRIDAY: RETROSPECTIVE, RECONCILIATION & WEEKEND LOCK (16:00–17:00 JST)                        │
│   • Compile weekly GMV and booking scorecard; lock automated weekend publishing queue           │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## 2. Detailed Meeting SOPs & Agendas

### 2.1 Monday Editorial & Campaign Sync (09:00–10:30 JST)
- **Objective**: Align on the week’s primary conversion objectives and lock the editorial calendar.
- **Attendees**: Marketing Lead, Copywriter, Social Media Manager, Community Lead, Local Bridge Lead.
- **Agenda**:
  1. **00:00–00:15 (Flash Metrics Review)**: Inspect trailing 7-day bookings on `zucity.org/en/all`, residency applications on `/calendar`, and Discord member intro rates.
  2. **00:15–00:45 (Pillar Allocation & Assignment)**: Review the Master Editorial Calendar; assign the 10 pillars across X, Instagram, Substack, and Discord.
  3. **00:45–01:15 (Campaign Focus Sprints)**: Check status on active campaign windows (e.g., Residency Phase 2 Application launch or Winter Stays Drop).
  4. **01:15–01:30 (Blockers & Asset Requests)**: Identify missing photography, translation needs, or physical node data from Komoro.

---

### 2.2 Wednesday Mid-Week Gatekeeper Review (14:00–14:45 JST)
- **Objective**: Execute the **5-Point Binary Gatekeeper Review** on all drafts scheduled for Thursday through Sunday.
- **Attendees**: Marketing Lead, Strategic Communications Reviewer.
- **Agenda**:
  1. Audit 100% of upcoming X threads, Instagram Reels, and Substack newsletters against the 5 checks (Epistemic Truth, Entity Routing, Voice/Lexicon Quarantine, Live Surface URL, Actionable CTA).
  2. Test all outbound links to ensure zero 404 errors and correct UTM parameter strings.
  3. Sign off on the Pre-Publication Scorecards.

---

### 2.3 Friday Retrospective & Weekend Queue Lock (16:00–17:00 JST)
- **Objective**: Synthesize weekly learnings, reconcile metrics, and ensure zero unmonitored weekend posting.
- **Attendees**: Marketing Lead, Community Moderator on duty.
- **Agenda**:
  1. **Outcome Scorecard Reconciliation**: Compare weekly actuals against benchmark targets (GMV, applications, NPS).
  2. **Learning Loop Capture**: Record top-performing headline hooks in `social_hook_and_post_templates.md`.
  3. **Weekend Moderation Handover**: Confirm on-call schedule for Discord moderation and guest inquiries.

---

## 3. Monthly Stakeholder Reporting Template (JGC Council Memo)

On the first Monday of every month, the Marketing Lead submits the **Monthly Marketing Performance Memo** to the Japan Global Council (JGC):

```markdown
# JAPAN GLOBAL NETWORK — MONTHLY MARKETING OS REPORT
**Month / Year**: [e.g., October 2026]  
**Author**: Marketing Lead  
**Epistemic Classification**: [Confirmed Fact] (Financials & Metrics)  

---

### 1. Executive Summary & Hard Business Outcomes
- **Total Gross Lodging Revenue (GMV)**: ¥[Total GMV] ($[USD Equivalent]) — [▲/▼ X% vs Target]
- **ZuCity Average Occupancy Rate**: [X]% across [N] active physical nodes in Komoro.
- **Residency Applications Received**: [N] submissions ([X]× oversubscription rate).
- **Direct Local Economic Spend Generated in Nagano**: ¥[Estimated Local Spend].
- **Net Resident NPS**: +[Score] (Based on [N] survey responses).

---

### 2. Community & Digital Reach Highlights
- **Net New Verified Discord Citizens**: +[Count] ([X]% introduction completion rate).
- **Substack Paid & Free Subscriber Base**: [Total Subs] (+[Net Growth] this month).
- **Top Converting Asset**: [Post Link / Title] — Generated [N] direct application clicks.

---

### 3. Campaign Playbook Status
- **Residency Cohort Status**: [Active Phase / Next Cohort Dates / Room Fill %].
- **Accommodations Catalog (`zucity.org/en/all`)**: [New Listings Added / Seasonal Package Performance].
- **Working Group Progress**: [Bounties Completed / Active Open-Source PRs].

---

### 4. Strategic Bottlenecks & Resource Allocations
- **Key Challenge Identified**: [e.g., Winter weekday occupancy dip].
- **Corrective Action & Test**: [e.g., Deploying Karuizawa ski shuttle package].
- **Budget Allocation Request**: [Any budget adjustments for paid distribution or creative assets].
```

---

## 4. Incident Escalation & Crisis Communications SOP

In the event of an operational failure, local cultural misunderstanding, or technical outage, the team follows this 4-tier escalation protocol:

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                 CRISIS ESCALATION MATRIX                                         │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                  │
│   TIER 1 (P3): BROKEN LINK OR MINOR TYPO                                                         │
│   • Response Time: < 30 Mins • Owner: Content Operator • Action: Hotfix URL or update copy       │
│                                      ▼                                                           │
│   TIER 2 (P2): TECHNICAL OUTAGE (Booking Engine or Application Form Down)                        │
│   • Response Time: < 15 Mins • Owner: Tech Lead + Marketing Lead                                 │
│   • Action: Activate Cloudflare fallback; post temporary Discord intake desk                     │
│                                      ▼                                                           │
│   TIER 3 (P1): LOCAL CULTURAL / NEIGHBORHOOD COMPLAINT (Noise, Parking, Etiquette)                │
│   • Response Time: < 30 Mins (In-Person) • Owner: Local Bridge Lead + Community Manager          │
│   • Action: Immediate in-person visit with fruit/tea apology gift; address resident behavior     │
│                                      ▼                                                           │
│   TIER 4 (P0): SEVERE BRAND CRISIS / PRESS MISINFORMATION / LEGAL INQUIRY                         │
│   • Response Time: < 15 Mins • Owner: Japan Global Council (JGC) + Strategic Comm Lead           │
│   • Action: Full public communications freeze; emergency JGC convening; verified statement draft│
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### 4.1 Step-by-Step Response Protocol for Tier 3 (Local Neighbor Concerns)
1. **Immediate On-Site Acknowledgment**: The Local Bridge Lead visits the neighbor in person within 30 minutes, bowing respectfully, listening without defensiveness, and offering formal apologies (*Kenson* / 謙遜).
2. **Internal Resolution**: The resident responsible is privately notified; living covenants are re-reviewed.
3. **Closing the Loop**: A formal follow-up visit is conducted 24 hours later to confirm that the issue (e.g., noise after 22:00 or improper trash sorting) has been completely resolved.
4. **Log Incident**: Log the event in `#ops-incidents` for weekly review.

### 4.2 Step-by-Step Response Protocol for Tier 4 (Severe Brand Crisis)
1. **Immediate Communications Freeze**: Halt all automated social queues and scheduled newsletters across `@JapanGlobalNet`, `@ZuCityJapan`, and Substack.
2. **Emergency JGC War Room**: Convene Council within 60 minutes on private voice channel.
3. **Fact-Checking & Epistemic Audit**: Establish the ground truth using our 4-tier epistemic taxonomy.
4. **Unified Statement Release**: Publish a single, measured, factual statement authored in both English and flawless formal Japanese (*Keigo*). No individual team members may comment independently.

---
*End of Marketing Operations SOP, Operating Rhythms & Incident Escalation.*
