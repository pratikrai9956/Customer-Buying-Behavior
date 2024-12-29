# Customer-Buying-Behavior Prediction Analysis
Customer Buying behavior of Airplane tickets on the basis of all the given facilities:
Starting with cleaning and making the data useful for analysis: Checking null and missing values.
Using "One-Hot Encoding" to assign binary value as: Customer will book the ticket: YES="1", Customer will not book the tickets: NO="0".
Using Pie Chart to understand the important variable and distribution of the data. 
Making Bar chart to know about highest booking from country-origin.
Chart of Booking status w.r.t. Sales_channel(How many tickets booked from different Platforms like:Mobile,Internet,other.
Number of booking w.r.t. to country. 
Countplot to count the booking per time(how many days before the customer booked the tickets).
Finding Correlation between the variable so that feature variable for the analysis does not be biased.
Splitting data into 70-30 for testing and training, Y:Dependent Variable=booking complete and X:other variables are independent.
# It is a classification problem to check weather the customer will book the tickets or not, so we will be using classification models for better result, models like: Logistics Regression, Random Forest, Decision Tree and XGBoost.
Using Confusion Matrix to check for correct predicted values.
XGBoost gives better accuracy with 85.2%
I applied cross-validation to check the accuracy and still XGBoost gives better result.
