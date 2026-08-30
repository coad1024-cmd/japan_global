# Email Nurture Sequences: Residency Applicant & Resident Onboarding

## Document Metadata & Epistemic Status
- **Author**: Japan Global Network (JGN) Lifecycle Marketing & Resident Experience Team
- **Document Type**: Automated 5-Email Onboarding & Nurture Sequence
- **Target Audience**: Confirmed Applicants and Accepted Residents for ZuCity Curated Cohorts
- **Epistemic Classification**:
  - Sequence Architecture & Logistics: `[Confirmed Fact]`
  - Physical Infrastructure & Transit: `[Web-Verified]` (`https://zucity.org/en/calendar`)
  - Long-Term Governance Attestations: `[Inference]`
- **Trigger Events**: Application Submission (Email 1) → Acceptance & Deposit Confirmation (Emails 2–4) → Residency Checkout (Email 5)

---

## 1. Automated Lifecycle Workflow & Timing Sequence

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                 THE 5-STAGE EMAIL ONBOARDING ENGINE                              │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                  │
│   EMAIL 1: APPLICATION CONFIRMATION (Sent Immediately upon Form Submission)                     │
│   • Sets expectations, explains the 72-hour review process, shares community links               │
│                                      ▼                                                           │
│   EMAIL 2: THEMATIC THESIS & CURATORIAL VISION (Sent Upon Acceptance & Deposit)                 │
│   • The intellectual why, reading list on The Network State & alpine deep work                   │
│                                      ▼                                                           │
│   EMAIL 3: THE SHINSHU LIVING COVENANT (Sent 10 Days Before Day 0)                              │
│   • Cultural etiquette, onsen rules, waste separation, quiet hours, harmony with Komoro neighbors │
│                                      ▼                                                           │
│   EMAIL 4: TRANSIT, PACKING & LOGISTICS (Sent 4 Days Before Day 0)                              │
│   • Tokyo → Sakudaira 70-min Shinkansen guide, shuttle meetup point, weather, packing list       │
│                                      ▼                                                           │
│   EMAIL 5: POST-STAY ALUMNI ONBOARDING (Sent 2 Days Post-Residency Checkout)                    │
│   • NPS survey, digital credentials, alumni Discord role, discounted recurring stays on zucity   │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## 2. Production Copy: The Complete 5-Email Sequence

---

### Email 01: Application Confirmation & What to Expect
- **Trigger**: Sent automatically within 60 seconds of submitting application on `https://zucity.org/en/calendar`.
- **Sender**: `admissions@zucity.org` (Display Name: *ZuCity Admissions Team*)
- **Subject**: `Application Received: Welcome to the ZuCity Residency Selection [Cohort Name]`
- **Preview Text**: *Your application has been received. Here is what happens next over the next 72 hours.*

#### Body Copy:
```markdown
Hello [First Name],

Thank you for applying to the **ZuCity [Cohort Name] Residency** in Komoro, Nagano ([Start Date] → [End Date]).

We review every application individually with a focus on Proof-of-Work, intellectual curiosity, and community fit. We intentionally cap our cohorts at 20–25 residents to preserve deep focus, authentic relationships, and high-signal unconference sessions.

### Here is what happens next:
1. **Admissions Review (48–72 Hours)**: Our team is reviewing your project proposal, technical background, and stated focus area.
2. **Shortlist Sync (If Applicable)**: If shortlisted, you will receive a calendar link for a brief 15-minute video sync with our Community Lead.
3. **Formal Decision & Room Allocation**: Successful applicants will receive an official Acceptance Letter with instructions to confirm their private suite and complete their deposit.

### In the meantime:
- **Join the Community**: Introduce yourself in our official Discord community: https://discord.gg/japanglobal
- **Explore Past Builds**: Read what previous builders shipped from our Komoro campus: https://japanglobal.org/network
- **Follow Live Updates**: See daily architectural restorations and dispatches on X: @ZuCityJapan

If you have urgent scheduling constraints or questions regarding your travel dates, simply reply directly to this email.

Warm regards from the mountains,

**The ZuCity Admissions & Curation Committee**  
*ZuCity Japan • Komoro, Nagano Prefecture*  
https://zucity.org
```

---

### Email 02: Acceptance, Thematic Thesis & Intellectual Preparation
- **Trigger**: Sent immediately upon approval and receipt of initial 50% reservation deposit.
- **Sender**: `curation@zucity.org` (Display Name: *ZuCity Community Architecture*)
- **Subject**: `Welcome to the Cohort: The Vision & Thesis for [Cohort Name]`
- **Preview Text**: *Your private suite is confirmed. Here is the intellectual thesis and reading list for our sprint in Nagano.*

