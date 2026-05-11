+++
title = "Out-of-County Violator Processing Analytics"
date = "2025-09-01"
+++

Six-year operational intelligence study on inter-county violator flows, data quality, and cooperation across Washington counties.
<!--more-->

**Role:** Lead analyst / pipeline engineer

**Highlights:**
- 123,291 records (2019-2025), 10 source tables to 32-field analytic model
- Composite county cooperation score using weighted metrics
- Chi-square and Cramer's V to separate structural missingness from true gaps (0.8% true gap vs. 45% apparent)
- Automated flagging of 4,107 high-complexity dual-mismatch individuals
- GeoPandas (US Census TIGER/Line) + NetworkX directed flows
- Interactive Quarto HTML reports

**Outcomes:** Informed KPI revision for county-level violator processing; supported resource planning for cross-county transport and logistics

`Python` `pandas` `GeoPandas` `NetworkX` `SciPy` `T-SQL` `Quarto`
