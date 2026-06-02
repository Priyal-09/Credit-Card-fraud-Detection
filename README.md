Credit Card Fraud Detection & Risk Scoring System

This project presents an end-to-end Credit Card Fraud Detection and Risk Scoring System developed using IBM SPSS Modeler. The system leverages machine learning techniques to identify fraudulent credit card transactions and classify them into risk categories for efficient investigation and decision-making.

Key Features
Fraud detection using XGBoost classification
SMOTE-based handling of severe class imbalance
Advanced feature engineering including:
Log-transformed transaction amount
Transaction hour and day extraction
Behavioral time-band categorization
Amount binning
Three-level risk scoring:
High Risk
Medium Risk
Low Risk
CHAID model for interpretability and feature importance analysis
Visual implementation using IBM SPSS Modeler following CRISP-DM methodology

## Dataset

This project is based on the Credit Card Fraud Detection dataset published by the Machine Learning Group at Université Libre de Bruxelles (ULB) and available on Kaggle.

Dataset:
https://www.kaggle.com/code/gpreda/credit-card-fraud-detection-predictive-models/input
The dataset contains 284,807 transactions, including 492 fraudulent transactions (0.172% of the data). The features V1–V28 are PCA-transformed for confidentiality.

## References
The project implementation and methodology were developed using IBM SPSS Modeler. Additional inspiration and learning resources included Kaggle notebooks and fraud detection tutorials, including:
https://www.kaggle.com/code/gpreda/credit-card-fraud-detection-predictive-models/notebook

## Technologies Used
- IBM SPSS Modeler
- XGBoost
- SMOTE
- CHAID Decision Tree
- Machine Learning
- Data Analytics

## Results
- Accuracy: 85.4%
- Risk-based transaction prioritization
- Feature importance analysis
- Fraud prediction and investigation support system

## Future Enhancements
- Real-time fraud detection
- SHAP explainability integration
- Kafka streaming deployment
- Federated learning
- Graph-based fraud network analysis

## Note
Custom test datasets used for evaluation and experimentation were generated with AI-assisted support and are not part of the original Kaggle dataset.
