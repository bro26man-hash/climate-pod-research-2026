# 🌍 Climate Technology & Geoengineering Podcast — Research Index

> **Repository:** `climate-pod-research-2026`  
> **Purpose:** GitHub-based research hub for a podcast series on climate technology and geoengineering  
> **Created:** September 2026  
> **Branches:** `solar-geoengineering` | `carbon-capture` | `ocean-intervention`

---

## 🎧 About This Series

This podcast explores the cutting edge of **climate technology and geoengineering** — the open-source tools, research institutions, and scientific debates shaping humanity's response to the climate crisis. Each episode branch contains curated GitHub project discoveries, commit trend analyses, podcast angle ideas, and key terminology.

---

## 🌿 Episode Branches

| Branch | Episode Theme | Key Projects |
|--------|--------------|-------------|
| [`solar-geoengineering`](../tree/solar-geoengineering) | ☀️ Solar Radiation Management | ClimateMARGO.jl, GCCS-Core, awesome-geoengineering |
| [`carbon-capture`](../tree/carbon-capture) | 🌱 Carbon Dioxide Removal | ClimateMARGO.jl, CarbonPlan, CCU-LCA, CCUS Maptool |
| [`ocean-intervention`](../tree/ocean-intervention) | 🌊 Ocean-Based Interventions | Oceananigans.jl, WRF, NCAR_ML_EKE, Project Vesta, Running Tide |

---

## 🔭 Top Project Discoveries Across All Themes

### 🔥 Most Active Projects (as of September 2026)

| Rank | Project | Stars | Language | Focus |
|------|---------|-------|----------|-------|
| 1 | [WRF Model](https://github.com/wrf-model/WRF) | 1,761 | Fortran | Weather Research & Forecasting |
| 2 | [Oceananigans.jl](https://github.com/CliMA/Oceananigans.jl) | 1,333 | Julia | GPU-accelerated global ocean simulation |
| 3 | [ClimateMARGO.jl](https://github.com/ClimateMARGO/ClimateMARGO.jl) | 73 | Julia | Climate-economic geoengineering optimizer |
| 4 | [carbonplan/forest-risks](https://github.com/carbonplan/forest-risks) | 35 | Python | Forest carbon risk statistical models |
| 5 | [carbonplan/cdr-database](https://github.com/carbonplan/cdr-database) | 29 | Python | CDR project evaluation database |
| 6 | [NCAR_ML_EKE](https://github.com/CrayLabs/NCAR_ML_EKE) | 20 | Jupyter | ML ocean parameterization (EKE) |
| 7 | [GCCS-Core](https://github.com/KOSASIH/GCCS-Core) | 9 | Python | Global Climate Control System framework |
| 8 | [SciGaP/simccs-maptool](https://github.com/SciGaP/simccs-maptool) | 8 | MPS | CCUS decision support tool |
| 9 | [massimopizzol/CCU-LCA](https://github.com/massimopizzol/CCU-LCA) | 14 | Jupyter | LCA of carbon capture & utilization tech |
| 10 | [brandonhimpfen/awesome-geoengineering](https://github.com/brandonhimpfen/awesome-geoengineering) | 4 | Python | Curated geoengineering resource list |

---

## 📊 Key Commit Trend Findings

### ⭐ The CliMA Ecosystem is the Dominant Force
The [Climate Modelling Alliance (CliMA)](https://github.com/CliMA) — a collaboration between Caltech, MIT, and NASA JPL — is running the most active open-source Earth System Model development effort in the world. Their modular Julia-based stack (Oceananigans + ClimaAtmos + ClimaLand) is receiving daily commits across all three components.

### 🚨 ClimateMachine.jl Deprecated → Modular Architecture Won
The original monolithic CliMA model (ClimateMachine.jl, 470 ⭐) was formally deprecated in late 2022. Its replacement is a modular ecosystem of specialized packages. This is a fascinating software architecture story for the podcast.

### 🌊 Oceananigans.jl: The Julia Ocean Simulation Revolution
With 1,333 stars and near-daily commits (driven by GPU acceleration with Zarr I/O and TripolarGrid), Oceananigans.jl represents a generational leap over legacy Fortran ocean models. June 2026 development is focused on global simulation capabilities directly relevant to ocean intervention modeling.

### 💰 CarbonPlan: Research Complete, Policy Uptake Phase
CarbonPlan's key repositories (forest-risks, cdr-database) are in **maintenance mode** — the scientific work is done and published. The real story is how their open-source methodology is reshaping carbon market regulation through credibility standards.

### ⏸️ NCAR_ML_EKE: Published Paradigm, Waiting for Adoption
The ML-EKE parameterization paper is published, but the repository is in maintenance mode. The concept of coupling neural networks with HPC ocean models (MOM6 + SmartSim) is proven — the next phase is community adoption.

### 📡 ClimateMARGO.jl: Documentation Push Hints at v1.0
After a long quiet period (2022–2023), ClimateMARGO.jl received a burst of README/documentation updates in August 2026. This suggests the lead developer (Fons van der Plas) may be preparing for a stable release.

---

## 🗂️ Repository Structure

```
climate-pod-research-2026/
├── README.md                      ← Repository overview (this file)
├── RESEARCH-INDEX.md              ← This research index
├── solar-geoengineering branch
│   └── episodes/solar-geoengineering/
│       ├── research-notes.md         ← Full SRM research notes
│       └── project-index.md          ← Quick reference table
├── carbon-capture branch
│   └── episodes/carbon-capture/
│       ├── research-notes.md
│       └── project-index.md
└── ocean-intervention branch
    └── episodes/ocean-intervention/
        ├── research-notes.md
        └── project-index.md
```

---

## 🔗 Key Organizations to Follow

| Organization | GitHub | Focus |
|-------------|--------|-------|
| CliMA | [github.com/CliMA](https://github.com/CliMA) | Earth System Modeling (Julia) |
| CarbonPlan | [github.com/carbonplan](https://github.com/carbonplan) | CDR evaluation & transparency |
| ClimateMARGO | [github.com/ClimateMARGO](https://github.com/ClimateMARGO) | Climate-economic optimization |
| CrayLabs | [github.com/CrayLabs](https://github.com/CrayLabs) | ML + HPC ocean modeling |
| NOAA-GFDL | [github.com/NOAA-GFDL](https://github.com/NOAA-GFDL) | Operational ocean/atmosphere models |
| C2G | [c2g2.net](https://www.c2g2.net) | Global geoengineering governance |

---

## 📝 Research Methodology

All project discoveries and commit trend data were gathered via GitHub API searches across:
- Repository search: `geoengineering`, `climate model simulation`, `carbon capture technology`
- Code search: climate modeling, geoengineering, CDR, SRM
- Commit history analysis: top 5 most recent commits per active project
- Repository metadata: stars, forks, license, last updated date

*Research compiled via GitHub API analysis — September 2026*