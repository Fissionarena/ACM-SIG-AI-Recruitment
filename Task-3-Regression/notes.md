HousePrice is a continuous numerical value, so Linear Regression is used.
- BuyHouse is a Yes/No outcome, so Logistic Regression is appropriate.

Feature scaling is necessary because models like Logistic Regression and KNN
use distance-based calculations. Without scaling, features with larger ranges
dominate the model.Outliers can disproportionately influence regression coefficients,
leading to poor generalization and increased error.

Overfitting can be detected when training error is low but test error is high.
Techniques include cross-validation and comparing train vs test metrics.