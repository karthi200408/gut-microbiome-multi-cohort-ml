🦠 gut-microbiome-multi-cohort-ml

🗂️ A multi-class classification framework was developed using Random Forest and XGBoost models across 14 independent disease cohorts.

🌟 To improve robustness and generalization:
- Domain adaptation techniques were applied to reduce cohort-specific bias.
- Probability calibration was performed to improve reliability of predicted class probabilities.

😷 Diseases Covered
- Gastric Cancer
- Inflammatory Bowel Disease (IBD)
- Autism
- Diabetes
- Additional disease cohorts

⚙️ Methodology
- Independent cohort-based training
- Feature preprocessing and normalization
- Random Forest and XGBoost classifiers
- Probability calibration (Platt scaling / isotonic regression)
- Domain adaptation techniques for cross-cohort generalization

📊 Model Performance
- Multi-class AUROC: ~0.90
- Improved cross-cohort generalization
- Enhanced probability reliability after calibration
