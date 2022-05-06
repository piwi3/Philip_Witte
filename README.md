__Welcome!__ This page gives an __overview of my most recent and relevant projects__. Since I am in the middle of a data science bootcamp, this is still highly __work in progress__. I will further clean up the code and add more projects over the upcoming weeks/months.

## [1: Simualtion of customer movement in a supermarket with pygame and Markov chains](https://github.com/piwi3/timeseries_analysis_temperature)
- Used data of customer movement in a supermarket (timestamp, customer_no, lcoation) to derive a transition matrix, with probabilities for customers moving from one location to another (i.e. dairy, spices, fruit, drinks).
- Project had strong OOP focus, e.g., defined a customer class and a supermarket class to conduct a (first) "Markov Chain Monte Carlo"-simulation (MCMC)
- Leveraged pygame to visualize MCMC (inspired by this [great tutorial](https://www.youtube.com/watch?v=JtiK0DOeI4A&t=1512s)) - for this, further detailed the customer and supermarket classes (using class inheritance) and added a spot and grid class to control visual elements in pygame; simulation/visualization has been conducted with determined transition matrix and observed frequency of new customer arrivals

<img src="https://github.com/piwi3/Philip_Witte/blob/main/images/pygame_supermarket_simulation.gif?raw=true" width="450"><br/>
_Figure 1: A few seconds of the built supermarket simulation/visualization in pygame_
    
## [2: Prediction of survival on the titanic using ML classification models](https://github.com/piwi3/classification_with_titanic_data)
- Used Titanic data set from Kaggle to  built and compare a variety of ML classifiers with sckit-learn (logistic regression, decision trees, support vector machine, random forest, voting classifier), in order to predict survival of passengers on the titanic
- Project comprised all phases of ML work flow (e.g., train-test-splitting the data, data exploration, feature engineering (incl. pipelines), optimization of hyperparameters, evaluation via cross-validation) 
- Best classifier (voting classifier) is further tuned by optimizing predictions thresholds  

<img src="https://github.com/piwi3/Philip_Witte/blob/main/images/overview_ml_kpis_1.png?raw=true" width="500"><br/>
_Figure 2: Main KPIs for implemented ML classifiers_

## [3: Prediction of bike rentals using ML regression models](https://github.com/piwi3/prediction_of_bike_rentals)
- Build and trained regression models with sckit-learn on the Capital Bike Share (Washington, D.C.) Kaggle data set, in order to predict demand for bicycle rentals at any given hour, based on time and weather
- Project comprised all phases of ML work flow  (e.g., train-test-splitting the data, exploratory data analysis, iteratively optimizing the models by expanding or selecting features (using pipelines), regularizing models to avoid overfitting, evaluating models for train and test data based on RMSLE)
- Further tried to optimized models by, e.g., modeling bike shares for registered and casual bike shares separately 

<img src="https://github.com/piwi3/Philip_Witte/blob/main/images/rdf_2_model_approach.png?raw=true" width="450"><br/>
_Figure 3: Predicted vs. true target values for random forest model (separate models for registered vs. casual customers)_

## [4: Natural language processing of webscraped lyrics](https://github.com/piwi3/nlp_for_lyrics)
- bullet 1
- bullet 2
- bulelt 3

<img src="https://github.com/piwi3/Philip_Witte/blob/main/images/the_rolling_stones_wrdcld.png?raw=true" width="500"><br/>
_Figure 4: Tongue shaped word cloud of 100 most used words in lyrics for 'The Rolling Stones'_

## [5: Metabase dashboard from a postgreSQL DB using AWS (RDS/EC2)](https://github.com/piwi3/psql_and_dashboard_aws)
- bullet 1
- bullet 2
- bulelt 3

## [6: Sentiment analysis of twitter tweets via dockerized pipeline](https://github.com/piwi3/dockerized_twitter_app)
- bullet 1
- bullet 2
- bulelt 3

<img src="https://github.com/piwi3/Philip_Witte/blob/main/images/twitter_sentiment_app.png?raw=true" width="600"><br/>
_Figure 6: Frontend of my twitter sentiment app (created with streamlit)_

## [7: Time series analysis of temperature data](https://github.com/piwi3/supermarket_simulation)
- bullet 1
- bullet 2
- bulelt 3

<img src="https://github.com/piwi3/Philip_Witte/blob/main/images/prediction_2019.png?raw=true" width="450"><br/>
_Figure 7: In-sample prediction of temperature for Berlin via manually built model using linear regression for 2019_

## [8: Visualization of gapminder data through GIFs](https://github.com/piwi3/gap_minder_gif)
- Downloaded data from [gapminder](https://www.gapminder.org/data/) project (cool video re. gapminder [here](https://www.youtube.com/watch?v=jbkSRLYSojo&t=1s))
- Used pandas to structure and manipulate data (e.g., cumulating CO2 emissions per country over years)
- Visualized data through creation of GIFs using seaborn

<img src="https://github.com/piwi3/Philip_Witte/blob/main/images/gapminder_income_co2.gif?raw=true" width="400"><br/>
_Figure 8: CO2 vs. income over time (gapminder data)_<br/>

