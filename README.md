__Welcome!__ This page gives an overview of my __most recent and relevant projects__. Since I am in the middle of a __data science bootcamp__, this is still highly __work in progress__. I will further clean up the code and add more projects over the upcoming weeks/months.


## [1: Classification of (toy) dinosaurs using convolutional neural networks (CNNs)](https://github.com/piwi3/cnns_for_dino_detection)
- Generated __120 images__ of __4 different toy dinosaurs__ (plus 120 images for 'empty' & 'hand only' class) using a webcam and this [script](https://github.com/bonartm/imageclassifier)
- Built __i) a CNN from scratch__ using __TensorFlow and Keras__ (optimized the model using __SciKeras__ to do grid search) and built __ii) a CNN based on the mobilenet CNN__ using __transfer learning__ approach (further optimized generalization through image augmentation)  
- Customized the [script](https://github.com/bonartm/imageclassifier) used for image generation (based on __OpenCV__) to __live predict toy dinosaurs__ held into the camera

<img src="https://github.com/piwi3/Philip_Witte/blob/main/images/scrsht_%20prediction_engine.png?raw=true" width="450"><br/>
_Figure 1: Classification of dinosaurs using a webcam, Keras/TensorFlow and OpenCV_


## [2: Simulation of customer movement in a supermarket with pygame & Markov chains](https://github.com/piwi3/timeseries_analysis_temperature)
- Used __data of customer movement__ in a supermarket ('timestamp', 'customer_no', 'location') to derive a __transition matrix__, with probabilities for customers moving from one location to another (i.e. dairy, spices, fruit, drinks).
- Project had __strong OOP focus__, e.g., defined __customer and supermarket classes__ to conduct a (first) __"Markov Chain Monte Carlo"__-simulation (MCMC)
- Leveraged __pygame to visualize MCMC__ (inspired by this [great tutorial](https://www.youtube.com/watch?v=JtiK0DOeI4A&t=1512s)) - for this, further detailed the customer and supermarket classes (using class inheritance) and __added spot and grid classes to control visual elements in pygame__

<img src="https://github.com/piwi3/Philip_Witte/blob/main/images/pygame_supermarket_simulation.gif?raw=true" width="450"><br/>
_Figure 2: A few seconds of the built supermarket simulation/visualization in pygame_
    
    
## [3: Sentiment analysis of twitter tweets via dockerized pipeline](https://github.com/piwi3/dockerized_twitter_app)
- Leveraged __Tweepy__ and the __Twitter developer API__ to download tweets from twitter via __customized querries__ (e.g., tweet mentions user x, timeline of user y until date z, discard retweets etc.)
- Built a __data pipeline__ using __docker__ (more precisely __docker-compose__), i.e., stored all tweets in __Mongo DB__, created an __ETL job__ (data cleaning, preparation) transferring the data to __PostgreSQL__, ran a __sentiment analysis__ leveraging [Vader](https://github.com/cjhutto/vaderSentiment)  
- Finally built a small webpage with __streamlit__ to __display the results__ of a querry in realtime (also dockerized)

<img src="https://github.com/piwi3/Philip_Witte/blob/main/images/twitter_sentiment_app.png?raw=true" width="600"><br/>
_Figure 3: Frontend of my twitter sentiment app (created with streamlit)_


## [4: Prediction of survival on the Titanic using ML classification models](https://github.com/piwi3/classification_with_titanic_data)
- Used __Titanic data set from Kaggle__ to  built and compare a __variety of ML classifiers__ with __sckit-learn__ (logistic regression, decision trees, support vector machine, random forest, voting classifier), in order to predict survival of passengers on the titanic
- Project comprised __all phases of ML work flow__ (e.g., train-test-splitting the data, data exploration, feature engineering (incl. pipelines), optimization of hyperparameters, evaluation via cross-validation) 
- Best classifier (voting classifier) is further tuned by __optimizing predictions thresholds__  

<img src="https://github.com/piwi3/Philip_Witte/blob/main/images/overview_ml_kpis_1.png?raw=true" width="500"><br/>
_Figure 4: Main KPIs for implemented ML classifiers_


## [5: Prediction of bike rentals using ML regression models](https://github.com/piwi3/prediction_of_bike_rentals)
- Build and trained __regression models__ with __sckit-learn__ on the __Capital Bike Share (Washington, D.C.) Kaggle data set__, in order to predict __demand for bicycle rentals__ at any given hour, based on time and weather
- Project comprised __all phases of ML work flow__ (e.g., train-test-splitting the data, exploratory data analysis, iteratively optimizing the models by expanding or selecting features (using pipelines), regularizing models to avoid overfitting, evaluating models for train and test data based on RMSLE)
- Further tried to optimized models by, e.g., __modeling__ bike shares for __registered and casual bike shares separately__

<img src="https://github.com/piwi3/Philip_Witte/blob/main/images/rdf_2_model_approach.png?raw=true" width="450"><br/>
_Figure 5: Predicted vs. true target values for random forest model (separate models for registered vs. casual customers)_


## [6: Time series analysis of temperature data](https://github.com/piwi3/timeseries_analysis_temperature)
- Developed a __short-term temperature forecast__ utilizing the temperature data provided [here](www.ecad.eu)
- __Cleaned the data__ and performed a step-by-step time series analysis of the data, starting with a __base model__ using __linear regression to model trend and seasonality__
- Tested the __remainder for stationarity__, then built and evaluated __3 different AR models__, i.e. i) self-built __linear regression__ model, ii) __AR model__ iii) __ARIMA__ model

<img src="https://github.com/piwi3/Philip_Witte/blob/main/images/prediction_2019.png?raw=true" width="450"><br/>
_Figure 6: In-sample prediction of temperature for Berlin via manually built model using linear regression for 2019_


## [7: Natural language processing of webscraped lyrics](https://github.com/piwi3/nlp_for_lyrics)
- Built a __text classification model__ on __song lyrics__ with the goal to __predict an artist__ from a piece of text
- To train the model, __web scraped lyrics__ from 5+ artists from this [page](www.lyrics.com) using __Beautiful Soup__ and __regular expressions__
- Utilized __bag of words__ (and vectorization) as well as __Naive Bayes__ to implement a __classification model__ for the described task  
- As an __add-on__ (just for fun): wrote a simple __command line interface__ for downloading lyrics of any artist and creating a __fancy word cloud__

<img src="https://github.com/piwi3/Philip_Witte/blob/main/images/the_rolling_stones_wrdcld.png?raw=true" width="500"><br/>
_Figure 7: Tongue shaped word cloud of 100 most used words in lyrics for 'The Rolling Stones'_


## [8: Metabase dashboard from a PostgreSQL DB using AWS (RDS/EC2)](https://github.com/piwi3/psql_and_dashboard_aws)
- Fort this project, I utilized the __Northwind Database__, a sample database shipped along with Microsoft Access (data is about 'Northwind Traders', a fictional company and its regarding sales transactions) 
- Loaded the data into a __PostgreSQL DB__ using __AWS RDS__ and installed Metabase using __AWS EC2__; connected both to enable __data pipeline__
- __Querried the PostgreSQL__ DB to implement several __charts/dashboars visualizing the sales data__ (e.g. for orders, customers, including geo maps using fortium and geopy)

_Note:_
- _Since AWS is a paid service, I deleted the RDS instance; hence, the dashboard is offline. I am thinking to bring it back online using docker and the (still active) EC2 instance_
- _To run the code, a credentials.py file with personal AWS authentiffication keys needs to be added in the 'code'-folder_


## [9: Visualization of gapminder data through GIFs](https://github.com/piwi3/gap_minder_gif)
- Downloaded data from [__gapminder__](https://www.gapminder.org/data/) project (cool video re. gapminder [here](https://www.youtube.com/watch?v=jbkSRLYSojo&t=1s))
- Used __pandas to structure and manipulate data__ (e.g., cumulating CO2 emissions per country over years)
- __Visualized data__ through creation of __GIFs__ using __seaborn__

<img src="https://github.com/piwi3/Philip_Witte/blob/main/images/gapminder_income_co2.gif?raw=true" width="400"><br/>
_Figure 9: CO2 vs. income over time (gapminder data)_<br/>

