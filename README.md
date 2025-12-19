Supplementary Data – Disproportionality Analysis Tables

This document presents the complete analytical results from applying four standard disproportionality analysis methods—BCPNN, MGPS, PRR, and ROR—to data from:
The U.S. FDA Adverse Event Reporting System (FAERS)
The WHO VigiBase database

The analysis focuses on three monoamine oxidase B inhibitors (selegiline, rasagiline, safinamide) and zonisamide.

📊 Table Overview
1. FAERS Database Analysis Tables
Lists all positive safety signals detected in FAERS, including:
Preferred Term (PT) for each adverse event
Number of reported cases
Calculated signal values with 95% confidence intervals for each method:
ROR (Reporting Odds Ratio)
PRR (Proportional Reporting Ratio)
BCPNN-IC (Bayesian Confidence Propagation Neural Network – Information Component)
MGPS-EBGM (Multi-Item Gamma Poisson Shrinker – Empirical Bayes Geometric Mean)
2. VigiBase External Validation Tables
Validates key signals from FAERS in the VigiBase database using the same analytical framework, confirming signal robustness across independent pharmacovigilance systems.
3. Monotherapy Restriction Analysis Tables
Presents signal detection results restricted to patients receiving only the target drug as monotherapy, strengthening causal inference by reducing confounding from polypharmacy.

🗂️ Data Organization

All tables are organized by:
Drug: selegiline, rasagiline, safinamide, zonisamide
Data source: FAERS, VigiBase

Each table typically includes the following columns:

Column Description
-------- -------------
Adverse Event Term MedDRA Preferred Term (PT)
Number of Reports Count of case reports involving the drug–event pair
ROR (95% CI) Reporting Odds Ratio with confidence interval
PRR (95% CI) Proportional Reporting Ratio with confidence interval
BCPNN IC (IC₀₂₅) Information Component and its lower 95% bound
MGPS EBGM (EBGM₀₅) Empirical Bayes Geometric Mean and its 5th percentile

🔍 Purpose & Transparency

This supplementary data constitutes a core output of the research and is provided to:
Ensure full reproducibility
Support transparent pharmacovigilance assessment
Comply with academic and regulatory standards for signal detection reporting
💡 Note: All analyses follow established best practices in quantitative safety signal detection using spontaneous reporting systems.
