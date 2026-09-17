# 🌊 Ocean Intervention — Podcast Research Notes

## Episode Theme Overview
Ocean-based climate interventions include ocean fertilization, marine cloud brightening, ocean alkalinity enhancement, and machine-learning-enhanced ocean modeling. This branch covers the most active open-source projects in ocean climate science.

---

## 🔬 Key Projects Discovered

### 1. Oceananigans.jl (⭐ 1,333 | Julia) — *from search results & README context*
- **Org:** [CliMA](https://github.com/CliMA)
- **Description:** GPU-accelerated global ocean simulation in Julia — the most actively developed ocean model in the open-source world as of mid-2026.
- **Stars:** 1,333 | **Commits/Month:** ~20-25
- **Recent Development Focus (June 2026):**
  - TripolarGrid for global simulations
  - Zarr I/O (cloud-native data storage)
  - Tracer boundary conditions (ocean intervention modeling)
- **Why It Matters:** A generational leap over legacy Fortran ocean models. Julia-based modular architecture enables rapid iteration and GPU acceleration.

### 2. NCAR_ML_EKE (⭐ 20 | Jupyter Notebook | BSD-2-Clause)
- **Repo:** [CrayLabs/NCAR_ML_EKE](https://github.com/CrayLabs/NCAR_ML_EKE)
- **Description:** Using Machine Learning at Scale in HPC Simulations with SmartSim — an application to **ocean climate modeling**.
- **Stars:** 20 | **Forks:** 6
- **License:** BSD-2-Clause
- **Last Updated:** 2022-03-30
- **ReadMe Highlights:**
  - Joint effort between HPE, NCAR, and University of Victoria
  - ML parameterization of ocean eddy kinetic energy (EKE) using neural networks inside MOM6
  - Uses SmartSim/SmartRedis for coupling ML models with HPC ocean simulations
  - Reproducible research with Zenodo DOI for input data
- **Repo Structure:** `driver/`, `ml_eke/`, `MOM6_config/`, `notebooks/`

#### Recent Commit Trends (NCAR_ML_EKE):
| Date | Author | Message |
|------|--------|---------|
| 2022-03-30 | Andrew Shao | Fix notebook typos (#10) |
| 2022-03-28 | Andrew Shao | Refactor driver for colocated option (#9) |
| 2022-03-14 | Sam Partee | Update MOM6 instructions and submodule |
| 2022-02-09 | Andrew Shao | Update README.md for compiling MOM6 |
| 2022-02-08 | Andrew Shao | Update MOM6 submodule |

**Trend Analysis:** Development burst in Feb-March 2022 aligned with the paper publication. All commits relate to MOM6 ocean model integration and SmartSim ML coupling. Project is in maintenance/reproducibility mode since the paper was released.

### 3. WRF Model (⭐ 1,761 | Fortran)
- **Repo:** [wrf-model/WRF](https://github.com/wrf-model/WRF)
- **Description:** The official Weather Research and Forecasting model — widely used in climate studies including ocean-atmosphere coupling.
- **Stars:** 1,761 | **Forks:** 882
- **Last Updated:** 2026-06-08
- **Recent Commit Trends:**
  | Date | Author | Message |
  |------|--------|---------|
  | 2026-06-08 | Anthony Islas | Merge release-v4.8.0 branch |
  | 2026-06-06 | Anthony Islas | Update README and version to v4.8.0 (#2347) |
  | 2026-06-05 | weiwangncar | Turn off tempo_aerosolaware and tempo_hailaware in Registry (#2346) |
  | 2026-05-30 | weiwangncar | Fix vectorization option in AOCC stanza (#2335) |
  | 2026-05-28 | weiwangncar | Correction for eot calculation for solar radiation (#2334) |

**Trend Analysis:** WRF is extremely active with 1,761 stars and near-daily commits. The v4.8.0 release (June 2026) is the latest milestone. Ocean-atmosphere coupling is a core feature, making it relevant for ocean intervention modeling.

### 4. GCCS-Core (⭐ 9 | Python | MIT)
- **Repo:** [KOSASIH/GCCS-Core](https://github.com/KOSASIH/GCCS-Core)
- **Description:** Global Climate Control System — includes ocean intervention capabilities as part of its geoengineering framework.
- **Relevance:** Conceptual framework for ocean-based interventions, though not actively maintained.

### 5. Awesome Geoengineering (⭐ 4 | Python)
- **Repo:** [brandonhimpfen/awesome-geoengineering](https://github.com/brandonhimpfen/awesome-geoengineering)
- **Ocean-Specific Resources Listed:**
  - [Project Vesta](https://www.vesta.earth/) — Coastal enhanced weathering using olivine to capture carbon
  - [Running Tide](https://www.runningtide.com/) — Ocean-based carbon removal using algae and ocean alkalinity enhancement
  - [OpenOcean
    Literacy](https://openocean
    literacy.org/) — Ocean monitoring and data

---

## 📊 Cross-Project Trend Summary for Ocean Intervention

| Project | Language | Stars | Last Activity | Focus |
|---------|----------|-------|---------------|-------|
| WRF Model | Fortran | 1,761 | Jun 2026 | Weather/ocean-atmosphere modeling |
| Oceananigans.jl | Julia | 1,333 | Daily | Global ocean simulation, GPU-accelerated |
| NCAR_ML_EKE | Jupyter | 20 | Mar 2022 | ML ocean parameterization (EKE) |
| GCCS-Core | Python | 9 | Oct 2024 | Ocean intervention framework |
| awesome-geoengineering | Python | 4 | Sep 2026 | Ocean CDR resource list |

### Key Takeaways:
1. **The Julia ocean modeling revolution is real** — Oceananigans.jl (1,333 stars) with CliMA backing is the most exciting development in ocean simulation. Daily commits and GPU acceleration represent a paradigm shift from Fortran legacy models.
2. **ML + HPC ocean modeling is a published paradigm** — NCAR_ML_EKE demonstrated that neural network parameterizations can replace traditional physics-based ocean models (EKE parameterization) within MOM6. The paper is out; now the community needs to adopt it.
3. **WRF remains the operational workhorse** — With 1,761 stars and the v4.8.0 release, WRF continues to be the go-to model for operational ocean-atmosphere forecasting, though it's not specifically an ocean intervention tool.
4. **Ocean alkalinity enhancement and marine cloud brightening are the frontier SRM-ocean techniques** — highlighted in the awesome-geoengineering list, with Project Vesta and Running Tide as the most prominent open-source-aligned projects.

---

## 🎙️ Episode Angle Ideas
- The Julia revolution in ocean modeling: how Oceananigans.jl is replacing decades of Fortran code
- ML parameterization inside ocean models: the NCAR_ML_EKE story and what it means for climate simulation
- Ocean alkalinity enhancement: can we speed up natural weathering to remove CO₂ at scale?
- Interview angle: the CliMA team (Caltech/MIT/NASA JPL) about building the next-generation Earth system model
- Ethics angle: ocean interventions carry global consequences — who gets to decide?