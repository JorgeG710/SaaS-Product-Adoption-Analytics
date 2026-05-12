# 📈 SaaS Product Adoption & Behavioral Engagement Analytics

## 📌 The Business Problem
* **Context:** A global B2B information platform needed to understand the engagement disparity between different client segments and identify early warning signs of churn.
* **Objective:** Define a unified engagement KPI, compare behavior between "First-Year" and "Tenured" accounts, and provide data-driven recommendations to improve platform stickiness.

## 🧠 Key Methodology: Engagement Intensity (EI)
To move beyond simple active user counts, I developed the **Engagement Intensity** metric:
> **EI = Total Events / Unique Active Clients**

This allowed for a granular view of how "deeply" users were interacting with the product, rather than just tracking if they logged in.

## 🔍 Analytical Deep-Dive
* **The "Mid Operator" Crisis:** Identified a drastic **-97% drop** in engagement for the Mid Operator segment within a 4-month window, signaling a high risk of systemic churn.
* **First-Year vs. Tenured Behavior:** Discovered that first-year clients have a higher "Email Interaction" rate but a lower "Download" rate. This insight suggested that onboarding should focus on moving users from passive consumption (email) to active utility (data downloads).
* **Segment Outliers:** Isolated the "Finance Insurance" segment as the primary driver of engagement peaks, allowing the marketing team to build a "look-alike" target profile for sales prospecting.

## 🚀 Strategic Recommendations
* **Predictive Onboarding:** Recommended increasing "Download" events within the first 90 days to mitigate early-stage churn.
* **Targeted Retention:** Developed a retention strategy specifically for the Legal and Consulting segments based on their unique usage signatures.
* **Email-to-Platform Pivot:** Proposed a targeted email campaign to leverage the high email-open rates of new users to drive them toward higher-value platform features.

## 🛠️ Tech Stack
* **Data Manipulation:** Python (Pandas/NumPy) and Excel
* **Strategy & Visualization:** Power BI, Think-Cell, Matplotlib
---
*For the complete H1 Product Review presentation, see the `/dashboards` folder.*
