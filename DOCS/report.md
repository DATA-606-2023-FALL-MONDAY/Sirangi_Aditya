# ﻿Default of Credit Card Clients

- Author: Aditya Sirangi
- Term: Fall 2023
- PPT:https://github.com/DATA-606-2023-FALL-MONDAY/Sirangi_Aditya/blob/main/DOCS/Capstone_final.pptx
- YouTube:
- GitHub:https://github.com/DATA-606-2023-FALL-MONDAY/Sirangi_Aditya/blob/main/src/capstone_final_code.ipynb


# Background:

- Effective risk management is fundamental for maintaining economic stability and growth in today's dynamic and interconnected financial landscape.
- Among various risk management facets, the assessment of credit risk is of paramount importance.
- Financial institutions prioritize understanding and predicting the probability of customer default on credit payments.
- The ability to assess credit risk accurately is essential for safeguarding the interests of financial institutions and promoting responsible lending.
- This research focuses on assessing credit risk, particularly regarding customers' default payments in Taiwan.

# Dataset Information:

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


# EDA


![age distribution](https://github.com/DATA-606-2023-FALL-MONDAY/Sirangi_Aditya/assets/144384906/f669cc42-951a-4e0d-b95a-890fb7b50bef)




![credit limit](https://github.com/DATA-606-2023-FALL-MONDAY/Sirangi_Aditya/assets/144384906/9fc88783-0365-4735-954c-746fcd84c112)




![payment over time](https://github.com/DATA-606-2023-FALL-MONDAY/Sirangi_Aditya/assets/144384906/33a0bbb1-4b62-4d71-9e3b-2c541ad2c62e)




![NUMBER OF CLIENTS](https://github.com/DATA-606-2023-FALL-MONDAY/Sirangi_Aditya/assets/144384906/c7983914-8140-4a47-853b-fd40fa24eb7e)




![NUMBER OF DEFAULTS](https://github.com/DATA-606-2023-FALL-MONDAY/Sirangi_Aditya/assets/144384906/b41a92f3-6470-4146-8374-279f70f43b67)





# Models and Evaluations:

- Logistic Regression

![lg1](https://github.com/DATA-606-2023-FALL-MONDAY/Sirangi_Aditya/assets/144384906/c0cf8e5d-2d33-47ad-9ba3-6100e488b756)







- Neural Networks


![rnn](https://github.com/DATA-606-2023-FALL-MONDAY/Sirangi_Aditya/assets/144384906/1a606ec2-6d6f-486a-933d-572e155fcb80)








- Mixed Naive bayes

![mnb](https://github.com/DATA-606-2023-FALL-MONDAY/Sirangi_Aditya/assets/144384906/c55f3ca8-0128-4f1a-adee-70c7162c97fe)

# Conclusion:

- As we consider Recall as our main performance metric, we observe that it has obtained a value of 0.770 which is better than the other models' results and took less time.
- For the Neural networks and Support vector machines, we can further tune the hyperparameters for better accuracy and recall values.
- We would like to propose the mixed naïve Bayes as our best model.


