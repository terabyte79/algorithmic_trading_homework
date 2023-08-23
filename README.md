# algorithmic_trading_homework

### Tune the Baseline Trading Algorithm

1. What impact resulted from increasing or decreasing the training window?
Answer: 

* Increasing the training window from 3 months to 6 months gives the model access to more historical data for training.
* The precision and recall of -1 slightly decreased when the window was increased from 3 months to 6 months.
* The precision for 1 instance remained the same, while recall increased from 0.96 to 0.99.

2. What impact resulted from increasing or decreasing either or both of the SMA windows?

Answer:

* Increasing the SMA windows allows the model to capture longer-term trends and may help smooth out short-term noise in the data.

* The precision for both instances remained the same, indicating changing SMA did not have any significant impact on the accuracy of predictions.


###### Graphs 

svm_model 

![svm_model](/Users/ramiz/Desktop/Fintech/algorithmic_trading_homework/comparison.png)

svm_model_1 

![svm_model_1](/Users/ramiz/Desktop/Fintech/algorithmic_trading_homework/comparison_1.png)

lg_model

![lg_model](/Users/ramiz/Desktop/Fintech/algorithmic_trading_homework/lg_comparison.png)


1. For the svm_model with lower training data and a rolling window, the strategic returns outperform the actual returns.

2. For svm_model_1, when we increased the rolling window, the strategic returns seem to be underperforming compared to the actual returns.

3. By using a logistic regression model, the strategic returns appear to outperform the actual returns by a significant margin for a considerable amount of time, but they seem to be trending downwards after mid-2020.




