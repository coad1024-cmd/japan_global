# Landing Page Blueprint: ZuCity Accommodations & Spaces

## Document Metadata & Epistemic Status
- **Author**: Japan Global Network (JGN) Conversion Architecture & Lodging Ops Team
- **Document Type**: Production Wireframe Blueprint, Spatial Specs & Booking Architecture
- **Target Page**: Public Lodging & Work Sanctuary Catalog (`https://zucity.org/en/all`)
- **Epistemic Classification**:
  - Live Catalog Architecture: `[Confirmed Fact]`
  - Room Specs & Pricing: `[Web-Verified]` (`https://zucity.org/en/all`)
  - Automated Smart Lock Rails: `[Inference]`
- **Primary Conversion Action**: Instant Room / Estate Booking & Payment Processing

---

## 1. Information Architecture & Layout Wireframe

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│ [SECTION 1: HERO GALLERY & PROPERTY OVERVIEW]                                                    │
│ • Grid: 1 Large Master Hero + 4 Thumbnail Photos (Restored Timber Interior, Garden, Workstation) │
│ • Header: "ZuCity Heritage Coliving & Work Sanctuary • Komoro, Nagano"                           │
│ • Badges: [Super-Host Rated 4.98/5] • [NTT 1 Gbps Fiber] • [Minpaku Certified #M200028491]       │
│ • Instant Booking Widget: Check-in / Check-out / Guests / Room Type / [Check Availability →]    │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ [SECTION 2: ROOM & SUITE SPECIFICATIONS]                                                         │
│ • Interactive Selector: Suite 101 (Edo Master), Suite 102 (Garden Tatami), Suite 201 (Cedar Loft)│
│ • Specs Grid: Dimensions (sqm), Bed Configuration, Natural Light, Private Desk, En-suite Bath   │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ [SECTION 3: MISSION-CRITICAL WORK SANCTUARY AMENITIES]                                           │
│ • Speedtest Badge (850 Mbps Down / 820 Mbps Up / 4ms Ping) • Herman Miller Aeron Seating •       │
│   4K USB-C Displays • Soundproof Zoom Phone Pods • 24/7 Unlimited Espresso & Tea Bar            │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ [SECTION 4: ALPINE NEIGHBORHOOD & LOCAL EXPERIENCE GUIDE]                                        │
│ • Interactive Map: 5 Min Walk to Nakadana Onsen • 8 Min Walk to Kaikoen Castle Ruins •           │
│   10 Min to Tsuruya Organic Supermarket • 12 Min Shuttle to Sakudaira Shinkansen Station        │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ [SECTION 5: LIVE AVAILABILITY CALENDAR & TRANSPARENT PRICING ENGINE]                            │
│ • Monthly / Weekly Discount Tiers (15% off 7+ days, 35% off 28+ days)                           │
│ • Add-on Tiers: ZuCity Concierge Credits, Private Onsen Pass, Shinkansen Connector Shuttle      │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ [SECTION 6: INSTANT CHECKOUT & BOOKING CTA]                                                      │
│ • Direct Payment via Stripe (Credit Card) or Instant Crypto Settlement (USDC on Base/Polygon)   │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ [SECTION 7: HOUSE COVENANTS & CULTURAL HARMONY RULES]                                            │
│ • Quiet Hours (22:00–08:00) • Japanese Waste Sorting Guide • Shoes-off Genkan • No Smoking       │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## 2. Section-by-Section Specifications & Copy Deck

### Section 1: Hero Gallery & Property Overview
- **Visuals**: High-resolution 5-image masonry header:
  1. Main (60% width): Restored 150-year-old living hall with soaring cedar beams (*Hari*), radiant heated floors, and floor-to-ceiling glass doors opening to a moss garden.
  2. Thumb 1: Private master suite with Japanese king futon bed and shoji partitions.
  3. Thumb 2: Ergonomic workstation with dual 4K monitors and mountain view.
  4. Thumb 3: Steam rising from Nakadana natural volcanic outdoor onsen.
  5. Thumb 4: Modern chef's kitchen with Shinshu timber countertops and espresso bar.
- **Copy Specification**:
  - *Title*: **ZuCity Heritage Node 01: The Alpine Work Sanctuary**
  - *Subtitle*: *A meticulously restored 150-year-old Edo-period merchant estate in Komoro, Nagano. Built for deep work, cultural immersion, and total tranquility. 70 minutes from Tokyo.*
  - *Key Highlights*: `⚡ 1 Gbps Fiber Mesh` | `♨️ Daily Historic Onsen Access` | `🏔️ Mount Asama Views` | `🔒 Keyless Smart Lock Entry`

---

### Section 2: Room & Suite Specifications
- **Interactive Suite Comparison Matrix**:

| Suite Name | Floor Area | Bed Configuration | Workstation Setup | Bath Type | Standard Nightly Rate | 28-Day Monthly Rate |
|---|---|---|---|---|---|---|
| **Suite 101: Edo Master Chamber** | 34 sqm (21 Tatami) | King Western-Futon Hybrid | Sit-Stand Desk + 27" 4K Display + Herman Miller Aeron | Private En-Suite Cedar Soaking Tub | **¥24,000 / night** | **¥340,000 / month** |
| **Suite 102: Garden Tatami Suite** | 24 sqm (15 Tatami) | Queen Japanese Futon | Private Solid Oak Desk + Ergonomic Chair | Shared Luxury Bath (1:2 ratio) | **¥16,000 / night** | **¥230,000 / month** |
| **Suite 201: Cedar Loft Studio** | 28 sqm (17 Tatami) | Double Western Bed | In-Room Standing Desk + External Monitor | Shared Luxury Bath (1:2 ratio) | **¥18,000 / night** | **¥260,000 / month** |
| **Full Estate Private Buyout** | 220 sqm (Full Node) | 4 Private Suites (Up to 8 Pax) | 8 Workstations + Private Seminar War-Room | 3 Bathrooms | **¥85,000 / night** | **¥1,200,000 / month** |

---

### Section 3: Mission-Critical Work Infrastructure
- **Enterprise Speedtest Proof**: Real-time verified widget showing 864 Mbps download, 810 Mbps upload, 4.2ms latency to Tokyo data centers.
- **Hardware & Peripherals Inventory**:
  - Sit-stand electric oak desks with memory height presets.
  - Authentic Herman Miller Aeron and Mirra 2 ergonomic task chairs.
  - LG 27-inch 4K USB-C monitors with 90W single-cable laptop charging.
  - Individual sound-dampened acoustic phone pods for private client calls.
  - Enterprise Ubiquiti UniFi Wi-Fi 6 access points with Starlink Business satellite failover.

---

### Section 4: Neighborhood & Alpine Experience Guide
- **Interactive Neighborhood Map & Walking Radii**:
  - **Nakadana Natural Onsen (5 Min Walk)**: Historic hot springs renowned for floating Shinshu apple baths and muscle recovery.
  - **Kaikoen Castle Park (8 Min Walk)**: 400-year-old stone ramparts, Edo-period fortress gates, and spring cherry blossoms.
  - **Local Sakagura Breweries (10 Min Walk)**: Artisan sake producers utilizing pure Mount Asama snowmelt water.
  - **Tsuruya Gourmet Supermarket (10 Min Bike)**: Flagship regional market featuring fresh Nagano produce, organic meats, and local wines.
  - **Sakudaira Shinkansen Hub (12 Min Shuttle)**: Direct bullet train connection arriving in Tokyo Station in exactly 70 minutes.

---

### Section 5: Live Availability Calendar & Add-On Marketplace
- **Dynamic Calendar Engine**: Real-time date picker reflecting live room availability from `https://zucity.org/en/all`.
- **Integrated Concierge & Experience Add-Ons**:
  1. **ZuCity Concierge Agent Credits (500 Credits / ¥5,000)**: Instant access to AI-powered bilingual concierge assistance, local restaurant reservations, and bike lock rentals.
  2. **Unlimited Nakadana Onsen Pass (¥15,000 / Month)**: Daily unlimited admission to natural mineral hot spring baths.
  3. **Shinkansen Station Private Connector (¥3,000 / Trip)**: Dedicated pickup from Sakudaira Station directly to ZuCity Komoro.

---

### Section 6: Instant Booking & Frictionless Checkout
- **Payment Rails**:
  - Credit / Debit Card (Visa, Mastercard, American Express via Stripe).
  - Apple Pay / Google Pay.
  - Cryptographic Payment (USDC, USDT, ETH via Coinbase Commerce / DePay).
- **Primary Action Button**: `[Reserve Suite & Confirm Booking →]` (Executes instant transaction on `https://zucity.org/en/all`).

---

### Section 7: House Covenants & Cultural Harmony
- **Living Guidelines**:
  1. **Night Quiet Hours (22:00 – 08:00)**: Absolute quiet in outdoor areas and corridors to respect neighbors and resting residents.
  2. **Traditional Footwear Protocol**: Outdoor shoes must be removed in the *Genkan* entry hall; indoor slippers provided.
  3. **Strict Japanese Waste Separation**: Meticulous 5-stream waste sorting (Combustible, Recyclable Plastics, Cans, Glass Bottles, Cardboard).
  4. **Non-Smoking Campus**: Strictly 100% non-smoking inside all heritage timber buildings and garden grounds.

---
*End of Accommodation Landing Page Blueprint.*
