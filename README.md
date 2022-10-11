# Client Subscription Predictions Using Logistic Regression Model
A machine learning project designed for the Western Governors University Capstone Course! This project was an application developed for a fictional company to solve a business problem using a machine learning solution.

Application is accessible through the following link:
https://mybinder.org/v2/gh/DClark404/WGU-Capstone/main?labpath=Bank%20Client%20Prediction%20Application.ipynb

  WGCU is a credit union that will soon begin a marketing campaign for long-term deposit subscriptions. The organization has commissioned the development of a proprietary machine learning solution to help target marketing toward clients that are more likely to subscribe to this deposit.
  
  The application processes company CSV files and transforms it into data that is useful for the machine learning algorithm. Processed data is then fitted to a logistic regression model that has been tuned for the highest possible accuracy using the recall score. The model is capable of correctly identifying 76% of clients that will subscribe to the long-term deposit. This metric is appropriate for the project as the organization’s goal is to identify as many subscribing clients as possible to increase revenue. 
  
  The application is written in python and hosted within a jupyter notebook. The application includes interactive widgets that allow the company to upload new data files and generate predictions. This project utilizes the Scikit-Learn, NumPy, Pandas, Matplotlib, Seaborn, and ipywidgets libraries. Exact library versions are listed within the requirements.txt file.
  
  The dataset used for this project is hosted on Kaggle at the following link:
  https://www.kaggle.com/datasets/rashmiranu/banking-dataset-classification?select=new_train.csv
