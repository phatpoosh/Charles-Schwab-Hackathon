This problem is about how we try to incorporate external features which help in identifying the risk of the customers of the advisors. We have approached the problem by first identifying important features and building an AnalyticaL Dataset using Bank customer churn data along with portfolio, quetionnaire data and other metrics. 
Next we calculate the Risk Exposure Metric(REI) as the probability obtained from a classification problem. Here we implemented Random Forest and XGBoost( in order to deal with imbalanced nature of the dataset). Next we qualitatively identified the thresholds of the REI and created High,Medium and Low risk customers. In the High risk customers we carried out k-means clustering to identify 3 different clusters within the group to understand different customer segments.
We also have a questionnaire which feeds in feedback of the client and returns the risk profile and group of the client.
Using the customer groups identified we created suitable marketing campaigns on the behalf of Schwab and Advisors.
Finally, we have tableau dashboard which provides the advisor a view of their respective clients, their portfolios, essential metrics and Risk Exposure Index.

The following are the files:
Schwakathon.ipynb -> Jupyter notebook containing REI modelling
SCHW2.twb <- Tableau file
Churn_Modelling(1).csv <- Data for modelling
RandomForest_data.csv <- Data for Tableau
Sch-wakathon-TeamE.pdf <- Presentation