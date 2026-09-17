# ☀️ Solar Geoengineering — Podcast Research Notes

## Episode Theme Overview
Solar radiation management (SRM) techniques aim to reflect a small fraction of sunlight back into space to cool the planet. This branch tracks the most active open-source projects in this space.

---

## 🔬 Key Projects Discovered

### 1. ClimateMARGO.jl (⭐ 73 | Julia | MIT)
- **Repo:** [ClimateMARGO/ClimateMARGO.jl](https://github.com/ClimateMARGO/ClimateMARGO.jl)
- **Description:** Julia implementation of MARGO — an idealized climate-economic modelling framework for optimizing trade-offs between emissions mitigation, adaptation, carbon dioxide removal, **and solar geoengineering**.
- **Stars:** 73 | **Forks:** 13
- **License:** MIT
- **Last Updated:** 2026-08-17
- **ReadMe Highlights:**
  - Interactive Pluto notebook available for running the MARGO model
  - Accompanying research article in *Environmental Research Letters* (open access)
  - Still in beta; structural changes may occur before v1.0.0
- **Repo Structure:** `src/`, `configurations/`, `docs/`, `examples/`, `test/`

#### Recent Commit Trends (ClimateMARGO.jl):
| Date | Author | Message |
|------|--------|---------|
| 2026-08-17 | Fons van der Plas | Update README.md |
| 2026-08-17 | Fons van der Plas | Update README.md (second commit) |
| 2023-10-18 | Fons van der Plas | Update unit_conversions.jl with comment |
| 2023-07-06 | Fons van der Plas | Add link to Pluto in README |
| 2022-11-14 | Fons van der Plas | Update Project.toml |

**Trend Analysis:** The project had a burst of README/documentation updates in August 2026, suggesting renewed development activity after a long quiet period (2022–2023). The lead developer is Fons van der Plas. The shift from code updates to documentation indicates the project may be preparing for a new release or major update.

---

### 2. GCCS-Core (⭐ 9 | Python | MIT)
- **Repo:** [KOSASIH/GCCS-Core](https://github.com/KOSASIH/GCCS-Core)
- **Description:** Global Climate Control System — foundational framework for real-time climate monitoring, predictive analytics, and geoengineering interventions including **solar radiation management**.
- **Stars:** 9 | **Forks:** 0
- **License:** MIT
- **Last Updated:** 2024-10-29
- **ReadMe Highlights:**
  - IoT sensor integration for real-time climate monitoring
  - Predictive modeling for climate patterns and extreme weather
  - API endpoint: `POST /api/interventions` for geoengineering intervention requests
  - Implements both carbon capture AND solar radiation management
- **Repo Structure:** `src/`, `docs/`, `examples/`, `scripts/`, `.github/`

#### Recent Commit Trends (GCCS-Core):
| Date | Author | Message |
|------|--------|---------|
| 2024-10-29 | KOSASIH | Update README.md (x5 commits same day) |

**Trend Analysis:** Five README updates all on the same day (Oct 29, 2024) suggests a major documentation overhaul or repo rebrand. The project has been inactive since, with no code commits visible — possibly read-only or in maintenance mode.

---

### 3. Awesome Geoengineering (⭐ 4 | Python)
- **Repo:** [brandonhimpfen/awesome-geoengineering](https://github.com/brandonhimpfen/awesome-geoengineering)
- **Description:** Curated list of projects, research, organizations, tools, and resources related to geoengineering — including extensive SRM coverage.
- **Stars:** 4 | **Forks:** 0
- **Last Updated:** 2026-09-06
- **SRM-Specific Resources Listed:**
  - [SilverLining](https://www.silverlining.ngo/) — Funding SRM research (marine cloud brightening)
  - [GeoMIP](https://geoeng-models.org/) — Scientific simulations of SRM effects
  - [OpenAirSRM](https://openairsrm.org/) — Advocacy for SRM transparency
  - [Harvard Solar Geoengineering Research Program](https://geoengineering.environment.harvard.edu/)
- **Tools/Models for SRM:** EN-ROADS simulator, CMIP6, FaIR Climate Model, GGRAtlas
- **Policy/Ethics:** Carnegie Council, Nature article on SRM risks, ETC Group, C2G

---

## 📊 Cross-Project Trend Summary for Solar Geoengineering

| Project | Language | Stars | Last Activity | Activity Type |
|---------|----------|-------|---------------|---------------|
| ClimateMARGO.jl | Julia | 73 | Aug 2026 | README/docs update |
| GCCS-Core | Python | 9 | Oct 2024 | README overhaul |
| Awesome Geoengineering | Python | 4 | Sep 2026 | Active curation |

### Key Takeaways:
1. **MARGO.jl is the most scientifically rigorous open-source SRM model** — 73 stars, active research backing, interactive notebook. Development is trending toward documentation polish, hinting at a potential v1.0 release.
2. **GCCS-Core is an ambitious but under-maintained framework** — while it promises real-time SRM intervention APIs, commit activity ceased after Oct 2024. Useful as a conceptual reference for the podcast, but not production-ready.
3. **The awesome-geoengineering list is the best starting point for episode resources** — it's the most actively updated and comprehensively curated, with strong SRM coverage including policy, ethics, and tools.

---

## 🎙️ Episode Angle Ideas
- Why open-source climate models matter for democratizing SRM research
- The gap between ambitious frameworks (GCCS) and working models (MARGO)
- Policy and governance challenges highlighted by the awesome-geoengineering list
- Interview angle: reach out to Fons van der Plas (MARGO lead) for the podcast