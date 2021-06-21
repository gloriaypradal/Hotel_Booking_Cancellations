# Hotel Bokkings
When Are going to be cancelled?


I chose a data set available in Kaggle, the data set contains booking information for a city hotel and for a resort hotel and includes guest data and details like, day, month, year of arrival, number of children and babies, number of special requests made by the guests, length of the stay and some others. The data correspond to the years 2015 to 2017. Hotel booking cancellations always has been an issue specially in busy season, sometimes people want to have vacation in some hotels, and when we call, is not possible to make reservations because the hotel is already booked, but what happened when those booking that are made some days ahead gets canceled? The hotel loses potential clients and money because it might not find another guest to fill that canceled room


The features of interest that I chose to start are:

•	'arrival_date_month',
•	'children',
•	'is_repeated_guest'
•	'lead_time',
•	'deposit_type'
•	'hotel'

Models tested:

Random Forest Classifier
Logistic Regression
K-Nearest N



In conclusion model selected is the Random Forest model, this model presented better perfor-mance with better values of precision, recall and F1 for both classes and the AUC value of 0.89 what is higher than the models used before. Even that the Random forest present a lower precision, in general all metrics were better with Random Forest Classifier. Also the True Positive (9872) for Random Forest is better than the 2 model before
