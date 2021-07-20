# Business-KPI-Forecasting-using-Time-Series-Analysis

Using Facebook's Prophet to implement a model to predict the following two KPIs:
Daily Sales Number: the total number of sales processed by a fictitious business on each day. I chose “sales” as KPI but you may have “orders” or “transactions” instead, depending on the type of products or services offered by your company. This metric has been selected for the forecast as it displays weekly, monthly and yearly seasonality and because other metrics can be derived from its prediction.
Daily Sales Value ($): the value in £ of the sales processed on each day, computed as Daily Sales Number * Average Price. This metric exhibits a very similar seasonality but cannot be accurately derived by predicting the first KPI. Also, the daily sales value could be used to derive the daily revenue ($) as well as to estimate the Average Sales Value (daily sales value ($)/daily sales number).

The focus is on how to put together an initial dataset, that will not only include the KPIs to be predicted, but also the date flags derived from business knowledge.
