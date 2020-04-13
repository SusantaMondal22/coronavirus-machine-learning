<div align=left><img width="379" height="114.9" src="https://i.ibb.co/fkQvQfM/logo-prediction.png"/></div>

UK Corona Virus Prediction
===========================
This project intends to implement the data of confirmed Corona Virus cases and predict the future trend of the epidemic in the United Kingdom and beyond.
### Website

https://covid19uk.live/

<div align=center><img width="420" height="238" src="https://github.com/lamharrison/coronavirus-machine-learning/blob/master/img/header.jpeg"/></div>

|Author|E-mail|Github
|----|---|---
|Big Tree|lamharrison123@gmail.com|https://github.com/lamharrison
|Jimmy Lu|lujiammy@outlook.com|https://github.com/lujiammy

## Feature
- [x] Implementing MLP models and constructing appropriate underlying functions.
- [x] Extracting data from trustworthy data sources.
- [x] Using real-time data to predict the epidemic trend within the UK.
- [x] Predicting the epidemic trend of other similar-sized European countries including Italy, Germany and France.
- [x] Using prediction results from other similar-sized European countries to update the pattern that we have previously predicted within the UK.
- [x] Plotting the result regarding real confirmed cases and our predicting trends into the chart.
  
## Design
This prediction problem set a perfect usage scenario for Transfer learning (TL) which is one of the Machine Learning domain and could gain updated knowledge through the process when solving one problem and applying it to a different but related problem. Thus this project has been divided into two part: analysing the data for the UK and all similar-sized countries; refining the model based on the prediction result.

<div align=center><img width="463" height="320" src="https://github.com/lamharrison/coronavirus-machine-learning/blob/master/img/transfer%20learning.jpeg"/> <img width="350" height="320" src="https://github.com/lamharrison/coronavirus-machine-learning/blob/master/img/transfer%20learning%20-%20NN.png"/>
</div>

## Model
This project basically applied the Multilayer Perceptron (MLP) model for analysing data. MLP is also known as one of Artificial Neural Networks(ANN) and could utilise Backpropagation to train the model between different nodes. The activation functions of nodes define the output of nodes given an input or set of inputs.

<div align=center><img width="574" height="378" src="https://github.com/lamharrison/coronavirus-machine-learning/blob/master/img/%20MLP.png"/></div>

We have primarily considered activation functions as sigmoid functions that almost perfectly represent the characteristics of the number of people who have been infected by the Corona Virus in the UK. We also used other activation functions like ReLU and linear functions for improving the precision.
<div align=center><img src="https://github.com/lamharrison/coronavirus-machine-learning/blob/master/img/activation%20functions.png"/></div>

## Sample Prediction
To better demostrate the our project objective, one of the sample predictions has been attatched below.


<div align=center><img width="560" height="400" src="https://github.com/lamharrison/coronavirus-machine-learning/blob/master/uk_model_7_days.png"/></div>

As the uncertainty of the epidemic remains high, the 7-day prediction would be recommended for using this prediction model. We would also constantly refine our model striving for better result.

## Data Source
The trustworthy data sources are always overwhelmingly essential to ensure the authenticity of reaching the prediction objective. We have collaborated with Jeff (https://isjeff.com/home) who provided us with valuable data for Corona Virus within the UK and other European countries based on the government statistical result. Thanks for his help!

 To find more information about our data sources, the attached link as follows could be friendly visited. 

Global data: https://github.com/isjeffcom/coronavirusDataGlobal    
UK data: https://github.com/isjeffcom/coronvirusFigureUK

![data](https://github.com/lamharrison/coronavirus-machine-learning/blob/master/img/london%20visual.png)

