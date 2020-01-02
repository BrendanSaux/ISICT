Folder structure
├── models
|   ├── model1-33.cbm
|   ├── model2-33.cbm
|   ├── model3-33.cbm
|   ├── model4-33.cbm
|   └── model5-33.cbm
├── tweets_final.csv
├── hashtags.json
├── twitter_scraping.ipynb
├── data_analysis.ipynb
├── sklearn_logistic_regression.ipynb
├── catboost_classifier.ipynb
├── UI.ipynb
├── MICTDataAnalysis.xlsx
├── requirements.txt
├── ML_requirements.txt
└── README.txt 

models: folder containing a set of 5 binary CatBoost models that are averaged. Models are used for the UI.
tweets_final.csv: document containing all tweet data (created by twitter_scraping.ipynb)
hashtags.json: document containing trending hashtags per date (created by twitter_scraping.ipynb)
twitter_scraping.ipynb: notebook to download tweets from twitter
data_analysis.ipynb: simple data analysis notebook for correlations and bar graphs
sklearn_logistic_regression.ipynb: notebook training simple sklearn machine learning model as illustration
catboost_classifier.ipynb: notebook training main machine learning model
UI.ipynb: notebook containing a demo file, input data and submit to obtain tweet quality
MICTDataAnalysis.xlsx: Microsoft Excel sheet with data analysis
requirements.txt: requirements to run all the code (can be installed via pip or conda)
ML_requirements.txt: requirements if you only want to run the machine learning models (can be installed via pip or conda)
