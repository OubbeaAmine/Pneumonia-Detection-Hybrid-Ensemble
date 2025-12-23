Pediatric Pneumonia Detection: A Hybrid Ensemble Approach
Authors (MedTech & Santé A4)
* Amine OUBBÉA * Thomas MERCIER * Florian CHOUSTERMAN 



Project Overview
This project develops a Computer-Aided Diagnosis (CADx) system designed as a Clinical Decision Support System (CDSS). It acts as a "Safety Net" to triage pediatric chest X-rays and ensure no high-risk cases are overlooked.


Key Results
* Primary Metric: Recall (Sensitivity). * Performance: The Hybrid Ensemble achieved a 96.6% Recall on the test set. * Impact: Reduced missed pneumonia cases (False Negatives) to only 2 out of 58 cases.





Methodology
We implemented a Hybrid Ensemble Learning approach: 
1. Model A: Logistic Regression on PCA-reduced ResNet50 deep features.
2. Model B: Advanced CNN using ResNet50 Transfer Learning.
3. Ensemble: Soft voting (averaging probabilities) to maximize safety.





