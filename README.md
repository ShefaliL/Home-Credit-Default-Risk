# Home-Credit-Default-Risk
In today’s world, many people struggle to get loans due to insufficient credit histories or even non-existing credit records, which often tend to be untrustworthy lenders who exploit them. Home Credit acts towards expanding the financial inclusion for the unbanked by providing a secure borrowing experience. Home credit utilizes several alternative data and methods to predict repayment abilities. To ensure that this underserved demographic has a favorable loan experience, we will be using machine learning and statistical methods to determine these predictions. This ensures that the clients who are capable of repayment will be granted a loan and are not rejected by any means.



Diagram: This is a block diagram to understand the workflow of the data.

![image](https://github.com/ShefaliL/Home-Credit-Default-Risk/assets/76598077/68a450c7-17fa-4672-9547-8697b5e54c39)


Also, they will be given a loan maturity plan and a repayment calendar that will accredit our clients to be more successful. Our goal in this phase is to work on the Home Credit Default Risk (HCDR) data and perform some cleaning and preprocessing techniques and modeling techniques with pipelining to predict whether a person receives a loan or not. 


After merging all subordinate files, cleaning the data,performing some exploratory data analysis, we apply some preprocessing steps which also includedividing the data into numerical and categorical values. The next step involved creating new features from the existing features that could add on as a good predictor in the existing dataset. The project included 3 phases where, the first phase included training the model without feature engineering and hyperparameter tuning, the second phase included creation of 11 new features from the existing important features and creating a modeling pipeline where we determined the best hyperparameters (hyperparameter tuning) for the models to select the best model. The testing data was then parsed through the best model to get the test results. The best model for the second phase was of the Random Forest Classifier with a training accuracy of 92.4% and a test roc score of 0.72814. The third and the final phase included creation of a Multi Layer Perceptron (MLP) neural network using Pytorch.The Artificial Neural Network model yielded a training score of 91.95% and a test roc score of 0.71225.
