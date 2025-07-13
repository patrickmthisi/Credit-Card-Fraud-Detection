# Credit-Card-Fraud-Detection
## Project aims and descriptions:
# OBJECTIVES: 

In this project, we investigated a suite of weighted machine learning methods that are commonly used to address skewed class distributions. Also investigated are data sampling approaches to address class imbalance. The following aspects are addressed in this project:
- Exploring the credit card dataset using the Dtale Exploratory Data Explorer.
- Framing the fraud detection problem, developing a test harness, and evaluating the baseline model. 
- Exploring a set of weighted machine learning algorithms and ensembles.
- Exploring a suite of data sampling methods to address class imbalance.
- In imbalanced classification problems such as fraud detection, the cost of misclassifying a fraudulent transaction as non-fraudulent (a false negative, FN) is typically higher than misclassifying a legitimate transaction as fraudulent (a false positive, FP). As a result, this project prioritizes optimizing recall—the true positive rate—to maximize the detection of fraudulent cases, even if it comes at the expense of precision. This reflects a deliberate trade-off that favors identifying as many true frauds as possible, accepting a higher false alarm rate.
- Implementing Bayesian hyperparameter searching based on the recall score to get a better coverage of fraudulent transactions.
- Determining the optimal threshold based on F2-measure:

$$\text{F2-measure} = \frac{(1 + 2^2) \times (\text{precision} \times \text{recall})}{(2^2 \times \text{precision} + \text{recall})}$$

   - This metric applies more weight to recall to limit FN, i.e., legitimate fraud cases misclassified as non-fraud, and
- Finalising and potential improvements.
