##﻿Default of Credit Cards

- Author: Aditya Sirangi
- Term: Fall 2023
- PPT:
- YouTube:
- GitHub:

Background:

- Effective risk management is fundamental for maintaining economic stability and growth in today's dynamic and interconnected financial landscape.
- Among various risk management facets, the assessment of credit risk is of paramount importance.
- Financial institutions prioritize understanding and predicting the probability of customer default on credit payments.
- The ability to assess credit risk accurately is essential for safeguarding the interests of financial institutions and promoting responsible lending.
- This research focuses on assessing credit risk, particularly regarding customers' default payments in Taiwan.

Dataset Information:

- The credit card company has acquired information on 30,000 clients.
- The dataset includes data on 25 variables, including demographic information, credit information, payment history, and bill statements of credit card users from April 2005 to September 2005, as well as information on the result.

Dataset reference: https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients

|Groups|Column names|
| - | - |
|Identifier|ID|
|Credit Information|Limit Bal|
|Demographics|SEX, EDUCATION, MARRIAGE, AGE|
|Payment History|Sep\_History, Aug\_History, Jul\_History, Jun\_History, May\_History, Apr\_History|
|Balance Information|Sep\_Balance, Aug\_Balance, Jul\_Balance, Jun\_Balance, May\_Balance, Apr\_Balance|
|Payment Information|Sep\_Pmt, Aug\_Pmt, Jul\_Pmt, Jun\_Pmt, May\_Pmt, Apr\_Pmt|
|Default Indicator|DEF\_PAY|

Models and Evaluations:

- Logistic Regression








- Neural Networks










- Mixed Naive bayes

Conclusion:

- As we consider Recall as our main performance metric, we observe that it has obtained a value of 0.770 which is better than the other models' results and took less time.
- For the Neural networks and Support vector machines, we can further tune the hyperparameters for better accuracy and recall values.
- We would like to propose the mixed naïve Bayes as our best model.


