# Autism-Disorder-Detection
Project Overview
This project presents a machine learning-based ASD screening tool using a Random Forest classifier. Early detection of Autism Spectrum Disorder (ASD) enables timely intervention, yet many regions lack easy access to diagnostic services. This tool empowers parents and caregivers with a fast, accessible, and reliable way to assess the risk of ASD in children based on a simple questionnaire.

📊 Dataset
The dataset consists of 6,500 entries and includes:

10 binary questionnaire responses (A1–A10)

Demographic features: Age, Sex, Jaundice, Family_ASD

Target variable: Class (Yes/No for ASD risk)

🧠 Model Used
Random Forest Classifier trained directly on the dataset without class balancing or oversampling.

Performance is evaluated using precision, recall, F1-score, and confusion matrix.
