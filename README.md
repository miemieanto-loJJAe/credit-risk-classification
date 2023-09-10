# credit-risk-classification
The purpose of this analysis is to train a model for loan risks. A historical lending activity dataset was used to build a model that will be able to identify the creditworthiness of different borrowers. This dataset holds financial information that is related to the loans. The target variable is "loan_status", and it will tell us whether a loan is healthy (low risk, 0) or unhealthy (hisk-risk, 1). The logistic regression model was used for this project as it is often used for prediction of the probability of a target variable. 

RESULTS 

* Machine Learning Model 1:

    *   Precision for low-risk loan (0) – 100%
    *   Precision for high-risk loan (1) – 85%
    *   Recall for low-risk loan – 99%
    *   Recall for high-risk – 91%
    *   F1-score for low-risk – 100%
    *   F1-score for high-risk – 88%
    *   Balanced Accuracy – ~95%


* Machine Learning Model 2:

    *	Precision for low-risk loan (0) – 100%
    *	Precision for high-risk loan (1) – 84%
    *	Recall for low-risk loan – 99%
    *	Recall for high-risk – 91%
    *	F1-score for low-risk – 100%
    *	F1-score for high-score – 91%
    *	Balanced Accuracy – 99%

SUMMARY

From the results, we can see that while both models perform quite well, the second model did even better than the first. This indicates that the second model will make fewer mistake than the first when classifying healthy and unhealthy loans.
In the first model, there were 56 false negatiaves but in the second model, there were only 4 false negatives. That is a percent difference of 173.33. To add to that, the amount of true negatives increased by ~9% from 563 occurances in the first model to 615 occurances in the second model. With that said, I can safely recommend the second model. 
