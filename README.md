# Creating models with Python and Machine Learning to predict the evolution of COVID-19 in Brazil

## About

###### Project developed in response to the challenge of Digital Innovation One in order to build models in Python and Machine Learning to predict the evolution of COVID-19 in Brazil.

## Developer

[Natália Araújo](https://www.linkedin.com/in/nat%C3%A1lia-freitas-ara%C3%BAjo-25a00b140/ "Natália Araújo")

## Fount

- Data used : [https://covid.saude.gov.br/](https://covid.saude.gov.br/ "https://covid.saude.gov.br/")
- Training taken at DIO : [https://web.digitalinnovation.one/](https://web.digitalinnovation.one/ "https://web.digitalinnovation.one/")

## Used Libraries

- **re**
- **numpy**
- **pandas**
- **plotly**
- **matplotlib**
- **statsmodels**
- **pmdarima.arima**
- **fbprophet**

## Objectives

- Analyze the data from two perspectives: national and for the northern region of Brazil
- Find patterns in the data
- Build Python and Machine Learning models to predict the evolution of COVID-19

## Tasks Performed

1. Importing libraries and data

2. Normalization of data

	*The data used contains information from all brazilian cities, to perform an analysis only of the north region it was necessary to filter the data by region and group (summing up) the data by date.*
	
3. Plotting graphs

	a. confirmed cases
	
	b. new cases per day
	
	c. deaths by COVID-19
	
4. Average and daily growth rate calculations

5. Predictions

	a. trend
	
	b. seasonality
	
	c. noise
	
6. Modeling

	a. autoregressive integrated moving average (ARIMA) - **using the pmdarima package**
	
	b. growth model to predict turning point on the curve - **using the fbprophet package**

## Some of the generated graphics

###### predictions of confirmed cases in the northern region - using the pmdarima package
[![arimaNorth](https://i.imgur.com/5Y1pzK7.png "arimaNorth")](https://i.imgur.com/5Y1pzK7.png "arimaNorth")

###### predictions of confirmed cases in the northern region - using the fbprophet package
[![fbprophetNorth](https://i.imgur.com/KTjwfQi.png "fbprophetNorth")](https://i.imgur.com/KTjwfQi.png "fbprophetNorth")

###### predictions of confirmed cases in Brazil - using the pmdarima package
[![arimaBrazil](https://i.imgur.com/KPAmDul.png "arimaBrazil")](https://i.imgur.com/KPAmDul.png "arimaBrazil")

###### predictions of confirmed cases in Brazil - using the fbprophet package
[![fbprophetBrazil](https://i.imgur.com/Uy2TcfY.png "fbprophetBrazil")](https://i.imgur.com/Uy2TcfY.png "fbprophetBrazil")

