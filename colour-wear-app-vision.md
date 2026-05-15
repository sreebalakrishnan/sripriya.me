# Colour Wear App — Vision Digest & Plan

> *A daily dressing intelligence app rooted in Vedic wisdom, numerology, skin tone science, weather-awareness, and image consulting.*

---

## What I Heard — The Core Idea

You want an app that answers one question every morning:

> **"What should I wear today — and why?"**

But the answer is not a generic outfit. It is a recommendation that considers who you are (skin tone, body type, gender), where you are (location, climate, humidity), and what the day means cosmically (planetary ruler, lunar phase, numerology). The clothes themselves should not default to boring Western or boring Indian — they should suggest creative fusions and variety.

---

## The Five Pillars of the Recommendation Engine

### 1. The Cosmic Calendar (Vedic + Numerology)
The day is not just a date. It carries planetary energy and numerical vibration.

- **Planetary day colours** (Vedic Jyotish):
  - Sunday → Sun → Copper, Gold, Burnt Orange
  - Monday → Moon → White, Silver, Pale Blue
  - Tuesday → Mars → Red, Crimson, Coral
  - Wednesday → Mercury → Green, Emerald
  - Thursday → Jupiter → Yellow, Turmeric, Cream
  - Friday → Venus → Pink, Lilac, Pastel
  - Saturday → Saturn → Black, Dark Blue, Indigo

- **Panchang layer** (lunar calendar):
  - Tithi (lunar day), Paksha (Shukla = waxing / Krishna = waning)
  - Purnima (full moon) and Amavasya (new moon) as special colour occasions
  - Nakshatra of the day as a secondary modifier

- **Numerology layer**:
  - Personal date number (birth date + today's date)
  - Day-specific number vibration mapped to colours

The engine combines these three signals and weights them — not just reports them separately.

---

### 2. Location, Weather & Time of Day
Colour and fabric choices must respect the physical reality of where you are.

- **Live location** pulled with user permission
- **Current weather** — temperature, humidity (critical for coastal / tropical users), wind
- **Season** — monsoon palettes differ from winter palettes
- **Time of day** — a colour for morning office light vs. evening social occasion
- **Humidity intelligence** — learned from your own experience: what works in a dry city does not work in a humid coastal town; fabric weight and colour depth adjust accordingly

---

### 3. Skin Tone & Undertone Engine (Indian Skin Science)
Indian skin is not a monolith. The app must honour its full spectrum.

- **Tone categories to cover**:
  - Fair with yellow undertone (common in North and East India)
  - Wheatish / warm beige
  - Dusky / medium-brown (widespread across India)
  - Deep / rich brown (South India, coastal)
  - Dark with cool or neutral undertone

- **Undertone detection** (user self-selects or answers a guided quiz):
  - Warm (gold, olive, peachy)
  - Cool (pink, bluish, rosy)
  - Neutral

- **Output**: for each cosmic colour recommendation, the engine filters through which shades of that colour actually flatters the user's skin tone. (E.g., on a Monday/Moon day, "white" becomes ivory for a warm undertone, true white for a cool undertone, or off-white for neutral.)

---

### 4. Clothing Variety Engine (Not Boring)
The recommendation goes beyond colour to **what to wear it in** — without defaulting to predictable choices.

- **Fusion intelligence**: suggests combinations across Western, Indian, and Indo-Western styles
  - Saree with contemporary blouse cut
  - Kurta with relaxed trousers and a scarf tie
  - Dhoti pants with a structured top
  - Linen shirt in Vedic colour with an Indian-print accessory

- **Occasion context**: casual, work, spiritual practice, social, festive

- **Gender**: separate recommendation tracks for female and male, with a non-binary / androgynous option

- **Colour combination logic**: not just one colour, but a curated palette — primary, secondary, and accent — so the user can mix and match across their wardrobe

---

### 5. The Recommendation Card — What the User Actually Sees

Every day, one card. It shows:

```
TODAY — Monday, Purnima, Life Path 7
Location: Auroville | Humidity: 84% | Morning

PRIMARY COLOUR: Soft White (Ivory)
ACCENT: Pale Blue-Grey
AVOID: Heavy black, deep red

WHY:
→ Monday is ruled by the Moon. Moon's colours are white and silver.
→ Purnima amplifies lunar energy — white is especially auspicious today.
→ Your skin undertone (warm dusky) means ivory flatters more than stark white.
→ High humidity in Auroville today: light cotton or linen fabrics only.
→ Your numerology for today is 2 — Moon's number, aligned with today's theme.

WHAT TO WEAR:
→ Ivory cotton kurta or linen shirt
→ Pale blue-grey loose trousers or dhoti pants
→ Silver or moonstone accessory
→ Avoid heavy layering — humid morning forecast
```

The user can tap into each "WHY" section to read a deeper explanation.

---

## Phase 1 vs Phase 2

### Phase 1 — Build This First
- Day / cosmic colour engine (Vedic + numerology)
- Panchang integration (lunar phase, tithi)
- Weather + location layer
- Skin tone + undertone filter
- Clothing variety suggestions (fusion, occasion, gender)
- Recommendation card with full justification

### Phase 2 — Body Type Layer (Image Consulting)
- Body type classification: rectangle, hourglass, inverted triangle, pear, apple, petite, plus-size
- How each body type interacts with colour placement, pattern scale, and silhouette
- Clothing cuts that flatter each type (necklines, waistlines, hem lengths, sleeve types)
- Fusion styling specific to body type (e.g., what kind of kurta silhouette for an apple shape)
- Integration with the Phase 1 engine so the final recommendation is: **right colour + right shade + right silhouette**

---

## Open Questions to Resolve Before Build

1. **Data source for Panchang** — which API or dataset? (Drik Panchang, Astrosage, or custom calculation?)
2. **Numerology system** — Pythagorean or Chaldean? Or user's choice?
3. **Skin tone onboarding** — self-select from illustrated swatches, or guided quiz?
4. **Clothing content** — who creates and curates the fusion outfit database? AI-generated, editorial, or user community?
5. **Weather API** — OpenWeather, Tomorrow.io, or local IMD integration?
6. **Body type assessment (Phase 2)** — image upload + AI analysis, or self-reported measurements?
7. **Platform** — mobile-first (iOS/Android), or web app first?

---

## The App's North Star

> It does not tell you what to buy. It helps you understand what you already own, through the lens of who you are, what day it is, and where you stand under this sky.

---

*Vision captured: May 2026 | Status: Pre-development, concept stage*
