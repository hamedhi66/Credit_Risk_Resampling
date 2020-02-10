# Credit_Risk_Resampling

![image-20200209175916515](C:\Users\hcivi_000.000\AppData\Roaming\Typora\typora-user-images\image-20200209175916515.png)

# Summary

**Analysis was performed to determine loan risk level based on several sampling methods as follow:**

1. ***Naive Random Oversampling**:	

    In **random oversampling,** instances of the minority class are randomly selected and added to the training set until the majority and minority classes are balanced. 

2. ***SMOTE Oversampling***

    The **synthetic minority oversampling technique (SMOTE)** is another oversampling approach to deal with unbalanced datasets. In SMOTE, like random oversampling, the size of the minority is increased. The key difference between the two lies in how the minority class is increased in size. 

3. ***Undersampling***

    Undersampling is another technique to address class imbalance. Undersampling takes the opposite approach of oversampling. Instead of increasing the number of the minority class, the size of the majority class is decreased. 

4. ***Combination of Over and Under Sampling***

    SMOTEENN combines the SMOTE and Edited Nearest Neighbors (ENN) algorithms. 

**The analysis determined Prevision, Recall and Balanced Accuracy Score for each analysis:**

- Naive Random Oversampling
  - Prevision Score (Precision is the measure of how reliable a classification(High Risk & Low Risk) is):
    - High Risk: 0.01 ==> *Very Low Number*
    - Low Risk: 1.0  ==> *Too High*
  - Recall Score ( Recall is the ability of the classifier to find all the positive samples )
    - High Risk: 0.69 ==> *Reasonable*
    - Low Risk: 0.61 ==> *Reasonable*
  - Balanced Accuracy Score: 0.65 ==> *can be higher*
    -  Balanced Accuracy Score determine the accuracy, or how often the classifier is correct with the model 
- SMOTE Oversampling
  - Prevision Score:
    - High Risk: 0.01 ==> *Very Low Number*
    - Low Risk: 1.0  ==> *Too High*
  - Recall Score
    - High Risk: 0.57 ==> *Reasonable*
    - Low Risk: 0.67 ==> *Reasonable*
  - Balanced Accuracy Score: 0.62 ==> *can be higher*
- Undersampling
  - Prevision Score:
    - High Risk: 0.01 ==> *Very Low Number*
    - Low Risk: 1.0  ==> *Too High*
  - Recall Score
    - High Risk: 0.58 ==> *Reasonable*
    - Low Risk: 0.68 ==> *Reasonable*
  - Balanced Accuracy Score: 0.65 ==> *can be higher*
- Combination of Over and Under Sampling
  - Prevision Score:
    - High Risk: 0.01 ==> *Very Low Number*
    - Low Risk: 1.0 ==> *Too High*
  - Recall Score
    - High Risk: 0.70 ==> *Reasonable*
    - Low Risk: 0.60 ==> *Reasonable*
  - Balanced Accuracy Score: 0.62 ==> *can be higher*

### **Recommendation**/Justifications:

- Non of the models seems to be accurate enough based on current analysis
  - Reasoning: The main reason is Low Accuracy (near 0) for high risk categories.