# Platform Operating Rubric: Discord & Community Operations

## Document Metadata & Epistemic Status
- **Author**: Japan Global Network (JGN) Community Architecture Team
- **Document Type**: Community Operations Rubric & Governance SOP
- **Version**: 1.0 (Production Release)
- **Epistemic Classification**:
  - Information Architecture & Channel Taxonomy: `[Confirmed Fact]` (Canonical Operating Standards)
  - Live Community Procedures & Onboarding: `[Web-Verified]` (Active Discord Operations)
  - Async Contributor Bounties & Governance: `[Inference]` (JGC Contributor Framework)
- **Target Surface**: Official JGN Global Discord Server (`discord.gg/japanglobal`)

---

## 1. Role of Discord in the Network State Lifecycle

Discord serves as the **Digital Commons & Virtual Capital** of the Japan Global Network. It is the real-time social coordination layer where online alignment precedes physical arrival in Nagano.

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                   THE DISCORD COMMUNITY ENGINE                                   │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                  │
│   STAGE 1: GLOBAL ONBOARDING  ──► Low-friction arrival, identity verification & role assignment │
│   STAGE 2: COLLABORATIVE COMMONS ──► Async working groups, dev sprints & thesis discussions     │
│   STAGE 3: PHYSICAL PREPARATION ──► Cohort logistics, packing guides, transit coordination       │
│   STAGE 4: LONG-TERM CITIZENSHIP ──► JGC governance, contributor bounties & network compounding │
│                                                                                                  │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## 2. Server Information Architecture & Channel Taxonomy

To ensure clarity, high signal-to-noise ratio, and seamless navigation for both international builders and Japanese community members, channels are organized into 6 functional categories:

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                 SERVER CATEGORY STRUCTURE                                        │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                  │
│  📁 01_START_HERE              📁 02_ECOSYSTEM_NEWS           📁 03_RESIDENCIES_&_STAYS          │
│  • #welcome-and-rules          • #announcements               • #residency-general               │
│  • #introductions              • #ecosystem-updates           • #housing-and-logistics           │
│  • #role-assignment            • #town-hall                   • #nagano-local-guide              │
│                                                                                                  │
│  📁 04_COMMUNITY_COMMONS       📁 05_DEV_&_INNOVATION         📁 06_GOVERNANCE_&_COUNCIL         │
│  • #general-chat               • #zaibots-and-agents          • #jgc-open-council                │
│  • #show-and-tell              • #akiya-architecture          • #bounties-and-grants             │
│  • #thesis-network-state       • #japanese-language-exchange  • #municipal-partnerships          │
│                                                                                                  │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### 2.1 Exhaustive Channel Directory

| Category | Channel Name | Purpose & Access Control | Allowed Post Types |
|---|---|---|---|
| **01 START HERE** | `#welcome-and-rules` | Read-only; foundational covenants, server guidelines, security verification. | System posts & bot verify buttons. |
| | `#introductions` | Member intro template; members introduce background and current projects. | Member text intros only. |
| | `#role-assignment` | Self-assign roles (`Builder`, `Researcher`, `Resident`, `Nagano Local`, `Investor`). | Reaction roles / Dropdowns. |
| **02 NEWS** | `#announcements` | High-priority official broadcasts; residency launches, major milestones. | Read-only (Marketing Lead & Admins). |
| | `#ecosystem-updates` | Weekly build logs, new blog posts, press releases, social highlights. | Read-only automated feed / Ops. |
| | `#town-hall` | Voice & video stage for bi-weekly community calls and guest AMAs. | Stage voice channel + live text chat. |
| **03 RESIDENCIES** | `#residency-general` | General discussion for upcoming and past ZuCity popup cohorts in Komoro. | Open discussion & Q&A. |
| | `#housing-and-logistics` | Shinkansen travel tips, room check-in details, packing, onsen etiquette. | Logistics discussions & FAQs. |
| | `#nagano-local-guide` | Recommendations for Komoro cafes, soba shops, onsens, and mountain trails. | Member guides, photos, reviews. |
| **04 COMMONS** | `#general-chat` | High-trust casual conversation, daily check-ins, watercooler chats. | General community chat. |
| | `#show-and-tell` | Showcase what you shipped this week (code, design, writing, physical craft). | Links, demos, screenshots. |
| | `#thesis-network-state` | Quarantined channel for deep theoretical discussion on TNS, urbanism, civics. | Long-form intellectual debate. |
| **05 DEV & TECH** | `#zaibots-and-agents` | Development discussion on Zaibots, RiChan AI, MCP servers, agentic DeFi. | Tech architecture, PRs, snippets. |
| | `#akiya-architecture` | Architectural restoration logs, timber CAD, smart home IoT, floorplans. | CAD files, photos, renovation logs. |
| | `#japanese-language` | Japanese-English language practice, cultural nuances, Keigo coaching. | Bilingual chat & study prompts. |
| **06 GOVERNANCE** | `#jgc-open-council` | Japan Global Council open session notes, roadmap proposals, working groups. | Contributor discussions. |
| | `#bounties-and-grants` | Paid task bounties for code, translation, design, and content creation. | Official bounty briefs & claims. |

---

## 3. Onboarding Flows & Verification Mechanics

```
[MEMBER JOINS VIA INVITE] ──► [SECURITY CAPTCHA VERIFY] ──► [ROLE SELECTION] ──► [INTRO TEMPLATE POST]
```

### 3.1 Step 1: Security Verification
- New joiners must pass a CAPTCHA gatekeeper bot within 5 minutes to prevent spam bots.
- Read-only access until verified.

