# H2O_AutoML_3rdCMIPB_Challenge

Overview
The analysis aimed to predict and rank individuals across various immunological and molecular outcomes post-vaccination using integrated datasets from 2020 to 2023. Robust preprocessing, feature alignment, and H2O AutoML were key to model optimization across all challenges.

Data Sources: Combined immunological (TCP, TCA) and molecular (gene expression) predictors.
Modeling Approaches: H2O AutoML used in all tasks for automated model optimization; log transformations applied to stabilize outcomes.
Strengths: Comprehensive feature integration, robust preprocessing, and strong validation metrics.
Limitations: No clinical metadata used; constrained AutoML runtime.

Challenge 1.1: IgG-PT Levels (Day 14); 
Predictors: Baseline (Day 0) IgG levels.

Challenge 1.2: IgG-PT Fold Change (Day 0 to Day 14); 
Predictors: Baseline IgG levels from 2020–2022 datasets.

Challenge 2.1: Monocyte Percentage (Day 1);
Predictors: Baseline PBMC cell frequencies.

Challenge 2.2: Monocyte Fold Change (Day 0 to Day 1);
Predictors: Baseline PBMC cell frequencies.

Challenge 3.1: CCL3 Expression (Day 3);
Predictors: Baseline gene expression of the KAT → STAT → CCL3 pathway.

Challenge 3.2: CCL3 Fold Change (Day 0 to Day 3);
Predictors: Baseline gene expression of the KAT → STAT → CCL3 pathway.

Challenge 4.1: IFN-γ/IL-5 Polarization Ratio (Day 30);
Predictors: TCP/TCA analytes and gene expression of Th1/Th2-related genes.
