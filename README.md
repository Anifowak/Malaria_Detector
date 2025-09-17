## Malaria Detector Project I

---

Analysis of submicroscopic Plasmodium falciparum infections (infections that cannot be detected using standard light microscopy because the parasite density in the blood is too low) using microscopy and PCR datasets.

### Project  Overview
This project investigates the detection of Plasmodium falciparum infections using two complementary diagnostic approaches: traditional light microscopy and molecular methods such as polymerase chain reaction (PCR). While microscopy has long been the standard for malaria diagnosis, it often fails to detect infections with low parasite densities, leading to an underestimation of the true malaria burden. In contrast, PCR offers enhanced sensitivity, revealing a substantial proportion of infections that are submicroscopic—low-density infections that are nonetheless capable of contributing to transmission.

The primary objectives of this study are to compare detection rates between microscopy and PCR, quantify the prevalence of submicroscopic infections through prevalence ratios, and examine how these hidden infections are distributed across different global malaria-endemic regions. By integrating and analyzing datasets from both diagnostic methods, this project provides a more comprehensive understanding of malaria epidemiology, highlights regional variations in submicroscopic infection density, and underscores the critical role of molecular diagnostics in accurately capturing the full spectrum of P. falciparum infections.

### Data Source
The dataset comes from a systematic review of malaria prevalence using microscopy and PCR across different countries and regions. [Download here]( https://raw.githubusercontent.com/HackBio-Internship/public_datasets/main/R/lancet_malaria.txt)


### Tasks
- Visualize PCR % vs. Microscopy %
- Add a 1:1 reference line to compare both techniques
- Compute the Prevalence Ratio (Microscopy Positives/PCR Positives)
- Generate boxplots of prevalence ratios across global regions
- Interpret results to determine which region has the highest density of submicroscopic infections

### Interpretation of Results
The boxplot of prevalence ratios across global regions highlights notable differences in the burden of submicroscopic Plasmodium falciparum infections. South America exhibits the lowest median prevalence ratio, indicating that microscopy detects relatively few infections compared to PCR, and suggesting a high prevalence of submicroscopic infections.

In contrast, Asia & Oceania and East Africa show intermediate prevalence ratios, consistent with a moderate burden of submicroscopic infections. West Africa demonstrates the highest prevalence ratio, implying that microscopy performs comparatively well in this region and that submicroscopic infections are less common relative to other regions.

### Recommendations
These findings underscore the critical role of molecular diagnostics, such as PCR, in accurately assessing the true malaria burden, particularly in regions like South America where submicroscopic infections are highly prevalent.

[View project on RPubs](https://rpubs.com/Akinjide/1343701)



## Malaria Detector Project II
---

Analysis of submicroscopic Plasmodium falciparum infections (infections that cannot be detected using standard light microscopy because the parasite density in the blood is too low) using microscopy and PCR datasets, including the computation of the percentage of infections missed by microscopy to highlight under-detection, Cohen’s kappa to measure agreement between the two methods, sensitivity, specificity, PPV, and NPV to evaluate microscopy accuracy against PCR, and stratified summaries of prevalence ratios and missed infections across regions to reveal geographic differences in detection efficiency.

### Project Overview
This project investigates submicroscopic Plasmodium falciparum infections—infections that are undetectable by standard light microscopy due to low parasite density—by comparing microscopy and PCR detection across multiple regions. Using a publicly available dataset, the study quantifies the proportion of infections missed by microscopy, evaluates agreement between detection methods with Cohen’s kappa, assesses microscopy accuracy through sensitivity, specificity, PPV, and NPV, and examines regional differences in prevalence ratios and missed infections. The analysis provides insight into the limitations of conventional microscopy, highlights hidden malaria reservoirs, and informs public health strategies for improved detection and surveillance.

### Tasks
- Percentage of infections missed by microscopy → which adds a clear public health message 
- Cohen’s kappa → quantitative measure of agreement between microscopy and PCR 
- Sensitivity, specificity, PPV, NPV → standard epidemiological metrics 
- Stratified summaries of prevalence ratios and missed infections by region → makes regional comparisons more explicit

[View project on RPubs](https://rpubs.com/Akinjide/1345793)
