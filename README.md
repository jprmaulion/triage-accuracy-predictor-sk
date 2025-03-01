# Bayesian-optimized, XGBoost-based supervised machine learning model to predict triaging accuracy in emergency settings

I developed an XGBoost-based supervised machine learning model to predict triaging accuracy in emergency settings in South Korea — whether a case is correctly triaged, under-triaged, or over-triaged. Upon identifying class imbalance in the dataset, I applied per-instance weighted loss correction using sample weights to account for the imbalance during model training. Additionally, I implemented stratified k-fold cross-validation to ensure that each fold preserved the class distribution across splits. The best model is the one that balanced performance across both majority and minority classes based on balanced accuracy from cross-validation. These procedures resulted in an average balanced accuracy of ~92% and average test set accuracy of ~98%, demonstrating the model's ability to detect both under-triage and over-triage cases even in the presence of class imbalance.


If you have questions to ask about this project, drop me a message at jprmaulion[at]gmail[dot]com. 🫶🏽
