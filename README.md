# Disaster Response Pipeline Project

Figure Eight has provided data related to messages, categorized into different classifications, that have been received during emergencies/disasters.

This project try to recognize these categories in order to cater for quicker responses to the emergency messages.

Using machine learning techniques, (Random Forest Classifier) we are able to predict the category with an accuracy of around XX %.

The process was carried out as follows:

###1. Data Processing
###2. Model training
###3. Prediction and Visualization



### Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://0.0.0.0:3001/

