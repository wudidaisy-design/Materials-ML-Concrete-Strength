# Materials-ML-Concrete-Strength
Machine learning-assisted prediction and screening of concrete compressive strength.

This project applies machine learning to predict concrete compressive strength from mixture composition and curing age. Objectives: analyze composition–strength relationships, develop prediction models, interpret feature importance, assess generalization, and explore ML-assisted candidate screening.

**Methods**: Python, Pandas, NumPy, Matplotlib, Seaborn; Linear Regression and Random Forest; five-fold cross-validation; group-based train–test split; feature importance, permutation importance, and residual analysis.

**Results**: Random Forest outperformed Linear Regression. Random split: R² = 0.909, MAE = 3.533 MPa, RMSE = 5.203 MPa. Group split: R² = 0.856, MAE = 4.409 MPa, RMSE = 5.835 MPa. Curing age and cement content were the leading predictive features. In retrospective screening, 6 of the 10 model-selected candidates overlapped with the actual top 10 highest-strength samples in the held-out test set.

**Limitations**: The study uses an existing dataset without new experiments; screening is retrospective and does not establish experimentally validated optimal compositions.

**Future interests**: More advanced ML methods and applications to computational materials science, data-driven alloy design, and property prediction for biomedical materials.