#### Body Copy:
```markdown
Welcome to ZuCity, [First Name]!

Your reservation for the **ZuCity [Cohort Name] Residency** is officially confirmed. Your private suite at our restored heritage estate in Komoro, Nagano is locked.

### The Curatorial Vision: Why We Gather in the Alps
You are joining an exceptional group of 24 software engineers, AI researchers, decentralized system architects, and creators hailing from 8 countries. 

Our core thesis for this sprint is simple: **High-density intellectual peers + Radical physical stillness = Generational breakthroughs.**

By stepping away from the cognitive noise of major metropolitan centers and immersing ourselves in the alpine beauty of Nagano, we create the container for multi-week deep work that is impossible in standard tech hubs.

### Recommended Pre-Arrival Reading & Intellectual Context:
To help you understand the broader ecosystem and philosophical roots of what we are pioneering, we recommend reviewing:
1. **The Network State Synthesis**: How ZuCity serves as the living physical prototype for Chokyo (our long-term alpine future city): https://japanglobal.org/network
2. **Rural Regeneration & The Akiya Inversion**: Understanding how we restore 150-year-old vacant timber homes into modern living nodes: https://japanglobal.org/network/akiya-manifesto
3. **The Philosophy of Wa (和)**: How consensual community living covenants create harmonious peer environments.

### Your Private Cohort Channel:
You have been granted access to the private `@Resident-[Cohort-Slug]` role in the Japan Global Discord. 

👉 **Enter the Private Cohort Hub**: https://discord.com/channels/japanglobal/cohort-lounge

Introduce yourself to your fellow cohort members and share what technical hurdle or research domain you plan to tackle during our 3 weeks together.

In one week, we will share the **Shinshu Living Covenant** and local cultural guide.

Onward,

**The ZuCity Curation Team**  
*Building the Physical Prototype of the Future City*
```

---

### Email 03: The Shinshu Living Covenant & Cultural Harmony Guide
- **Trigger**: Sent 10 days before Day 0 of the residency.
- **Sender**: `community@zucity.org` (Display Name: *ZuCity Local Stewardship Desk*)
- **Subject**: `Living in Harmony: The Shinshu Rhythms & Cultural Etiquette Guide`
- **Preview Text**: *Essential guidance on onsen etiquette, quiet hours, Japanese waste separation, and local neighborhood respect.*

#### Body Copy:
```markdown
Hello [First Name],

With our residency kickoff just 10 days away, we want to share the **Shinshu Living Covenant**—the core principles that allow us to live in deep harmony with our local Komoro neighbors, artisans, and nature.

ZuCity is not an isolated bubble; we are grateful guests and active stewards in a historic Japanese castle town with centuries of living tradition.

---

### 1. The 4 Golden Rules of Our Heritage Campus:
- **Quiet Hours (22:00 – 08:00)**: Rural Japanese evenings are remarkably peaceful. All outdoor conversations, music, and loud socializing must transition indoors by 22:00.
- **Shoes-Off Protocol (*Genkan*)**: Outdoor footwear must always be removed at the raised wooden threshold of every estate. Indoor slippers are provided.
- **Strict Waste Separation**: Japan takes recycling seriously. Our estate features 5 clearly marked receptacles (Combustible, Plastics, Aluminum Cans, Glass Bottles, and Cardboard). A visual guide is posted in every kitchen.
- **100% Non-Smoking**: Due to the irreplaceable nature of 150-year-old cedar timber, smoking is strictly forbidden inside all buildings and garden verandas.

---

### 2. The Onsen (Hot Spring) Ritual at Nakadana:
Every resident receives daily access to historic Nakadana Onsen. To ensure a welcoming experience:
- **Always wash and rinse thoroughly** at the sit-down shower stalls *before* entering the hot spring bath.
- **Keep small privacy towels out of the bathwater** (rest them on your head or beside the tub).
- **Tattoos**: Nakadana Onsen is welcoming of our international community; please remain mindful and respectful of local bathers.

---

### 3. Community Dinners & Family Rhythms:
We host communal dinners four evenings per week prepared with local Shinshu buckwheat soba, fresh vegetables, and regional specialties. 
- Please update your dietary preferences on your profile: https://zucity.org/en/resident-portal
- Communal kitchen duties (loading the dishwasher, clearing tables) are shared collaboratively by all residents.

By embracing these simple cultural norms (*Wa* / 調和), we ensure that ZuCity continues to be warmly embraced by the local community.

Our next email will cover travel logistics and Shinkansen transit details from Tokyo.

With respect and anticipation,

**ZuCity Local Stewardship & Community Team**
```

---

