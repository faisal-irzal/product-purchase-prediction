# Machine Learning Model Deployment

This repository consists of documents required to deploy my ML model Web-App live via Heruko app. 

## The Model

Random Forest classifier is used to predict customer purchasing behavior. Model is built based on customer information i.e. age, gender and credit score. Target variable is classification of purchase (1) or not purchase (0). 

## The Pipeline

Scikit-learn library of Pipeline is used to ensure the machine learning workflow runs effectively. 

The model is trained and tested by using the available dataset. The accuracy of the model is received and recorded. The trained model is saved in the pipeline as "model.joblib".

## The Deployment

Web-App is created using Flask web development and the HTML templates as seen in folder "templates". Furthermore, the developed web-app is launched and deployed on Heruko platform. The web-app can be found via the following link:

https://purchase-pred-app.herokuapp.com


