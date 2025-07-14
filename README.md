# PCOS Data Modelling: Predicting Polycystic Ovarian Syndrome

# Overview
Polycystic Ovarian Syndrome (PCOS) is a common endocrine disorder affecting approximately 1 in 3 women globally. While there is currently no cure for PCOS, early detection and proactive lifestyle interventions—such as dietary adjustments, regular exercise, and avoiding processed foods—can significantly alleviate symptoms and improve long-term health outcomes.

This project aims to leverage machine learning to predict the likelihood of a woman having PCOS based on a comprehensive set of symptomatic, physiological, and lifestyle factors. By providing a tool for early indication, we hope to empower more women to seek timely diagnosis and implement beneficial lifestyle changes, thereby mitigating current symptoms and preventing future health complications associated with PCOS.

# Model Performance
The developed XGBoost classification model demonstrates strong predictive capabilities on the test dataset:

Accuracy: 97.75%

Precision: 1.00

Recall: 92.97%

These metrics indicate that the model is highly effective at identifying individuals with PCOS (high recall) while minimizing false positives (perfect precision), making it a reliable tool for preliminary risk assessment.

Features Used
The model incorporates a variety of features to make its predictions, including but not limited to:

Age

Weight and BMI

Hair follicle count

Presence of various PCOS symptoms (e.g., irregular periods, acne, hirsutism)

Other relevant clinical and lifestyle factors (specifics to be detailed in the Data section or notebook).