### Email 04: Packing, Transit & Arrival Logistics Guide
- **Trigger**: Sent 4 days before Day 0.
- **Sender**: `concierge@zucity.org` (Display Name: *ZuCity Arrival Concierge*)
- **Subject**: `Transit & Packing Guide: Tokyo to ZuCity in 70 Minutes`
- **Preview Text**: *Bullet train directions, shuttle meetup point at Sakudaira Station, packing essentials, and check-in times.*

#### Body Copy:
```markdown
Hello [First Name],

The countdown is on! We are thrilled to welcome you to Komoro in just 4 days.

Here is everything you need to navigate your journey seamlessly from Tokyo to ZuCity:

---

### 🚄 Step-by-Step Transit from Tokyo:
1. **Depart Tokyo Station**: Board the **Hokuriku Shinkansen** (Asama or Hakutaka train) bound for Nagano / Kanazawa.
2. **Travel Time**: Exactly 70 minutes from Tokyo Station to **Sakudaira Station (佐久平駅)**.
3. **Cost**: Approximately ¥6,000 JPY (Tickets can be purchased via SmartEX app or ticket kiosks at Tokyo Station).
4. **Shuttle Meetup at Sakudaira Station**:
   - Our ZuCity welcome shuttle meets incoming residents at the **Sakudaira Station Asama Exit (Shinkansen Gate)** at **14:00, 16:00, and 18:00** on Day 0.
   - Look for the ZuCity welcome sign. From Sakudaira, it is a 12-minute drive to our Komoro campus.

---

### 🧳 Packing Essentials for the Japanese Alps:
- **Work Peripherals**: Your laptop, USB-C chargers, and favorite keyboard/mouse. (We provide 27" 4K displays and ergonomic chairs).
- **Alpine Clothing**: Komoro sits at 700m elevation. Daytime temperatures are pleasant (18–22°C), but mountain evenings can drop to 8–12°C. Bring a warm fleece or light down jacket.
- **Slip-On Footwear**: Shoes that are easy to take on and off for frequent transitions between buildings.
- **Trail Running / Hiking Shoes**: For weekend exploration of Mount Asama alpine paths.

---

### 🕒 Check-In & Welcome Schedule:
- **Check-In Window**: 14:00 – 19:00 on [Day 0 Date].
- **Welcome Sake Toast & Family Dinner**: 19:30 in the Main Dining Hall of Node 01.

If your flight is delayed or you plan to take an alternate train, please message our on-site team in Discord or WhatsApp: **+81-80-XXXX-XXXX**.

Safe travels, and see you in the mountains!

**ZuCity Arrival Concierge Desk**
```

---

### Email 05: Post-Stay Alumni Network & Continuing the Build
- **Trigger**: Sent 2 days after residency checkout.
- **Sender**: `alumni@japanglobal.org` (Display Name: *Japan Global Network Alumni*)
- **Subject**: `From Resident to Network Citizen: Continuing the Build with JGN`
- **Preview Text**: *Claim your digital residency credential, share your feedback, and unlock exclusive alumni booking privileges.*

#### Body Copy:
```markdown
Dear [First Name],

It was a true honor hosting you at ZuCity Komoro over the past 3 weeks. 

The energy, late-night architecture debates around the irori hearth, and the incredible artifacts shipped during Demo Day have left a lasting mark on our community and the Komoro ecosystem.

As you settle back into your regular rhythms, remember that your journey with Japan Global Network is just beginning.

---

### 1. Claim Your Digital Residency Attestation:
Your verified Proof-of-Residency credential has been issued. This verifiable badge confirms your participation in Cohort [Cohort Number] and grants you permanent voting and discussion privileges in our alumni governance channels.
👉 **Claim Your Credential**: https://japanglobal.org/credentials/[credential-id]

---

### 2. Share Your Honest Feedback (3-Minute Survey):
We are obsessed with continuous improvement. Please take 3 minutes to tell us about your experience with our fiber connectivity, work facilities, food, and community culture:
👉 **Take the Resident Survey**: https://zucity.org/feedback/[survey-token]

---

### 3. Exclusive Alumni Return Stays & Working Groups:
As a ZuCity alumnus:
- You receive **20% lifetime preferred rates** on all year-round individual stays and team retreats booked via `https://zucity.org/en/all`.
- You are invited to join our specialized JGN Working Groups (AI Agents, Architecture, Cultural Bridge, Governance) to help shape our next physical nodes.

Stay in touch on Discord (`#alumni-lounge`), and we look forward to welcoming you back to the mountains soon.

With deepest gratitude,

**The Japan Global Network & ZuCity Stewards**  
*Nagano Basin • Tokyo • Cloud*  
https://japanglobal.org
```

---
*End of Email Nurture Sequences Swipe File.*
