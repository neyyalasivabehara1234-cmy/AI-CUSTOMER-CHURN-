# How to present (5 slide talking points)

Slide 1 — Business problem
- Subscription business losing customers to churn reduces ARR.
- Objective: predict churn and create targeted retention.

Slide 2 — Data & features
- Synthetic dataset (5,000 rows). Key features: tenure, plan, usage, support calls.
- Engineered features: avg_usage_per_month, recent_activity_days, high_support_flag.

Slide 3 — Modeling approach
- Baseline models: Logistic Regression, Random Forest, XGBoost.
- Metrics: AUC, Precision, Recall, F1, PR curve for class imbalance.

Slide 4 — Key findings & actions
- High risk: short-tenure, many support calls, monthly contracts.
- Recommended actions: offer discounts, onboarding, proactive support.

Slide 5 — Dashboard & next steps
- Dashboard shows KPIs, cohort churn, ROC curve, and upload-to-predict.
- Next: feature importance, cost-sensitive models, A/B test retention offers.
