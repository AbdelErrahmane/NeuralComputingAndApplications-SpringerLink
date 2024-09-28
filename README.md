
# Enhancing IoT Security through Boosting and Feature Reduction Techniques for Multiclass Intrusion Detection

## Research Paper Overview
This project investigates the effectiveness of boosting techniques combined with feature reduction methods for optimizing Intrusion Detection Systems (IDS) in IoT environments. It focuses on multiclass classification of cyberattacks using two prominent IoT datasets: NF-ToN-IoT-v2 and NF-BoT-IoT-v2.

The study evaluates five different boosting techniques:
- AdaBoost
- Gradient Boosting Machine (GBM)
- LightGBM
- CatBoost
- XGBoost

Additionally, feature selection methods such as ANOVA, Mutual Information (MI), Kendall’s test, and Chi-square are applied to improve model accuracy and reduce feature sets. The combination of XGBoost with feature reduction strategies has been found to outperform other models in terms of performance metrics such as MCC, Kappa, and AUC.

### Key Results:
- Best performance achieved using XGBoost with ANOVA+MI for NF-ToN-IoT-v2 and Kendall+Chi2 for NF-BoT-IoT-v2.
- Significant reduction in features while maintaining high detection accuracy.
- Model robustness demonstrated through cross-validation and statistical testing.

## Jupyter Notebook: BoT-IoT and ToN-IoT Dataset Analysis

### Description
This Jupyter notebook showcases the application of boosting techniques on the NF-BoT-IoT-v2 and NF-ToN-IoT-v2 datasets for multiclass cyberattack detection. Users can explore various feature selection methods and experiment with different combinations of boosting algorithms to evaluate model performance using metrics like MCC, Cohen’s Kappa, and AUC.

### Techniques Used:
- Feature Selection: ANOVA, Mutual Information (MI), Chi-square, and more.
- Boosting Algorithms: AdaBoost, Gradient Boosting, LightGBM, CatBoost, XGBoost.
- Evaluation Metrics: Kappa, MCC, AUC.

### Usage
1. Install necessary dependencies listed in the `requirements.txt`.
2. Run the notebook `bml-BoT-Num.ipynb` or `bml-ToN-Num.ipynb` to replicate the analysis on boosting techniques.
3. Modify the dataset paths and parameter configurations in the notebook to explore further variations.

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Libraries: scikit-learn, xgboost, lightgbm, catboost, numpy, pandas

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
