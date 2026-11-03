# DeltaBV Planner

Browser-based tool that turns biological variation estimates (CVI, from the EFLM Biological Variation Database) and a laboratory's analytical imprecision (CVA) into:

- personalized reference interval (prRI) rules for the LIS, using the population model (Coşkun et al., Clin Chem 2021) and the within-person model (Coskun et al., Clin Chem Lab Med 2022);
- multi-analyte delta-check tables (symmetric and asymmetric log-normal RCV, with the effect of CVI uncertainty).

Everything runs in the browser; no data leave the user's computer.

Validation: the page runs built-in checks against published values on every load. The workbook `DeltaBV_test_dataset.xlsx` reproduces every check with Excel formulas.

Author: Muhammed Fevzi Kılınçkaya (ORCID 0000-0002-0815-5467). Draft v0.1. For laboratory planning and education; verify limits locally before clinical use.

License: MIT
