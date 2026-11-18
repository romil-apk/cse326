# VenturePulse // Startup Pitch Deck Demo Day & Deal System

A responsive, high-performance web platform built **exclusively using pure semantic HTML5 and modern CSS3** (zero JavaScript, zero external dependencies).

---

## 🚀 Key Features

### 1. Categorized Startup Pitch Showcase
Interactive sector tabs powered by pure CSS (`:checked` pseudo-class and general sibling combinators `~`):
- **FinTech**: PayMesh Global, LedgerPulse
- **HealthTech**: OmniGenetics AI, NeuroSync Bio
- **AI / SaaS**: Synthetix Workflows, CodeArmor AI
- **CleanTech**: TerraGrid Energy, BioCapture Materials
- **EdTech**: Praxis Labs AI, MentorGraph

### 2. Startup Profile Cards
Every venture card features:
- **Problem Summary** with clear market pain points
- **Traction Metrics Grid**: Monthly Recurring Revenue (MRR), MoM User Growth %, Gross Margins, and Customer Accounts
- **Funding Ask & Terms**: Round size (e.g. `Raising $2.0M Seed`, `Raising $1.5M Seed`, `Raising $2.5M Seed+`), Valuation Caps, and SAFE instruments
- **Interactive Pitch & Modeler Triggers** and direct deal reservation CTAs

### 3. Confidential Pitch Deck & Financial Modeler Link Access Gate
- Bilateral Non-Disclosure Agreement (NDA) gated room
- Interactive **Gate Unlock Simulator** using CSS checkbox states:
  - **Locked State**: Protected with blur effects and "NDA Required" overlay.
  - **Unlocked State**: Reveals unredacted 24-slide pitch decks, 3-year audited DCF modelers, Carta cap table files, and YC SAFE documents.

### 4. Accredited Investor Registration & Deal Syndicate Form
- Investment fund / firm legal entity name
- Investor classification picker (Institutional VC, Family Office, Qualified Angel $1M+ net worth)
- Sector focus selection
- **Check Size Preference Tiers**:
  - `$10k - $25k` (Syndicate Member)
  - `$25k - $50k` (Angel Participant)
  - `$50k - $100k` (Major Angel / Family Office)
  - `$100k - $250k` (Co-Lead Ticket)
  - `$500k+` (Lead Institutional)
- Expandable Bilateral NDA Agreement terms via HTML5 `<details>` and `<summary>`
- Pure CSS real-time accreditation approval feedback badge

### 5. Pure CSS Interactive Modals (`:target`)
- Click **"Pitch & Modeler"** on any card to launch an institutional modal previewing slide deck extracts and 3-Year Audited DCF Financial Model Tables.
- Click outside or click the `×` button to seamlessly return to the showcase without page reloads.

---

## 🛠️ File Structure
```text
htmlproject/
├── index.html        # Main semantic HTML5 markup (zero <script> tags)
├── styles.css        # Modern responsive dark-mode styling & CSS interactions
└── README.md         # Project documentation & overview
```

## 🌐 How to View
Double-click `index.html` or open it with any web browser (Google Chrome, Edge, Firefox, Safari). No web server, node runtime, or build step required.
