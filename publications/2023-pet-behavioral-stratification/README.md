# Medial Temporal Lobe Tau Aggregation Relates to Divergent Cognitive and Emotional Empathy Abilities in Alzheimer’s Disease

**Published In:** Journal of Alzheimer’s Disease, 2023  
**DOI:** [https://doi.org/10.3233/JAD-230367](https://doi.org/10.3233/JAD-230367)

## Abstract
Background:  
In Alzheimer’s disease (AD), the gradual accumulation of amyloid-β (Aβ) and tau proteins may underlie alterations in empathy.  

Objective:  
To assess whether tau aggregation in the medial temporal lobes related to differences in cognitive empathy (the ability to take others’ perspectives) and emotional empathy (the ability to experience others’ feelings) in AD.  

Methods:  
Older adults (n = 105) completed molecular Aβ positron emission tomography (PET) scans. Sixty-eight of the participants (35 women) were Aβ positive and symptomatic with diagnoses of mild cognitive impairment, dementia of the Alzheimer’s type, logopenic variant primary progressive aphasia, or posterior cortical atrophy. The remaining 37 (22 women) were asymptomatic Aβ negative healthy older controls. Using the Interpersonal Reactivity Index, we compared current levels of informant-rated cognitive empathy (Perspective-Taking subscale) and emotional empathy (Empathic Concern subscale) in the Aβ positive and negative participants. The Aβ positive participants also underwent molecular tau-PET scans, which were used to investigate whether regional tau burden in the bilateral medial temporal lobes related to empathy.  

Results:  
Aβ positive participants had lower perspective-taking and higher empathic concern than Aβ negative healthy controls. Medial temporal tau aggregation in the Aβ positive participants had divergent associations with cognitive and emotional empathy. Whereas greater tau burden in the amygdala predicted lower perspective-taking, greater tau burden in the entorhinal cortex predicted greater empathic concern. Tau burden in the parahippocampal cortex did not predict either form of empathy.  

Conclusions:  
Across AD clinical syndromes, medial temporal lobe tau aggregation is associated with lower perspective-taking yet higher empathic concern.

---

## Technical Methodologies
*Although raw data and code are protected under university intellectual property, this molecular neuroimaging and behavioral study demonstrates the ability to isolate distinct, divergent neural features to predict specific socioemotional and behavioral outcomes:*
*   **Tools:** R packages (MASS, MuMIn, nlme, lmtest, car, lsmeans, ggplot2, visreg, plotly, sjPlot).
*   **Predictive Behavioral Modeling:** Implemented forward-selection hierarchical regression models to predict divergent socioemotional outcomes based on competing neural features, successfully pinpointing region-specific predictors (tau burden) while strictly controlling for multicollinearity.
*   **Multivariate Cohort Analysis:** Conducted multivariate linear regressions to characterize the clinical cohort (Amyloid-β positive individuals across multiple neurodegenerative syndromes), quantifying statistically significant elevations in emotional empathy alongside simultaneous declines in cognitive empathy.
*   **Exploratory Data Analysis (EDA) for Cohort Stratification:** Identified localized differences in behavioral profiles by conducting exploratory multivariate linear regressions followed by Type-II analyses of variance (ANOVA) and Bonferroni-corrected post-hoc tests to segment the broader clinical population into syndrome-specific cohorts.
*   **Biomarker and Behavioral Integration:** Cross-analyzed dual-tracer molecular PET scans (Amyloid-β and tau) with multidimensional cross-sectional behavioral indices.

## Industry Application
*How this methodology translates to commercial data science:*
*   **Predictive Feature Extraction and Identification:** Deploying selective analyses to effectively localize predictive data features is relevant to efficiently building complex industry products such as targeted health algorithms or models.
*   **Behavioral Proxy Development:** Demonstrates the ability to decouple behavioral metrics and map biological endpoints (regional tau aggregation) onto these distinct, quantifiable behavioral profiles. This would be applicable to creating proxy metrics for digital health products, where objective physiological data is used to predict user states or outcomes.
*   **Advanced Stratification Modeling:** Shows expertise in segmenting complex clinical populations using a combination of molecular data and behavioral proxies to uncover non-obvious, counter-intuitive statistical effects that may provide insights into subtle socioemotional or health changes.


