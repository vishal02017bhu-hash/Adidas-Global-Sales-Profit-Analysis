# Adidas-Global-Sales-Profit-Analysis
 project utilizing Random Forest Regression (95% accuracy) and K-Means Clustering to analyze 44k+ Adidas global sales records. Optimizes pricing strategies, identifies discount "sweet spots," and provides behavioral market segmentation using Python and Explainable AI (XAI).

# Project Overview
This framework was developed to optimize retail pricing strategies for **Adidas** using a global dataset of **44,888 records**. The project addresses the **"Volume-Profit Paradox"**—identifying the exact discount thresholds that maximize sales velocity without eroding net profit margins.

#Technical Highlights
* **95% Forecasting Accuracy:** Developed a **Random Forest Regressor** achieving a verified **R² score of 0.95**.
* **Behavioral Segmentation:** Implemented **K-Means Clustering** (optimized via the Elbow Method) to partition customers into four segments.
* **Explainable AI (XAI):** Used feature importance to identify **Discount %** and **Market Exposure** as primary drivers.

# Visual Analytics
![Model Comparison](./Model_Comp<img width="1230" height="655" alt="WhatsApp Image 2026-04-20 at 09 49 17" src="https://github.com/user-attachments/assets/338513a4-5fe2-4a2f-990e-4d2797229b77" />
arison.jpeg)
*Fig: Random Forest outperforming other algorithms.*

![Elbow Method](./Elbow_Meth<img width="1230" height="655" alt="WhatsApp Image 2026-04-20 at 09 49 17" src="https://github.com/user-attachments/assets/f3b7d37a-3800-4129-bc34-fb447cff33d8" />
od.jpeg)
*Fig: Optimal K selection for clustering.*

#Key Business Insights
1. **The 40% Sweet Spot:** Optimal discount range identified between 30–50%.
2. **Global Visibility:** Products in 10+ markets show 20% higher price stability.
3. **Non-Linearity:** Ensemble methods significantly outperform linear models.

#Tech Stack
**Language:** Python 3.9+
**Libraries:**  Pandas, Scikit-Learn, Matplotlib, Seaborn.

