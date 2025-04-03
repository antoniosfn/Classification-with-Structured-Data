# Classification-with-Structured-Data

The data used in this work was obtained from the Breast Cancer Wisconsin repository (Wolberg et al., 1995), processed by the scikit-learn library (Pedregosa et al., 2011).

The analysis of the Wisconsin Breast Cancer Diagnostic dataset (569 samples, 30 features) revealed excellent performance across all tested machine learning models. The dataset showed a class distribution of 357 benign cases (62.7%) and 212 malignant cases (37.3%), indicating a moderate class imbalance.

Our comprehensive evaluation using 5-fold cross-validation demonstrated:

Logistic Regression emerged as the top-performing model with:

98.1% accuracy; 97.8% precision; 99.2% recall; 98.5% F1-score.

SVM showed nearly comparable results:

97.2% accuracy; 96.7% precision; 98.9% recall; 97.8% F1-score.

Random Forest performed slightly lower but still strongly:

95.6% accuracy; 95.9% precision; 97.2% recall; 96.5% F1-score.

All models achieved recall scores above 97%, indicating excellent sensitivity in detecting malignant cases. The particularly strong performance of Logistic Regression suggests that the classification boundaries in this dataset may be effectively modeled with linear relationships, while still maintaining robustness to the moderate class imbalance.

REFERENCES

Pedregosa, F., Varoquaux, G., Gramfort, A., Michel, V., Thirion, B., Grisel, O., Blondel, M., Prettenhofer, P., Weiss, R., Dubourg, V., Vanderplas, J., Passos, A., Cournapeau, D., Brucher, M., Perrot, M., & Duchesnay, E. (2011). Scikit-learn: Machine Learning in Python. Journal of Machine Learning Research, 12, 2825–2830.

Street, W. N., Wolberg, W. H., & Mangasarian, O. L. (1993). Nuclear feature extraction for breast tumor diagnosis. IS&T/SPIE’s Symposium on Electronic Imaging: Science and Technology, 1905, 861–870.
