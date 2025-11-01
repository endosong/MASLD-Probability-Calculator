# 🧮 MASLD Probability Calculator

A simple **web-based calculator** for estimating the probability of **Metabolic Dysfunction-Associated Steatotic Liver Disease (MASLD)** using a logistic regression equation derived from clinical and body composition parameters.

---

## 📘 Formula

**Probability (MASLD)**  
\[
P = \frac{1}{1 + e^{-y}}
\]

where

\[
y = -14.743 + 0.083×Age − 2.167×Sex + 0.319×BMI + 0.020×MBP + 0.111×PBF + 0.010×SMI
\]

**Variable Definitions:**
| Variable | Description | Unit |
|-----------|--------------|------|
| Age | Age of subject | years |
| Sex | 1 = Male, 2 = Female | — |
| BMI | Body Mass Index | kg/m² |
| MBP | Mean Blood Pressure | mmHg |
| PBF | Percent Body Fat | % |
| SMI | Skeletal Muscle Mass Index | — |

---

## 💻 How to Use

1. Download the file [`MASLD_Probability_Calculator_simple.html`](./MASLD_Probability_Calculator_simple.html)
2. Open it in any modern browser (Chrome, Edge, Safari, Firefox)
3. Enter the values for each variable
4. The **linear predictor (y)** and **predicted probability (%)** are updated automatically

---

## 🧠 Model Description

This calculator implements a **logistic regression model** developed for research and educational use in MASLD risk estimation.  
It is based on anthropometric and bioimpedance analysis (BIA)-derived parameters.  
Model coefficients were optimized for prediction accuracy in young adult populations.

**Model equation:**
\[
\text{logit}(P) = β₀ + β₁·Age + β₂·Sex + β₃·BMI + β₄·MBP + β₅·PBF + β₆·SMI
\]

| Coefficient | Value |
|--------------|--------|
| Intercept | -14.743 |
| Age | +0.083 |
| Sex | -2.167 |
| BMI | +0.319 |
| MBP | +0.020 |
| PBF | +0.111 |
| SMI | +0.010 |

---

## ⚠️ Disclaimer

- This calculator is intended **for research and educational purposes only**.  
- It should **not** be used for standalone clinical diagnosis or decision-making without professional medical evaluation and external validation.

---

## 🧾 Citation

If you use or adapt this tool for research or publication, please cite:

> Song K, et al. *Development and Validation of a Machine Learning-Based Model for Predicting MASLD in Young Adults.* (Under review)

---

## 🛠️ License

This project is distributed under the **MIT License**.  
You are free to use, modify, and distribute this calculator with attribution.

---

© 2025 Kyungchul Song, M.D., Ph.D.  
Department of Pediatrics, Yonsei University College of Medicine
