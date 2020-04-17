# Disaster Response Messages - Multi-class classifier

Prepare, analyze and visualize disaster data provided by figure8 to build a Machine Learning model that classifies disaster messages based on their content. 

This project was developed as part of Udacity Data Science Nanodegree.

To classify a message, the user can input text in the text-input slot and then press __Classify Message__. The classes that are assigned as most appropriate to the message will be highlighted in green.

![Search results page](figures/example.png)

## Installation Requirements

The project uses scikit-learn and nltk with Python 3.*.

## Data
The data (and code) can be accessed within the repository in the app/data. The two csv files were provided by figure8 in partnership with Udacity for the Data Science Nanodegree.
The overview of the used data can be seen in the bellow chart:

![Landing pange](figures/pie-chart-messages.png)


## Running the App

* Run the following commands in the project's root directory to set up a new database and model.

    * To run ETL pipeline that cleans data and stores in database:
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    * To run ML pipeline that trains classifier and saves it (a trained model is already available):
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl` 
* Run the following command in the app's directory to run your web app. 
    `python run.py`

* Go to http://0.0.0.0:3001/


## Results 

The results of the code are presented inline as plots. 
A brief discussion on the results can be found [here](https://medium.com/@mlacra/data-science-insights-2019-60e916d7e120?sk=370fcb0edf2fbb69b01b1f16ae31c89a).

## Licensing, Authors, Acknowledgements

Must give credit to [Kaggle](https://www.kaggle.com) for the data. 
You can find the Licensing for the data and other descriptive information at the respective websites. Otherwise, feel free to use the code here as you would like!