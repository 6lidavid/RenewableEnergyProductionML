# Project GOOSE: Renewable Energy Production Based off of the Weather
by Sammy Almawaldi, David Li, and Eli Zhu

## Concept
Build a model that will predict viability of renewable energy sources based on the climate and weather of a given area. 

## Project Abstract
As we enter the 3rd decade of the 21st Century, it has become increasingly clear that our current methods of producing energy are not adequate to address the concerns of climate change. The current solution to this problem is to retire the use of fossil fuels and begin to rely more on renewable energy sources such as solar and wind power. However, renewable energy is dependent on the weather of the day and the overall climate of the area or country. The objective is to create a machine learning model to determine how much energy will be produced based on weather and climate.
To start with, a data set from the Open Power System Data will be used. It contains two data sets: energy production metrics for over 37 European countries and weather data such as direct radiation, diffused radiation, temperature, and wind speed. The data sets are separate so part of our task will be to combine the two datasets.
There is a medium.com article doing the same task but the scope of that project is much lesser. The author is only looking at the data for Germany specifically and the result is just a trained model. Where this project will differ is that the model will be trained on a larger amount of data and will be used to directly predict the energy production of another location. The value of training the model with fewer features means that we need fewer features to predict once the model has been trained. The goal is to train a linear regression model given the energy production and weather data acquired and use the model to predict the energy production of any location because weather data is commonly available.

## Repo Need To Knows
1. There are two branches: master and develop. All work is in develop and develop only
2. The data is too large for git so it is on Google drive: https://drive.google.com/drive/folders/1slL2Asn36snNvkyWS1fMbQPpTwfQLbzN?usp=sharing
3. The notebooks that are in the top level of the repo are the ones we mention throughout the report. There is another folder called NonFinalWorkAndExperimentation. This holds many notebooks that we have work in where we experiment with ideas but nothing significant came out of it and decided not to include it in the report because of it. But, if you are curious in what we might have played around with, it is in those notebooks.
