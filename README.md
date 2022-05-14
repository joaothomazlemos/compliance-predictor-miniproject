# Compliance Predictor Miniproject

This is a project where I try to predict with a Receiver Operating Characteristic curve with Area under Curve (ROC AUC) score > 75%, whereas a person is gonna pay the property fine or not, and obtain the best score of 80%.
For this task, I clean and use data from a state of the US. Then, I choose a simple classification model, the Logistic Regression, and then I use a more complex, the Random Forest Classifier.

In this project, I explain every step and the whys for each decision, like model decision and their parameters.
For traning and tuning, I make use of the mutiple folders method of scoring, and the GridParamCV for searching the best model parameters with the range of the parameters that I pre set.

I make use of the sckit-learn, numpy, matplotlib, datetime and pandas libraries for this task.

This are the final results plotted:

Figure 1 - ROC AUC scores

![image](https://user-images.githubusercontent.com/62029505/168437127-52b7f9e7-205a-4124-9622-4c749009fb7a.png)

Figure 2 - Importance of each feature for the Random Forest Classifier model
![image](https://user-images.githubusercontent.com/62029505/168437456-e00fd1f7-7041-46f3-8246-84d3a1924096.png)


