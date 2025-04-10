# Churn-Reduction-and-Customer-Lifetime-Value-Enhancement-in-a-Telecom-Company
A customer segmentation and churn prediction project for a telecom company, focused on identifying high-risk customers, improving retention, and maximizing Customer Lifetime Value (CLV) using clustering, predictive modeling, and actionable marketing insights.

## Project Summary

Customer churn is one of the biggest challenges in the telecom industry — every lost customer costs **$2,926**, adding up to over **$5.5M annually**. This project, conducted for Borcelle Company, identifies actionable insights and builds a predictive framework to help reduce churn by:

- Understanding which customers are at highest risk of leaving.
- Segmenting users based on behavior and service usage.
- Recommending personalized retention strategies per segment.

---

## Objectives

- **Identify high-risk customers** through churn prediction modeling.
- **Segment customers** to understand behavioral differences using clustering techniques.
- **Visualize and interpret churn patterns** across demographics, services, and payment methods.
- **Recommend targeted actions** to improve customer retention and lifetime value (CLV).

---

## Key Insights

- **Tenure is critical**: New customers (<1 year) have the highest churn rates.
- **Payment method matters**: Customers using electronic checks are nearly twice as likely to churn.
- **Demographics like gender are less predictive** than behavioral features.
- **CLV correlates with tenure and monthly charges** — retaining early customers boosts long-term revenue.

---

## Methodology Overview

1. **Data Cleaning & Feature Engineering**
   - Imputed missing values, standardized numeric fields.
   - Created Customer Lifetime Value (CLV) and Total Services metrics.
   - Encoded categorical variables (Label + Target Encoding).

2. **Customer Segmentation**
   - Applied **K-Means clustering** to group customers by usage patterns and demographics.
   - Visualized behavioral characteristics (partner status, dependents, seniority) by cluster.

3. **Churn Prediction Models**
   - Trained **XGBoost** and **Random Forest** models separately for each cluster.
   - Used **SMOTE** to balance class distribution before training.
   - Achieved up to **91% accuracy** in low-risk clusters.

4. **Cluster-Specific Recommendations**
   - Suggested **contract incentives** for new customers.
   - Promoted **automatic payments** to reduce churn.
   - Encouraged **tech support and service bundles** for upselling.

---

## Visual Insights

Our analysis includes:

- Churn distribution by gender, partner status, and tenure.
- CLV distribution by cluster.
- Churn rates by payment method and service features.
- Cluster-specific churn breakdowns for deep targeting.

> Visualizations were created using `matplotlib`, `seaborn`, and `scikit-learn` for PCA and t-SNE.

---

## Technologies Used

- Python (Pandas, NumPy, Scikit-learn, XGBoost, imbalanced-learn)
- Jupyter Notebooks
- Matplotlib, Seaborn
- SMOTE (for class balancing)

---

## Future Enhancements

- Integrate **email engagement data** to refine churn models.
- Use **A/B testing** to optimize promotional messaging.
- Add **SHAP or LIME** for model interpretability.
- Deploy recommendations through a **streamlit dashboard** for the marketing team.

---

## Team

Dameli Aziken • Siboney Cardoso • Ari Pai • Andrew White • Anita Yadav

---

## License

This project is for academic and professional demonstration purposes. Feel free to reference or adapt with attribution.

---

## Contact

For inquiries or collaboration opportunities, feel free to reach out via LinkedIn or GitHub.
