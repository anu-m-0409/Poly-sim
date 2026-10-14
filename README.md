# India Budget 2025-26 Simulator & Union Budget Policy Analysis

An interactive simulation dashboard and exploratory policy analysis sandbox modeling the Union Budget 2025–26. This platform allows users to explore sector allocations, simulate macroeconomic policy trade-offs, and inspect fiscal deficit trajectories.

---

## 🔗 Live Demo

Experience the interactive frontend prototype here:  
👉 **[https://v0-policy-simulation-app-2-green.vercel.app/](https://v0-policy-simulation-app-2-green.vercel.app/)**

---

## Overview

The simulator translates the core priorities and numbers of the Union Budget 2025–26 into clear, dynamic, and exploratory visuals:

- **Macroeconomic Policy Sandbox:** Test hypothetical policy levers on capital expenditure, revenue streams, and target deficit percentages.
- **Sectoral Allocation Breakdown:** Detailed views across major expenditure heads including Defense, Infrastructure, Rural Development, Healthcare, and Education.
- **Tax Policy Explorer:** Compare direct and indirect taxation structures, slab changes under the New Tax Regime, and hypothetical revenue outcomes.
- **Fiscal Deficit & Debt Metrics:** Visual representations of borrowing requirements, interest obligations, and expenditure distributions.

---

## Built With

- **Frontend & Prototyping:** React, Next.js, Tailwind CSS (generated & architected via v0 by Vercel)
- **Data Visualizations:** Interactive charts and distribution maps using modern web chart libraries
- **Data State:** Static JSON datasets representing Union Budget estimates and policy tables

---

## Project Structure

```text
├── public/                 # Static assets, icons, and baseline mock data
├── src/
│   ├── components/         # Dashboard cards, metric displays, and chart components
│   ├── data/               # Baseline budget allocations and slab reference data
│   ├── pages/ (or app/)    # Simulator routes and analytical view layouts
│   └── styles/             # Global styling and Tailwind configurations
├── backend/                # [In Development] Future APIs and simulation computation engine
├── package.json
└── README.md