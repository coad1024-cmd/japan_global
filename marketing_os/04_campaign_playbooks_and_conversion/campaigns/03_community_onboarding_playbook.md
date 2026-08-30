# Community Onboarding & Activation Playbook: Japan Global Discord

## Document Metadata & Epistemic Status
- **Author**: Japan Global Network (JGN) Community Architecture Team
- **Document Type**: Multi-Tier Community Funnel & Member Activation SOP
- **Target Surface**: Japan Global Network Discord Community (`/join-discord`), Working Groups & Town Halls
- **Epistemic Classification**:
  - Community Structure & Tiers: `[Confirmed Fact]`
  - Operational Channels & Live Verification: `[Web-Verified]`
  - Governance Evolution to JPG Staking: `[Inference]`
- **Primary Conversion Endpoint**: Official JGN Discord Invite Link (`/join-discord`)

---

## 1. Executive Summary & Community Architecture

The **Japan Global Community Funnel** is the social engine that transforms passive social media followers and casual curious observers into verified, active contributors, resident builders, and long-term network citizens.

In accordance with Balaji Srinivasan's *The Network State* paradigm, a physical network node (ZuCity) and future city (Chokyo) cannot succeed without an organized, high-trust digital union preceding it. The Discord server serves as our digital agora—the cloud-first layer of our network archipelago.

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                 THE 5-TIER COMMUNITY FUNNEL                                      │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                  │
│   TIER 0: SOCIAL AUDIENCE & CURIOUS OBSERVERS (X, Instagram, Substack)                          │
│   • Discovery via high-density content, reels, and essays                                        │
│                                      ▼                                                           │
│   TIER 1: VERIFIED DISCORD MEMBERS (Rules Accepted & Self-Selected Roles)                       │
│   • Entry via /join-discord, bot verification, role tagging (Builder, Nomad, Local, Partner)    │
│                                      ▼                                                           │
│   TIER 2: ACTIVE CONTRIBUTORS & WORKING GROUPS (AI/Agents, Architecture, Local Bridge)          │
│   • Participation in weekly AMAs, bounties, open-source commits, and discussion channels         │
│                                      ▼                                                           │
│   TIER 3: VERIFIED RESIDENTS & COHORT ALUMNI (Physical Proof-of-Presence)                       │
│   • Completed a ZuCity residency or 7+ day stay; holding on-chain/role residency badge          │
│                                      ▼                                                           │
│   TIER 4: FOUNDING STEWARDS & JGC COUNCIL CONTRIBUTORS (Governance & Node Co-Stewards)          │
│   • Deep operational commitment, node funding, municipal liaisons, strategic steering           │
│                                                                                                  │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## 2. Multi-Tier Gating & Role Permissions Architecture

To preserve signal over noise and protect community members from spam, the server implements strict role gating:

| Tier | Role Title | Access Threshold / Requirement | Channel Visibility & Permissions | Key Activation Milestone |
|---|---|---|---|---|
| **Tier 0** | **Public Observer** | Following X/IG or reading Substack. | External surfaces only. | Clicks `/join-discord` CTA link. |
| **Tier 1** | **@Verified Citizen** | Completes Captcha verification + Agrees to community rules + Selects interests. | `#welcome`, `#announcements`, `#general-chat`, `#introductions`, `#show-your-work`. | Posts introduction in `#introductions` within 48h. |
| **Tier 2** | **@Active Contributor** | Participated in 2+ Town Halls OR submitted a verified GitHub PR / project demo. | Unlocks Working Group channels: `#wg-ai-agents`, `#wg-architecture`, `#wg-local-bridge`. | Claims an open bounty or joins a working group call. |
| **Tier 3** | **@ZuCity Alumni** | Verified booking / completion of a ZuCity residency or stay in Komoro. | Unlocks `#alumni-lounge`, `#insider-stays-early-bird`, `#regional-alpha`. | Books repeat stay or refers 2+ qualified applicants. |
| **Tier 4** | **@Council Steward** | Formal appointment by Japan Global Council (JGC) or node steward equity. | Unlocks private `#jgc-governance`, `#node-economics`, `#municipal-strategy`. | Co-hosts a residency cohort or leads a major civic initiative. |

---

## 3. Automated Welcome Sequence & First 7-Day Journey

When a new member enters the Discord server, the automated onboarding bot executes the following 4-step sequence:

```
[STEP 1: ENTRY] ──────► [STEP 2: CAPTCHA] ───► [STEP 3: ROLE SELECT] ──► [STEP 4: INTRO PROMPT]
Member joins via         Completes zero-spam    Selects persona roles    Bot pings #introductions
custom invite link       security check         (Builder / Nomad / etc.) with structured template
```

