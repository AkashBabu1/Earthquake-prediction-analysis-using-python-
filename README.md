# Earthquake-prediction-analysis-using-python-
Instructions to run the projectRequirements

1.click==7.1.2

2.Flask==1.1.2

3.gunicorn==20.0.4

4.itsdangerous==1.1.0

5.Jinja2==2.11.2

6.joblib==0.16.0

7.MarkupSafe==1.1.1

8.numpy==1.19.1

9.pandas==1.1.0

10.python-dateutil==2.8.1

11.pytz==2020.1

12.scikit-learn==0.23.1

13.scipy==1.5.2

14.six==1.15.0

15.sklearn==0.0

16.SQLAlchemy==1.3.18

17.threadpoolctl==2.1.0

18.Werkzeug==1.0.1

19.xgboost==1.1.1

20.python3.x

Note for windows user : install gitbash and proceed with same instruction as linux.

step 1 : $ git clone https://github.com/Dineshvvelu/EARTHQUAKE-PREDICTION-MODEL-USING-PYTHON/edit/main/README.md

step 2 : $ cd Realtime-Earthquake-forecasting

step 3 : $ python3 -m venv <> (If error occurs, download virtual environment for python)

step 4 : $ source <>/bin/activate

step 5 : $ pip install --upgrade pip

step 6 : $ pip install -r requirements.txt (If error occurs in xgboost installation, upgrade pip using step 5)

step 7 : Run application with $ python application.py i.e in root directory of project repo.

step 8 : Go to local host when application starts and use slider to choose dates for prediction in app.

Dataset:

Real time data that updates every minute on https://www.kaggle.com/datasets/usgs/earthquake-database. Below is the feature description of the dataset with 22 features and 14150 samples at the time of training.

time ---------------------- Time when the event occurred. Times are reported in milliseconds since the epoch

latitude ------------------- Decimal degrees latitude. Negative values for southern latitudes.

longitude ------------------ Decimal degrees longitude. Negative values for western longitudes.

depth ---------------------- Depth of the event in kilometers.

depthError ------------------ The depth error, three principal errors on a vertical line.

type ------------------------ Type of seismic event.

mag ------------------------ Magnitude of event occured.

magType -------------------- The method or algorithm used to calculate the preferred magnitude

Project Overview:

Countless dollars and entire scientific careers have been dedicated to predicting where and when the next big earthquake will strike. But unlike weather forecasting, which has significantly improved with the use of better satellites and more powerful mathematical models, earthquake prediction has been marred by repeated failure due to highly uncertain conditions of earth and its surroundings. Now, with the help of artificial intelligence, a growing number of scientists say changes in the way they can analyze massive amounts of seismic data can help them better understand earthquakes, anticipate how they will behave, and provide quicker and more accurate early warnings. This helps in hazzard assessments for many builders and real estate business for infrastructure planning from business perspective. Also many lives can be saved through early warning. This project aims a simple solution to above problem by predicting or forecasting likely places to have earthquake in next 7 days. For user-friendly part, this project has a web application that extracts live data updated every minute by USGS.gov and predicts next likely place world wide to get hit by an earthquake, hence a realtime solution is provided.
