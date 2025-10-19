# 🧮 MASLD Probability Calculator

This repository provides an interactive **web-based calculator** for estimating the probability of **Metabolic Dysfunction–Associated Steatotic Liver Disease (MASLD)** using a logistic regression model.

## 📊 Model Equation
The model was derived from a young adult cohort study and is expressed as:

y = -14.743 + 0.083×Age - 2.167×Sex + 0.319*BMI + 0.020×MBP + 0.111×PBF + 0.010×SMI

- **Sex coding:** Male = 1, Female = 2  
- **Units:**  
  - Body Mass Index (BMI): kg/m²  
  - Mean Blood Pressure (MBP): mmHg  
  - Percent Body Fat (PBF): %  
  - Skeletal Muscle Mass Index (SMI): consistent with study definition  

---

## ⚙️ How to Use
1. Open [`masld_probability_calculator.html`](./masld_probability_calculator.html) in any modern browser (Chrome, Edge, Safari).  
2. Enter the following variables:
   - Age (years)  
   - Sex (1 = Male, 2 = Female)  
   - Body Mass Index (kg/m²)  
   - Mean Blood Pressure (mmHg)  
   - Percent Body Fat (%)  
   - Skeletal Muscle Mass Index  
3. The calculator automatically computes:
   - Linear predictor *(y)*  
   - Predicted probability (%)  
   - Risk level (Low / Moderate / High)

---

## 🩺 Clinical Note
This calculator is intended **for research and educational purposes only**.  
Do not use it for standalone clinical diagnosis or decision-making without external validation.

---

## 📄 Reference
If you use this tool in academic work, please cite:  
> Song, K.C. *et al.* “Optimal Cutoffs of Hepatic Steatosis Index and Fatty Liver Index in Diagnosing Pediatric MASLD.” (in preparation)

---

## 🧠 Example
- Age = 30 years  
- Sex = 1 (Male)  
- BMI = 25 kg/m²  
- MBP = 90 mmHg  
- PBF = 25%  
- SMI = 7  

Result → **Predicted MASLD probability ≈ 28% (Moderate risk)**

---

© 2025 Kyungchul Song, Yonsei University College of Medicine
