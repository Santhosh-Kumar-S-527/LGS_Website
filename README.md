# Lingaasys Web Platform

A enterprise-grade web application built with **Astro 4**, **Tailwind CSS**, **TypeScript**, and **React**. Lingaasys delivers deterministic software foundations for real-world operations across high-concurrency cloud systems, edge telematics, and intelligent automation platforms.

---

## 🚀 Key Features & Highlights

- **Astro Server-Side Architecture**: Built with Astro 4 for ultra-low latency, optimal SEO, and zero unnecessary client-side JS hydration.
- **Modern Industrial Design System**: Tailored dark-mode aesthetic featuring deep canvas bases (`#050708`), ambient orange radial glow gradients (`#E7430B`), and Space Grotesk / Sora typography.
- **Interactive Workbench**: Dynamic capability tabs with smooth CSS entrance animations (`@keyframes tabContentEntrance`).
- **Responsive Layout**: Fluid layouts engineered for seamless experience across mobile, tablet, desktop, and ultra-wide displays.
- **Floating Support Chatbot & Contact Drawer**: Global interactive UI widgets integrated across all pages.

---

## 📁 Directory Structure

```text
lingaasys-web/
├── public/
│   ├── favicon.svg             # Lingaasys branded vector favicon
│   ├── fonts/                  # Self-hosted typography assets
│   ├── images/
│   │   ├── hero/               # Dark architectural hero photography
│   │   ├── about/              # Subtle watermarks & workshop images
│   │   ├── technology/         # Domain schematics & vector graphics
│   │   ├── industries/         # Sector photography
│   │   └── cta/                # Background overlays
│   └── logos/                  # SVG brand logos and partner marks
│
├── src/
│   ├── assets/                 # Icons & SVG vectors
│   ├── styles/
│   │   └── globals.css         # Design tokens, typography resets & variables
│   │
│   ├── types/                  # Shared TypeScript data schemas & contracts
│   │   ├── navigation.ts
│   │   ├── industry.ts
│   │   ├── career.ts
│   │   └── technology.ts
│   │
│   ├── layouts/                # Astro Layout Shells
│   │   └── Layout.astro        # Base HTML shell wrapping global nav, footer & metadata
│   │
│   ├── components/
│   │   ├── common/             # UI Primitives (Button, Badge, SectionTitle, Chatbot)
│   │   ├── layout/             # Global Frame (Navbar, Footer, ContactModal)
│   │   └── sections/           # Isolated Section Components
│   │       ├── home/           # Hero, Stats, Partners, Insights, Testimonials
│   │       ├── technology/     # TechHero, SolutionTabs
│   │       ├── about/          # AboutHero, MissionVision, TeamGrid
│   │       ├── industry/       # IndustryGrid, IndustryCard
│   │       └── career/         # ValuesList, JobPositions
│   │
│   └── pages/                  # Astro Routed Views
│       ├── index.astro         # Home Page
│       ├── technology.astro    # Technology Page
│       ├── about.astro         # About Page
│       ├── industry.astro      # Industry Page
│       └── career.astro        # Career Page
│
├── astro.config.mjs            # Astro configuration (@astrojs/node, tailwind, react)
├── tailwind.config.cjs         # Tailwind token mappings
├── package.json                # Project dependencies and scripts
└── README.md
```

---

## 🛠️ Tech Stack & Dependencies

| Tool / Library | Role / Usage |
| :--- | :--- |
| **[Astro](https://astro.build/)** | Core Web Framework (`output: 'server'`) |
| **[Tailwind CSS](https://tailwindcss.com/)** | Utility-first styling & custom design tokens |
| **[TypeScript](https://www.typescriptlang.org/)** | Type safety & strict component contracts |
| **[React](https://react.dev/)** | Interactive client islands (`Chatbot`, `ContactModal`) |
| **[Node Adapter](https://docs.astro.build/en/guides/integrations-guide/node/)** | SSR deployment adapter |

---

## 📦 Getting Started

### 1. Prerequisites
Ensure you have **Node.js** (v18.0.0 or higher) and **npm** installed on your system.

### 2. Installation
Clone the repository and install dependencies:

```bash
# Clone the repository
git clone https://github.com/Santhosh-Kumar-S-527/LGS_Website.git
cd LGS_Website

# Install dependencies
npm install
```

### 3. Development Server
Start the local development server:

```bash
npm run dev
```

Open [http://localhost:4321](http://localhost:4321) in your browser to inspect the application.

---

## 🏗️ Building for Production

To generate a production-ready build:

```bash
npm run build
```

To preview the built output locally before deployment:

```bash
npm run preview
```

---

## 📝 License

Copyright © 2026 Lingaasys Technologies. All Rights Reserved.
