# 🩺 Breast Cancer Subtypes Study – Meru County, Kenya  

## 📌 Project Overview  
This repository contains data analysis, visualizations, and summary tables from a hospital-based study on **breast cancer subtypes in Meru County, Kenya**.  

Breast cancer is an increasing public health concern in Meru. Hospital registries and pathology reports were reviewed to explore **sociodemographic patterns, risk factors, and associations with intrinsic breast cancer subtypes (Luminal A, Luminal B, HER2-enriched, and Basal-like)**.  

---

## 🎯 Objectives  
- To describe the **sociodemographic and lifestyle profiles** of breast cancer patients in Meru.  
- To analyze the **distribution of breast cancer intrinsic subtypes**.  
- To identify **clinical and demographic factors associated with intrinsic subtypes**.  
- To visualize findings using **plots, tables, and forest plots**.  

---

## 🧑‍⚕️ Study Site  
- **Location:** Meru County, Eastern Kenya  
- **Population:** ~1.5 million  
- **Hospitals included:** MeTRH, Jordan, Guardian, Chaaria, Kiirua  
- **Selection criteria:** Patient volume, data availability, and role in cancer care.  

---

## 📊 Methodology  
- **Study design:** Hospital-based, retrospective registry review.  
- **Data sources:** Hospital cancer registries, pathology reports, and demographics.  
- **Variables:**  
  - *Demographic:* Age, marital status, religion, employment status, BMI  
  - *Clinical:* Cancer stage, HIV status, ER/PR/HER2, Ki-67, treatment  
- **Analysis methods:**  
  - Descriptive statistics (frequencies, percentages)  
  - Data visualization (bar charts, boxplots, missingness plots)  
  - Logistic regression to model associations with intrinsic subtypes  
  - Forest plots for odds ratios and confidence intervals  

---

## 📈 Key Results  

### Sociodemographics  

- **Age distribution**  
  - Breast cancer most common among **40–60 years**.  
  - Less frequent in the **17–39 years** group.  
  - Few cases in those over 60 → sample is predominantly middle-aged.  

- **BMI categories**  
  - Most patients in the **Normal** weight group.  
  - Next: **Overweight** and **Obese**.  
  - Few classified as **Underweight**.  
  - Some missing data ("NA").  
  - Indicates higher-than-average BMI representation.  

- **Employment status**  
  - Majority **employed**.  
  - Few unemployed → reflects an economically active sample.  

- **Marital status**  
  - Majority **married**, followed by **single**.  
  - Fewer **widowed** or **separated**.  
  - Some missing data ("NA").  

- **Religion**  
  - Predominantly **Protestant/other Christian**.  
  - Few **Catholic** or **Muslim**.  
  - Indicates religious homogeneity.  

---

### 🪢 Forest Plot Findings  

#### Luminal A Subtype  

- **Cancer stage**  
  - *Stage I:* OR < 1, wide CI → patients at Stage I are less likely Luminal A, but uncertain.  
  - *Stage II:* OR slightly > 1, CI crosses 1 → no definite association.  
  - *Stage III:* OR ≈ 1, CI wide → no strong correlation.  
  - *Stage IV:* OR ≈ 1, very wide CI → not significant.  

- **HIV status**  
  - *Not available:* OR > 1, but CI crosses 1 → missing data limits interpretation.  

- **BMI group**  
  - *Overweight/Obese:* OR ≈ 1, CI crosses 1 → no clear relationship.  
  - *Not available:* OR ≈ 1 → missing data again limits interpretation.  

- **Marital status**  
  - *Married:* OR slightly < 1, CI crosses 1 → not significant.  
  - *Single:* OR ≈ 1, CI crosses 1 → no significant association.  
  - *Widowed:* Slightly > 1, not strong.  
  - *Separated:* OR << 1, suggesting much lower odds, but CI very wide → inconclusive.  
  - *Other:* OR ≈ 1 → no association.  

---

#### Luminal B Subtype  

- Forest plot generated and analyzed.  
- Detailed interpretation ongoing (see `results/ForestPlot_LuminalB.png`).  

---

#### HER2-enriched & Basal Subtypes  

- Forest plots generated.  
- No clear strong associations detected; most ORs hovered around 1 with wide confidence intervals.  
- Results indicate the need for **larger datasets** to detect significant predictors.  

---

## 📂 Repository Structure  
