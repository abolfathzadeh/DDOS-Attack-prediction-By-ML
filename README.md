# DDOS-Attack-prediction-By-ML
DDoS Attack Prediction using Decision Tree and Random Forest Algorithms
The most common network attacks are Denial of Service (DoS) and Distributed Denial of Service (DDoS) attacks which causes packet loss by delaying the exchange of information, thereby altering the data packets sent through networks which affect the integrity and reliability of the data

this paper improves on existing works by re-evaluating and comparing the accuracy between Decision Tree and Random Forest Algorithms in predicting DDoS attacks

## Dataset
The dataset used in this study was obtained from Kaggle (insert URL and brief description of the dataset). It contains (insert number) records of network traffic data, including both legitimate traffic and DDoS attack traffic.

## Data Understanding
The dataset used for this study is an open access dataset gotten from https://www.kaggle.com/datasets/aikenkazin/ddos-sdn-dataset [19]. The dataset is named DDoS SDN dataset with 104345 rows and 23 columns. The dataset contains 3 categorical and 20 numeric features (including the label).

 ![image](https://user-images.githubusercontent.com/9671082/229542130-19ce37fd-5e36-453c-aafb-458155961f17.png)

Figure 1- Attached and non-attacked records


##	RESULTS
The predictive performance of the decision tree and random forest models was evaluated using several metrics, including accuracy, precision, recall, F1 score, and ROC curve analysis. The models were also compared to each other and to a baseline model using these metrics. Based on the Logistic Regression ,Decision Tree Classifier, Random Forest Classifier and SVC the best mode was SVC.
	
 ![image](https://user-images.githubusercontent.com/9671082/229542401-b3891ba8-0662-42c1-a496-887a56e08075.png)

Figure 2- compare the score and errors by models

Furthermore, these findings can be visualized using a bar chart, as presented in Figure 5. The bar chart was constructed by plotting the accuracy score and mean absolute error on the Y-axis, while the classification models were displayed on the X-axis. The chart demonstrates that the SVM algorithm outperforms other algorithms in terms of accuracy, with a lower error rate than the other models.

 ![image](https://user-images.githubusercontent.com/9671082/229542587-a85d4b01-450f-4403-8d8d-cc853d35c91f.png)

Figure 3- depicting the results
