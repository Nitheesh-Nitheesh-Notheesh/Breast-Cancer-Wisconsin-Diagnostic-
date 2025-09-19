🩺 Breast Cancer Classification using K-Nearest Neighbors (KNN)

Project Overview  
This project applies the K-Nearest Neighbors (KNN) algorithm to the Breast Cancer Wisconsin (Diagnostic) dataset to classify tumors as benign or malignant. The goal is to demonstrate how distance-based classification can be used in healthcare prediction tasks.

Dataset  
- Source: UCI Machine Learning Repository / Scikit-learn  
- Records: 569  
- Features: 30 numerical features (radius, texture, perimeter, area, smoothness, concavity, symmetry, etc.)  
- Target Label: diagnosis  
  - 0 → Malignant (cancerous)  
  - 1 → Benign (non-cancerous)  
- An extra empty column (Unnamed: 32) was removed.

Workflow  
1. Data Preprocessing  
   - Removed irrelevant columns.  
   - Split into features (X) and labels (y).  
   - Standardized feature values using StandardScaler.  

2. Model Building  
   - Implemented KNN classifier from scikit-learn.  
   - Tuned the number of neighbors (k) for best accuracy.  
   - Used Euclidean distance as the metric.  

3. Evaluation  
   - Accuracy score  
   - Confusion matrix  
   - Precision, Recall, F1-score  

Results  
- The KNN model achieved high accuracy (≈95–97%) in predicting tumor type.  
- The classification report showed balanced performance for both benign and malignant cases.  

Tools & Libraries  
- Python 3  
- Google Colab / Jupyter Notebook  
- pandas, numpy  
- scikit-learn  


How to Run  
1. Open the Colab notebook:  
   https://colab.research.google.com/drive/1q5YR-K25zaLMeERUh3qXXE_vfTxiwXzi?usp=sharing  
2. Run the cells step by step.  
3. Modify k values or scaling methods to see performance changes.  

Future Scope  
- Try other classifiers (Logistic Regression, SVM, Random Forest) for comparison.  
- Apply feature selection techniques to reduce dimensionality.  
- Extend the project for real-time cancer prediction systems.  

Author  
Nithees vl 
Student  
