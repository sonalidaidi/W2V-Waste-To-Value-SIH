# 🌱 Waste2Value (W2V)

> **AI-Powered Smart Food Waste Reduction, Valorization & Sustainable Redistribution Ecosystem**  
> *Transforming institutional kitchen surplus and food processing side-streams into high-value community nourishment and circular bio-products.*

[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-6-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Leaflet](https://img.shields.io/badge/Leaflet-Maps-199900?logo=leaflet&logoColor=white)](https://leafletjs.com/)
[![Google Gemini](https://img.shields.io/badge/Google_Gemini-AI_Powered-8E75C2?logo=google&logoColor=white)](https://ai.google.dev/)

---

## 📌 Table of Contents

- [Introduction to the Project](#-introduction-to-the-project)
- [Core Sustainability Mission](#-core-sustainability-mission)
- [Key Modules Overview](#-key-modules-overview)
  - [1. Institutional Kitchen Dashboard](#1-institutional-kitchen-dashboard)
  - [2. Food Processing Unit (FPU) Module](#2-food-processing-unit-fpu-module)
  - [3. Interactive Geospatial Map Analytics](#3-interactive-geospatial-map-analytics)
  - [4. Resource Recovery & Impact Dashboard](#4-resource-recovery--impact-dashboard)
  - [5. Master Admin & Verification Control Center](#5-master-admin--verification-control-center)
- [Technology Stack](#-technology-stack)
- [System Architecture & Data Flow](#-system-architecture--data-flow)
- [Getting Started & Development Server](#-getting-started--development-server)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Environment Configuration](#environment-configuration)
  - [Running the Development Server](#running-the-development-server)
  - [Production Build & Preview](#production-build--preview)
- [Project Directory Structure](#-project-directory-structure)
- [Pre-Configured Demo Credentials](#-pre-configured-demo-credentials)
- [Contributing](#-contributing)
- [License & Acknowledgements](#-license--acknowledgements)

---

## 📖 Introduction to the Project

**Waste2Value (W2V)** is an enterprise-grade digital ecosystem designed to prevent, recover, and valorize food surplus across institutional kitchens, universities, corporate cafeterias, and industrial food processing units (FPUs).

Every day, mega-kitchens produce substantial pre-consumer and post-preparation surplus due to unpredictable attendance fluctuations. Simultaneously, food processing factories generate high-moisture organic side-streams (spent grains, fruit pomace, vegetable peels, whey) that incur hefty landfill tipping fees.

**W2V bridges this divide:**
1. **At the source:** AI-driven demand forecasting curtails overproduction before cooking begins.
2. **In real-time:** Safe, unconsumed meals are routed within minutes to verified hunger-relief shelters and food banks before shelf-life expiry.
3. **Beyond human consumption:** Inevitable kitchen scraps and industrial side-streams are automatically matched with local biogas digesters, cattle shelters (*gaushalas*), organic composting facilities, and bio-polymer manufacturers.

---

## 🌍 Core Sustainability Mission

Waste2Value is fundamentally rooted in the global circular bio-economy framework and actively advances **United Nations Sustainable Development Goal 12.3** *(halving per-capita food waste by 2030)*.

- **Mitigating Landfill Methane Emissions**: Decomposing food waste in landfills is one of the leading anthropogenic sources of methane ($CH_4$), a greenhouse gas 28× more potent than carbon dioxide over a 100-year timescale. W2V diverts organic waste to controlled aerobic composting and anaerobic biogas production.
- **Quantifying Scope 3 ESG Impact**: For corporate cafeterias and industrial food processors, W2V logs verifiable metrics—averted $CO_2e$ greenhouse gas emissions, conserved embodied virtual water (litres), and total equivalent meals served.
- **Zero Food Waste Hierarchy**: W2V operationalizes the EPA Food Recovery Hierarchy:
  $$\text{Source Reduction} \longrightarrow \text{Feed Hungry People} \longrightarrow \text{Feed Animals} \longrightarrow \text{Industrial Energy (Biogas)} \longrightarrow \text{Composting}$$

---

## 🧩 Key Modules Overview

### 1. Institutional Kitchen Dashboard
Built for mess managers, head chefs, and facility directors in universities, corporate campuses, and hospital canteens.
- **AI Batch Meal Quantity Planner**: Estimates required portions using historical trends, days of the week, weather variables, and meal types to minimize batch overproduction.
- **Surplus Detection & Safe Redistribution**: Log surplus cooked trays with automated safe-consumption countdown timers; immediately alerts the nearest verified NGOs with calculated transit ETAs.
- **Smart Menu Optimization**: Analyzes frequent kitchen left-overs and recommends recipe tweaks, ingredient substitutions, and batch portion adjustments.
- **Smart Inventory & Storage Auditor**: Tracks perishable produce shelf-life, refrigeration temperatures, and storage zones.
- **Smart Utility & Energy Monitor**: Visualizes cooking gas (LPG/PNG), water, and kitchen electricity consumption benchmarks.

### 2. Food Processing Unit (FPU) Module
Engineered for industrial food manufacturing units, breweries, juice processors, and packaging plants.
- **Side-Stream Byproduct Logger**: Catalogs wet/dry pomace, grain residues, husks, peelings, and whey by batch volume, moisture percentage, and contaminant grade.
- **Valorization Pathway Engine**: Calculates economic and environmental yields across circular applications (anaerobic methane potential, cattle feed formulation, bio-compost, and biochemical extraction).
- **Offtake Deal Management**: Facilitates direct collection agreements between processing plants and local bioconversion plants.

### 3. Interactive Geospatial Map Analytics
- **Live Leaflet GIS Dashboard**: Interactive geographic visualization of kitchens, food processing units, verified NGOs, gaushalas, and biogas reactors.
- **Color-Coded Status Markers**:
  - 🟢 **Available Food Surplus**: Live quantity and shelf-life countdown.
  - 🟠 **Food Processing Side-Streams**: High-volume industrial byproducts.
  - 🔵 **Verified NGOs & Food Banks**: Capacity and pickup radius.
  - 🟣 **Bioconversion Plants**: Biogas digesters and commercial composters.
- **Routing & Radius Calculations**: Instant directions, distance calculations, and logistics corridor analysis to minimize transport fuel emissions.

### 4. Resource Recovery & Impact Dashboard
- **Waste Segregation Tracking**: Monitors dry vs. wet vs. used cooking oil (UCO) segregation compliance.
- **Circular Valorization Metrics**: Visualizes conversion rates into animal fodder, organic vermicompost, and clean biogas units.
- **Auditable ESG Reports**: Generates downloadable impact certificates validating meals salvaged and greenhouse gases averted.

### 5. Master Admin & Verification Control Center
- **FSSAI & Regulatory Vetting**: Review government licenses, registration documents, and hygiene compliance credentials of kitchens and NGOs.
- **Platform Oversight**: Real-time audit logs of all active donations, side-stream transactions, and node verifications.
- **One-Click Approval Queue**: Verify, request clarification, or flag institutions to preserve chain-of-custody safety.

---

## 🛠 Technology Stack

| Layer | Technologies |
| :--- | :--- |
| **User Interface** | [React 19](https://react.dev/) (Modern Functional Architecture, Custom Hooks) |
| **Styling & Design System** | [Tailwind CSS v4](https://tailwindcss.com/) (Fluid Typography, Responsive Breakpoints) |
| **Build Tool & Dev Server** | [Vite 6](https://vitejs.dev/) (Ultra-fast Hot Module Replacement) |
| **Language** | [TypeScript 5.8](https://www.typescriptlang.org/) (Strict Type Safety) |
| **Geospatial Mapping** | [Leaflet](https://leafletjs.com/) & [React-Leaflet](https://react-leaflet.js.org/) |
| **Iconography** | [Lucide React](https://lucide.dev/) |
| **AI & Smart Insights** | [Google Gemini API (@google/genai)](https://ai.google.dev/) |
| **State & Persistence** | Reactive LocalStorage Sync with Persistent Storage Service |

---

## 🏗 System Architecture & Data Flow

```text
               ┌────────────────────────────────────────────────────────┐
               │             W2V Unified Frontend Portal                │
               │   (Landing, Map Analytics, Auth, Stakeholder Selector) │
               └──────────────────────────┬─────────────────────────────┘
                                          │
                  ┌───────────────────────┴───────────────────────┐
                  ▼                                               ▼
     ┌──────────────────────────┐                    ┌──────────────────────────┐
     │  Institutional Kitchen   │                    │  Food Processing Unit    │
     │  Intelligence Hub        │                    │  Valorization Engine     │
     ├──────────────────────────┤                    ├──────────────────────────┤
     │ • Meal Quantity Forecast │                    │ • Byproduct Inventory    │
     │ • Safe Surplus Dispatch  │                    │ • Valorization Matcher   │
     │ • Menu Optimization      │                    │ • Methane & Feed Yields  │
     │ • Resource Segregation   │                    │ • Utility Energy Audits  │
     └────────────┬─────────────┘                    └────────────┬─────────────┘
                  │                                               │
                  └───────────────────────┬───────────────────────┘
                                          ▼
     ┌──────────────────────────────────────────────────────────────────────────┐
     │               Geospatial Redistribution & Routing Hub                    │
     │          (Leaflet Map, Geo-Fenced Alerts to NGOs & Biogas Units)         │
     └────────────────────────────────────┬─────────────────────────────────────┘
                                          ▼
     ┌──────────────────────────────────────────────────────────────────────────┐
     │              Master Admin Verification & Compliance Center               │
     │            (FSSAI Validation, NGO Vetting, ESG Audit Reporting)          │
     └──────────────────────────────────────────────────────────────────────────┘
```

---

## 🚀 Getting Started & Development Server

### Prerequisites

Ensure you have the following installed on your machine:
- **Node.js**: `v18.0.0` or higher (LTS recommended)
- **npm**: `v9.0.0` or higher (or `bun` / `pnpm` / `yarn`)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/waste2value.git
   cd waste2value
   ```

2. **Install all dependencies:**
   ```bash
   npm install
   ```

### Environment Configuration

Create a local environment file by copying `.env.example`:

```bash
cp .env.example .env
```

*(Optional)* Provide your Google Gemini API key if you wish to run live generative menu optimization:
```env
GEMINI_API_KEY=your_gemini_api_key_here
```
> **Note:** The application functions out-of-the-box with built-in heuristic models even if no external API key is configured.

### Running the Development Server

To launch the Vite development server with Hot Module Replacement (HMR):

```bash
npm run dev
```

Once started, open your browser and navigate to:
```
http://localhost:3000
```

### Production Build & Preview

To generate an optimized production bundle:

```bash
npm run build
```

To test and preview the production build locally:

```bash
npm run preview
```

To run TypeScript verification:

```bash
npm run lint
```

---

## 📁 Project Directory Structure

```text
waste2value/
├── public/                     # Static assets (brand emblems, logos, favicon)
│   ├── LOGO.jpeg               # Master brand identity asset
│   ├── w2v_circle_emblem.png   # Transparent circular W2V mark
│   └── w2v_full_logo.png       # High-resolution full brand mark
├── src/
│   ├── assets/                 # Vector artwork and images
│   ├── components/             # Modular React view & UI components
│   │   ├── Navigation.tsx      # Top navbar with brand wordmark and role triggers
│   │   ├── HeroSection.tsx     # Hero banner with W2V branding & quick-action CTA
│   │   ├── ProductFeatures.tsx # Core circular feature highlights
│   │   ├── HowItWorks.tsx      # Four-step circular recovery workflow
│   │   ├── AboutSection.tsx    # Sustainability mission & platform background
│   │   ├── MapAnalyticsView.tsx# Fullscreen interactive Leaflet GIS dashboard
│   │   ├── InstitutionalKitchenDashboardView.tsx # Kitchen surplus & prep portal
│   │   ├── FPUDashboardView.tsx# Industrial food processing valorization portal
│   │   ├── AdminDashboardView.tsx # Compliance, verification & system audit console
│   │   ├── AdminLoginView.tsx  # Secure administrator authentication view
│   │   ├── UserLoginView.tsx   # Stakeholder login view
│   │   ├── RegistrationPage.tsx# Multi-step organization onboarding form
│   │   ├── WhoAreYouView.tsx   # Stakeholder persona selection view
│   │   ├── DetectSurplusModule.tsx # Surplus detection & safe route dispatcher
│   │   ├── PlanFoodQuantity.tsx# AI batch cooking & headcount forecaster
│   │   ├── SmartMenuOptimization.tsx # Ingredient re-balancing module
│   │   ├── SmartEnergyModule.tsx # Kitchen utility & resource monitor
│   │   ├── SmartInventoryModule.tsx # Pantry & perishable shelf-life tracker
│   │   └── ResourceRecoveryView.tsx # Bio-conversion & composting metrics
│   ├── services/
│   │   └── registrationStorage.ts # Persistent storage & seed accounts
│   ├── App.tsx                 # Root application state & navigation router
│   ├── index.css               # Tailwind CSS v4 styling rules
│   └── main.tsx                # Application DOM entry point
├── package.json                # Project dependencies and script runner
├── tsconfig.json               # TypeScript configuration
├── vite.config.ts              # Vite build configuration
└── metadata.json               # AI Studio applet specifications
```

---

## 🔑 Pre-Configured Demo Credentials

For demonstration, testing, and evaluation, you can use the built-in quick-login buttons or the following credentials:

| Role | Username / Identifier | Password | Access Area |
| :--- | :--- | :--- | :--- |
| **System Administrator** | `admin` | `admin123` | Master Admin Console |
| **Institutional Kitchen** | `demo-kitchen` | *(One-Click Demo Button)* | Kitchen Surplus & Prep Portal |
| **Food Processing Unit** | `demo-fpu` | *(One-Click Demo Button)* | FPU Valorization Hub |

---

## 🤝 Contributing

We welcome contributions from developers, sustainability advocates, and food safety researchers!

1. Fork the Project.
2. Create your Feature Branch:
   ```bash
   git checkout -b feature/CircularMetricEnhancement
   ```
3. Commit your Changes:
   ```bash
   git commit -m 'Add support for spent grain protein extraction tracking'
   ```
4. Push to the Branch:
   ```bash
   git push origin feature/CircularMetricEnhancement
   ```
5. Open a Pull Request.

---

## 📄 License & Acknowledgements

Distributed under the **MIT License**. See `LICENSE` for details.

- **SDG 12.3**: Responsible Consumption and Production.
- **Icons**: [Lucide Icons](https://lucide.dev/).
- **Maps**: [Leaflet](https://leafletjs.com/) & OpenStreetMap contributors.

---

<div align="center">
  <sub>Built with ❤️ for a Zero-Food-Waste Future • Waste2Value (W2V)</sub>
</div>
