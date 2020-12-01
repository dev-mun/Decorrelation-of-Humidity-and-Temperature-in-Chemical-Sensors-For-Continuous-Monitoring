# Decorrelation-of-Humidity-and-Temperature-in-Chemical-Sensors-For-Continuous-Monitoring
____________________________________________________________________________________________________________________________________________
Motivation
____________________________________________________________________________________________________________________________________________

1. Chemical sensors are sensitive to humidity and temperature.
2. Cross-sensitivity challenges the task of identifying and quantification of violations in uncontrolled scenarios .
3. To build a model that predicts the changes in the sensor conductance as a function of humidity and temperature variations. 

____________________________________________________________________________________________________________________________________________
Model 
____________________________________________________________________________________________________________________________________________

1. Obtain gas sensor  data from a sensing device 
2. Preprocess the sensor data
3. Input the preprocessed data in to a machine learning model (Artificial Neural Network)
4. Receive predicted discrimination among banana, wine, baseline response as output from the machine learning model 

____________________________________________________________________________________________________________________________________________
Data Collection 
____________________________________________________________________________________________________________________________________________

1.Data has been obtained from UCI Machine Learning Repository 
2. Dataset has recordings of a gas sensor array composed of 8 MOX gas sensors, and a temperature and humidity sensor.
3. This sensor was exposed to background home activity while subject to two different stimuli: wine and banana

____________________________________________________________________________________________________________________________________________
Conclusion 
____________________________________________________________________________________________________________________________________________

We can confirmed that the most statistically significant factors are humidity changes and correlated changes of temperature and humidity
To show how the humidity–temperature correction model works for gas discrimination, we constructed a model for online discrimination among banana, wine and baseline response.
This shows that pattern recognition algorithms improve performance and reliability by including the filtered signal of the chemical sensors.
