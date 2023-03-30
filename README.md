# 💳 Python: Predicting Credit Card Defaulters

## Introduction
**👩🏻‍💼 THE SITUATION** 

A bank in you region want to build a model to predict credit card defaulters more accurately in order minimize money loss.
Employee attrition is a costly event for any company, not only does it imply lost productivity, but there are also costs involved in recruiting and training new personnel. Moreover, high employee turnover can create a burden on the remaining staff that are left to pick up the workload, affecting motivation and morale.

**✏️ THE OBJECTIVE**

Suppose a bank hired me as a consultant to build a model to predict credit card defaulters more accurately in order minimize money loss. They want to use the model to aid in the decision of whether to grant a loan or not to customers in the future.

The main objectives of this project are:
- Explore the data to gain insights on who is most likely to default on a loan and understand risk factors that may be related to defaulting.
- Create a binary classification model that predicts whether a client will default or not. 
- With insights from data exploration and the predictions from the model, propose an optimal threshold for the probabilities produced by the model to optimize profit for the bank.

**🛠 THE TOOLS**

This project was conducted in Python using mainly Numpy, Pandas, and Sklearn.
		
## Project
**🗄 The final output**

- You can find the notebook with all the data exploration and the classification models attempted [here](https://github.com/beatriz-fc-leitao/Predicting-Credit-Card-Defaulters-Python/blob/main/predicting_credit_card_defaulters.ipynb).

## 📚 Conclusion
**💡 Summary of Key Findings**
- Clients who have a lower maximum balance limit, who took longer to pay their loan in the previous month, and who have a lwoer level of education are more likely to default. Therefore, these appear to be risk factors for defaulting on a loan.
- The bianry classification model created in this project can predict whether someone will default or not in about 79% of cases. 
- The optimal threshold found for the model, in order to optimize the bank's profit was 0.453. This threshold was established based on the validation dataset and in this case resulted in a profit of $2,116,000. This clearly shows the benefit of using a predictive model to inform decisions of whether or not to grant a loan.

In conclusion, this project demonstrates the value of using data analysis and machine learning to assess credit risk and make informed decisions about loan approvals. By understanding the risk factors associated with defaulting on a loan and building a predictive model with an appropriate threshold, the bank can make more accurate and profitable decisions.
