# Georgia Housing Cost-Burden (ACS 2019–2023)
**Owners vs. Renters · County-level (159 GA counties) · CVIOG Project**

> Turns public ACS data into county-level insights for policy and planning

---

## Objective
- **Who is most cost-burdened** (≥30% of income on housing) across Georgia counties?
- How do **burdens differ by tenure** (owners vs renters), **age**, **race**, and **urbanicity**?
- Which county-level characteristics (income, education) are associated with higher/lower burden?

---

## Key findings
- **Highest-risk groups**: renters **65+**, owners **15–24** and **65+**, and **Black households (both tenures)**.
- **Urban effect (renters)**: urban counties show **+9.4 percentage points** higher renter burden (vs. non-urban).
- **Income effects**:
  - **Owners**: higher median income **reduces** burden.
  - **Renters**: each **+$1,000** household income is associated with **−0.153 pp** renter burden (WLS model).
- **Education signal (owners)**: a higher share with **Bachelor’s+** is associated with **higher** owner burden.

---

## Data sources
- **ACS 5-year estimates (2019–2023)** — U.S. Census Bureau.
- **TIGER/Line shapefiles** — county boundaries for mapping.

---

## Methods
- **Group comparisons**: Welch ANOVA + Games–Howell for unequal variances/sample sizes.
- **Modeling**: log-linear regression; **heteroskedasticity** checked via BP; **WLS** used when indicated.
- **Diagnostics**: AIC model selection, VIF multicollinearity checks, residual plots.
- **Spatial viz**: county-level **choropleths** (owners vs renters, subgroup overlays).