### 3.1 Structured Introduction Template (`#introductions`)
New members receive a direct ephemeral prompt asking them to share:
```markdown
👋 **Welcome to Japan Global Network! Introduce yourself to the community:**
1. **Name & Current Location**: [e.g., Kenji | Tokyo & San Francisco]
2. **What You Build / Superpower**: [e.g., Autonomous Agent Tooling / Woodworking / Full-stack Rust]
3. **What Drew You to ZuCity & Japan Global**: [e.g., Long-time Japanophile looking for deep-work retreats]
4. **Favorite Place or Craft in Japan**: [e.g., Nagano Soba / Nakadana Onsen / Kyoto joinery]
```

### 3.2 Automated Community Activation Milestones (Day 1 to Day 7)
- **Day 1**: Welcome ping in `#welcome` + Community Lead / Mod reacts with personalized emoji and greeting.
- **Day 3**: Automated DM reminder inviting the member to attend the upcoming **Weekly Town Hall AMA** on Discord Stage.
- **Day 5**: Automated highlight ping featuring the top 3 community showcase projects from `#show-your-work`.
- **Day 7**: Call-to-Action to explore live residency cohorts on `https://zucity.org/en/calendar` or book a stay on `https://zucity.org/en/all`.

---

## 4. Community Activation Rituals & Operating Cadence

High-retention communities rely on recurring, predictable rituals that foster intellectual density, mutual accountability, and genuine friendship:

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                WEEKLY COMMUNITY RITUAL SCHEDULE                                  │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│  • TUESDAYS (12:00 UTC / 21:00 JST): #Show-Your-Work Lightning Demos                            │
│  • THURSDAYS (13:00 UTC / 22:00 JST): JGN Global Town Hall & Thematic AMA (Stage Channel)        │
│  • FRIDAYS (09:00 UTC / 18:00 JST): Weekly Asama Fireside (Casual Voice Hangout & Music)        │
│  • MONTHLY (1st Saturday): Live Streamed Demo Day from ZuCity Komoro Campus                     │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### 4.1 The Thursday Global Town Hall SOP
1. **Duration**: 45 Minutes strictly timed.
2. **Format**:
   - 00–10m: Ecosystem Progress & Physical Node Updates (Akiya renovations, residency dates).
   - 10–30m: Guest Speaker or Resident Builder Spotlight (Deep-dive technical or cultural presentation).
   - 30–45m: Open Q&A from the community.
3. **Recording & Repurposing**: Town Hall audio is recorded, edited into a 5-minute highlight reel, and distributed across X and Substack.

---

## 5. Working Groups & Bounties Architecture

To engage Tier 2 contributors, JGN operates four structured **Working Groups (WGs)**, each led by an appointed Guild Master:

1. **WG-01: AI Agents & Software Systems (`#wg-ai-agents`)**:
   - Focus: Zaibots framework, RiChan tourism concierge tooling, Model Context Protocol (MCP) integrations, smart access IoT.
   - Deliverables: Open-source GitHub contributions, API integrations for local services.
2. **WG-02: Architecture & Physical Spaces (`#wg-architecture`)**:
   - Focus: Akiya structural analysis, sustainable timber renovation, radiant heating optimization, interior workspace design.
   - Deliverables: 3D architectural renders, renovation playbooks, material sourcing guides.
3. **WG-03: Local Bridge & Cultural Heritage (`#wg-local-bridge`)**:
   - Focus: Japanese-English translation, municipal coordination, local artisan interview documentation, Shinshu culinary guides.
   - Deliverables: Bilingual content, local merchant onboarding kits, cultural etiquette guidelines.
4. **WG-04: Decentralized Governance & Economics (`#wg-governance`)**:
   - Focus: JGC charters, network state theory synthesis, coliving unit economics, future JPG protocol specifications.
   - Deliverables: Governance research memos, economic whitepapers.

---

## 6. Community Moderation Rules & Anti-Toxicity Policy

To preserve a welcoming, intellectual, and culturally respectful culture, all members must adhere to the **Japan Global Community Covenant**:

1. **Strict No-Shitposting & Anti-Hype Rule**: Prohibited from pumping speculative tokens, posting generic referral spam, or engaging in low-effort tribal flame wars.
2. **Cultural Reverence**: Zero tolerance for disrespectful, xenophobic, or disparaging commentary regarding Japanese culture, local Nagano residents, or municipal partners.
3. **High-Context Constructive Discourse**: Critique ideas and code rigorously, but treat people with kindness and humility (*Wa* / 調和).
4. **Enforcement Protocol**:
   - *1st Offense*: Private warning by Moderator + message deletion.
   - *2nd Offense*: 24-hour timeout + temporary role revoke.
   - *3rd Offense*: Permanent server ban + blacklisting from ZuCity physical residencies.

---
*End of Community Onboarding Playbook.*
