__Welcome!__ This page gives an __overview of my most recent and relevant projects__. Since I am in the middle of a data science bootcamp, this is still highly __work in progress__. I will further clean up the code and add more projects over the upcoming weeks/months.

## [1: Simulation of customer movement in a supermarket with pygame & Markov chains](https://github.com/piwi3/timeseries_analysis_temperature)
- Used __data of customer movement__ in a supermarket (timestamp, customer_no, lcoation) to derive a __transition matrix__, with probabilities for customers moving from one location to another (i.e. dairy, spices, fruit, drinks).
- Project had __strong OOP focus__, e.g., defined __customer and supermarket classes__ to conduct a (first) __"Markov Chain Monte Carlo"__-simulation (MCMC)
- Leveraged __pygame to visualize MCMC__ (inspired by this [great tutorial](https://www.youtube.com/watch?v=JtiK0DOeI4A&t=1512s)) - for this, further detailed the customer and supermarket classes (using class inheritance) and __added spot and grid classes to control visual elements in pygame__

<img src="https://github.com/piwi3/Philip_Witte/blob/main/images/pygame_supermarket_simulation.gif?raw=true" width="450"><br/>
_Figure 1: A few seconds of the built supermarket simulation/visualization in pygame_
    
## [2: Prediction of survival on the titanic using ML classification models](https://github.com/piwi3/classification_with_titanic_data)
- Used __Titanic data set from Kaggle__ to  built and compare a __variety of ML classifiers__ with __sckit-learn__ (logistic regression, decision trees, support vector machine, random forest, voting classifier), in order to predict survival of passengers on the titanic
- Project comprised __all phases of ML work flow__ (e.g., train-test-splitting the data, data exploration, feature engineering (incl. pipelines), optimization of hyperparameters, evaluation via cross-validation) 
- Best classifier (voting classifier) is further tuned by __optimizing predictions thresholds__  

<img src="https://github.com/piwi3/Philip_Witte/blob/main/images/overview_ml_kpis_1.png?raw=true" width="500"><br/>
_Figure 2: Main KPIs for implemented ML classifiers_

## [3: Prediction of bike rentals using ML regression models](https://github.com/piwi3/prediction_of_bike_rentals)
- Build and trained __regression models__ with __sckit-learn__ on the __Capital Bike Share (Washington, D.C.) Kaggle data set__, in order to predict __demand for bicycle rentals__ at any given hour, based on time and weather
- Project comprised __all phases of ML work flow__ (e.g., train-test-splitting the data, exploratory data analysis, iteratively optimizing the models by expanding or selecting features (using pipelines), regularizing models to avoid overfitting, evaluating models for train and test data based on RMSLE)
- Further tried to optimized models by, e.g., __modeling__ bike shares for __registered and casual bike shares separately__

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
- Downloaded data from [__gapminder__](https://www.gapminder.org/data/) project (cool video re. gapminder [here](https://www.youtube.com/watch?v=jbkSRLYSojo&t=1s))
- Used __pandas to structure and manipulate data__ (e.g., cumulating CO2 emissions per country over years)
- __Visualized data__ through creation of __GIFs__ using __seaborn__

<img src="https://github.com/piwi3/Philip_Witte/blob/main/images/gapminder_income_co2.gif?raw=true" width="400"><br/>
_Figure 8: CO2 vs. income over time (gapminder data)_<br/>

