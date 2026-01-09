# Employee Attrition Performance Prediction

##  Overview
This project focuses on predicting employee performance and analyzing its relationship with employee attrition using machine learning techniques.  
A Kaggle dataset containing 10,000 employee records was used, and multiple models were evaluated.

---

## Dataset
- Source: Kaggle – Employee Attrition Prediction Dataset
- Total Records: 10,000
- Original Features: 26
- Features After Engineering: 41
- Target Variable: Attrition (Yes / No)

###  Preprocessed Dataset Preview
<img src="preprocessed_dataset.png" width="400"/>

---

##  Models Used
1. Logistic Regression  
2. Random Forest  
3. XGBoost  
4. MLP Neural Network  
5. Voting Ensemble  
6. Final Optimized MLP Model  

---

##  Confusion Matrices

### Logistic Regression
<img src="confusion_matrix1.png" width="300"/>

### Random Forest
<img src="confusion_matrix2.png" width="300"/>

### XGBoost
<img src="confusion_matrix3.png" width="300"/>

### MLP Neural Network
<img src="confusion_matrix4.png" width="300"/>

### Voting Ensemble
<img src="confusion_matrix5.png" width="300"/>

### Final Optimized Model
<img src="confusion_matrix6.png" width="300"/>

---

##  Key Results
- MLP Neural Network achieved the best performance
- Test Accuracy: *93%*
- F1-Macro Score: *0.9297*
- Ensemble model showed strong generalization

---

##  Conclusion
Machine learning models, especially neural networks and ensembles, can effectively predict employee performance and provide early indicators of attrition risk. This approach can support HR decision-making and workforce planning.

---
