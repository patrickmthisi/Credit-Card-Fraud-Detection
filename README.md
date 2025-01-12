# Credit-Card-Fraud-Detection

In this project, a set of cost-sensitive/weighted machine-learning algorithms was employed to predict fraudulent credit cards. The dataset is highly skewed, with fraud cases accounting for only 0.172% of the examined data.  In addition, l also explored data sampling approaches used to address class imbalances. These include but are not limited to, versions of SMOTE (SVMSMOTE and BorderlineSMOTE, ADASYN, and combinations that harness the benefits of undersampling the majority class using TOMEK links or ENN.

 Data for the project was sourced from: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud.

 ## Conclusion and recommendations:
 - In this highly skewed dataset, the voting ensemble produced the highest performance score, achieving an ROC AUC of 0.974 and a PR AUC of 0.794. Utilizing this model as a baseline, we evaluated various sampling methods, including SMOTE and SMOTETomek, to address the challenges posed by class imbalance. While the ROC AUC remained consistent across the different sampling techniques, SMOTE delivered the most significant improvement in PR AUC, rising to 0.810, an increase from the initial score of 0.794.

- The machine learning algorithms that we employed in this project used default parameters. Performance can be enhanced by employing grid search to determine the best parameters. 

- One can explore one-class algorithms in this work as well. The ones that l can think of are isolation forests or one-class support vector machines. Due to the severe class imbalance, we believe these algorithms could yield very interesting and useful results. 
