---
title: "ACE2 and Coronavirus Evolution"
excerpt: "A comparative protein analysis of ACE2 in bats vs. non-bats using R, MUSCLE, and Jalview."
collection: portfolio
layout: project
date: 2025-08-07
---

This project explores the evolutionary divergence of the ACE2 receptor — a key entry point for coronaviruses — across 10 bat and 10 non-bat species. Using R-based tools and Jalview visualizations, I assessed sequence conservation, entropy, and consensus residue shifts at 31 key positions implicated in viral binding.

Results show that while overall ACE2 conservation is high, several residues (e.g., 79, 31, 41) diverge significantly between groups, suggesting localized adaptation. These findings shed light on bat-specific evolutionary pressures and implications for zoonotic spillover risk.

[GitHub Repo](https://github.com/shilpasanapala/portfolio.github.io)

### Summary of Key Metrics

| Metric                     | Bats | Non-Bats |
|---------------------------|------|----------|
| Mean Conservation Score   | 8.32 | 8.39     |
| Mean Entropy              | 0.74 | 0.61     |
| Total Positions Analyzed  | 31   | 31       |

[Download annotated residue table (XLSX)](../files/Jalview_Conservation_Score_Template_Chart.xlsx)

### Conservation Scores Across Species
![Conservation heatmap](../images/conservation_heatmap.png)

### Entropy and Divergence Plot
![Entropy divergence](../images/entropy_divergence_plot.png)

### Jalview Visualization: Combined Alignment and Tree
[Jalview combined view](../images/Jalview_Combined_ExploratoryAnalysis.jvp)  
[Bat ACE2 Alignment (.jvp)](../files/Jalview_Bat_ACE2_ExploratoryAnalysis.jvp)  
[Non-Bat ACE2 Alignment (.jvp)](../files/Jalview_NonBat_ACE2_ExploratoryAnalysis.jvp)

### Tools Used
- R (Biostrings, msa, seqinr, ggmsa, ggplot2)
- Jalview
- MUSCLE for MSA
- Elicit AI
