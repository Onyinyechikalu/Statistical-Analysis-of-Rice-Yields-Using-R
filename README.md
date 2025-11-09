
# 🌾 Rice Yield Statistical Analysis

## 📋 Overview
This project investigates whether the mean grain yield for a rice variety (R1) in experimental fields differs significantly from the literature value of 3.5 t/ha. Using statistical hypothesis testing, the analysis determines if fertilizer treatment or field conditions significantly increased the yield.

## 🎯 Objectives
- Compare experimental mean yield to the known benchmark (3.5 t/ha).
- Test significance using a **one-sample t-test** at a 1% significance level.
- Visualize yield distributions and interpret statistical outcomes.
- Illustrate a reproducible workflow for data-driven agricultural research.

- ## 📈 Analysis Workflow
1. Imported and inspected dataset (`ricevarR1.txt`)
2. Computed summary statistics and visualized the data
3. Conducted a **one-sample t-test**
4. Visualized and interpretted statistical results
5. Reported findings and conclusions

6. ## 🪄 Example Result
**Hypotheses:**
- Null hypothesis (H₀): μ = 3.5
- Alternative hypothesis (H₁): μ > 3.5

After performing a one-sample t-test:
- p-value < 0.01 → **Reject H₀**
- Conclusion: The mean yield is significantly greater than the literature value, suggesting improved performance under experimental conditions.

- ## 💡 Key Learnings
- Applying hypothesis testing to real-world data.
- Understanding how sample means compare to population benchmarks.
- Communicating findings through statistical reasoning and visuals.
- Reproducible workflows for academic-style data analysis.