### 3.2 Step 2: Role Self-Selection
Members select up to 3 interest tags in `#role-assignment`:
- 🛠️ `Builder / Developer` (Software, AI, Web3, Hardware)
- 🏛️ `Architect / Spatial Designer` (Timber restoration, CAD, Interior design)
- 📖 `Researcher / Writer` (Network State theory, urbanism, journalism)
- 🏔️ `Visiting Resident` (Interested in ZuCity Komoro coliving stays)
- 🇯🇵 `Nagano Local / Japan Resident` (Local stakeholders, Japanese speakers)

### 3.3 Step 3: Standard Introduction Prompt
Pinned prompt in `#introductions`:
```markdown
Welcome to Japan Global Network & ZuCity! 👋

Please take a moment to introduce yourself:
1. **Who are you?** (Name, background, current location)
2. **What are you building or researching?** (Links, domains, passions)
3. **What draws you to ZuCity / Japan?** (Alpine deep work, Akiya restoration, Network State theory)
4. **How can the community help you, and how can you help others?**
```

---

## 4. Official Broadcast & Announcement Formats

All posts in `#announcements` must use standardized Markdown formatting to guarantee readability and brand authority:

### 4.1 Production Announcement Template
```markdown
📢 **[OFFICIAL ANNOUNCEMENT TITLE: CLEAR & CONCISE]**

**Date**: [Date JST]
**Target Group**: `@Everyone` / `@Residency-Cohort` / `@Contributors`

---

### Overview
[2–3 sentences summarizing the major milestone, event launch, or ecosystem update.]

### Key Details & Highlights
- 🏔️ **[Highlight 1]**: [Detail]
- 📅 **[Highlight 2 / Dates]**: [Detail]
- 🛠️ **[Highlight 3 / Logistics]**: [Detail]

### Action Required / Next Steps
👉 **[Action Name]**: [Direct link to live surface]
🔗 **Live URL**: https://zucity.org/en/calendar

---
*For questions or discussions regarding this update, please head to #residency-general.*
```

---

## 5. Town Hall & Community Call Hosting Guidelines

Bi-weekly Town Halls are held on Discord Stage to synchronize global members with physical operations in Nagano.

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                 TOWN HALL AGENDA (60 MINUTES)                                    │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│  00:00 – 00:05 (Welcome & Icebreaker)  ──► Welcome new joiners, sound check, community vibes.    │
│  00:05 – 00:20 (Ecosystem State of the Node) ──► Marketing Lead / Founder progress briefing.    │
│  00:20 – 00:40 (Resident & Builder Showcase) ──► 2 live 10-minute lightning demos from Komoro.   │
│  00:40 – 00:55 (Open Q&A & Discussion) ──► Moderated voice questions from the community.        │
│  00:55 – 01:00 (Next Steps & Synthesis) ──► Wrap-up, action items, and photo snapshot.          │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### 5.1 Speaker & Stage Etiquette
- **Microphone Discipline**: Mute when not speaking; use Push-to-Talk or Krisp noise cancellation.
- **Stage Moderation**: The Community Lead moderates stage hands; unmuting one guest speaker at a time.
- **Post-Call Protocol**: Record call audio, generate automated transcript, and post a 5-bullet synthesis to `#ecosystem-updates` within 4 hours.

---

## 6. Working Group Coordination & Contributor Bounties

Contributors collaborating on open initiatives (Zaibots tools, translation, architectural CAD, marketing) coordinate via standardized weekly check-ins:

### 6.1 Weekly Contributor Sprint Template (in `#jgc-open-council`)
```markdown
### 🛠️ Working Group Weekly Sprint: [Group Name: e.g., Translation & Localization]
**Sprint Period**: [Date] → [Date]
**Lead Coordinator**: [@Handle]

**1. Accomplished Last Sprint**:
- [x] Translated ZuCity visitor onboarding guide into Japanese (*Keigo* verified).
- [x] Updated `#nagano-local-guide` with 10 new Komoro restaurant entries.

**2. Objectives This Sprint**:
- [ ] Draft Japanese municipal briefing deck for Komoro City Council.
- [ ] Review Japanese subtitle timing on upcoming Instagram Reels.

**3. Blockers & Help Needed**:
- Need native review on historical terminology regarding Meiji silk mills.
```

---

## 7. Moderation Standards, Cultural Norms & Anti-Spam Guardrails

To protect community cohesion and high-trust civility, moderation is strictly enforced:

### 7.1 Community Covenants (The High-Trust Law)
1. **Constructive Civility**: Respectful, intellectually rigorous discourse. Personal attacks, harassment, or online status games result in immediate removal.
2. **Quarantine Discipline**: Keep technical Web3 / crypto-economic token speculation strictly inside `#thesis-network-state` and `#dev-and-zaibots`. Never spam general chat with financial speculation.
3. **Cultural Reverence**: Treat Japanese traditions, local Nagano residents, and municipal partners with the highest respect.
4. **No Cold DMs or Unsolicited Sales**: Unsolicited direct messaging to sell services, promote unrelated tokens, or pitch agencies results in an instant permanent ban.

### 7.2 Violation Escalation Ladder
- **Level 1 (First Warning)**: Friendly public or DM reminder citing server guidelines.
- **Level 2 (Temporary Mute)**: 24-hour timeout for repetitive noise, off-topic spam, or aggressive tone.
- **Level 3 (Permanent Ban)**: Immediate expulsion for scams, hate speech, harassment, or unauthorized privacy leaks.
