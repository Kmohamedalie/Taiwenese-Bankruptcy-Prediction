# Taiwenese  Bankruptcy  Prediction using IBM SnapML

The data were collected from the Taiwan Economic Journal for the years 1999 to 2009. Company bankruptcy <br> was defined based on the business regulations of the Taiwan Stock Exchange.

**Task:** is to predict whether a bank will go bankrupt or not (classical classification Task). <br>
**Data:** <a href="https://archive.ics.uci.edu/dataset/572/taiwanese+bankruptcy+prediction">UCI Machine Learning</a>,   <a href="https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction">Kaggle</a> <br>

**Complete JupyterNotebook:** [Link](https://github.com/Kmohamedalie/Taiwenese-Bankruptcy-Prediction/blob/master/Notebook/Taiwan%20Bankruptcy%20-%20SnapML(Random%20Forest%20vs%20Boosting%20Machine).ipynb)

**Note:** the dataset is imbalanced and [SMOTE](https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.SMOTE.html) wasn't apply.



![image](https://github.com/Kmohamedalie/Taiwenese-Bankruptcy-Prediction/assets/63104472/e9e35778-f316-49f7-a55e-93443d39c9bb)


<br>

### **Metrics**

| Algorithm | Precision | Recall | F1-score | Accuracy |
|-----------|-----------|--------|----------|----------|
| Boosting Machine(SnapML)   |  96%    |  97% | 96.18%  | 97%    |


<br>


### **Classification report and Confusion matrix:**

![image](https://github.com/Kmohamedalie/Taiwenese-Bankruptcy-Prediction/assets/63104472/8673de7d-d483-4499-b3dc-e1462ffcb5ce)



### **Additional Information about the dataset**

The first attribute is the class lable. <br>
X1	Cost of Interest-bearing Debt  <br>
X2	Cash Reinvestment Ratio    <br>
X3	Current Ratio   <br> 
X4	Acid Test      <br>
X5	Interest Expenses/Total Revenue  <br>


For more on the features please follow the link: <a href="https://archive.ics.uci.edu/dataset/572/taiwanese+bankruptcy+prediction">UCI Machine Learning</a>,   <a href="https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction">Kaggle</a>
    
