# bikes_mlr
> Building a Multiple Linear Regression model for bike-sharing company to predict. Company is sharing pre-covid 2018,2019 data and trying to understand the demand after covoid.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- In this project, we are trying to build a MLR model to prediict demand for bike sharing company, We are using RFE to find the top 15 variable and then will refine the model based on the p-value, VIF etc 
- US Bike sharing company has suffered dip in their revenue due to ongoing Corona pandemic and company is trying to understand the demand post Pandemic.
- Project bike sharing demand post covid based on Pre-covid data 
- Data set contain 2018,2019 daily bike sharing count, weather condition, holiday, weekday, season, tempature etc

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 : model Independent variable are temp, workingday, windspeed, 2019 yr, Saturday, summer &  Winter season , 
 (Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist) and (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds) Weather condition, 
 Sep month
- Conclusion 2 R-squared:	0.835, Adj. R-squared:	0.832 & R2_Score is 0.796
- Conclusion 3 Residual plot is following binomial distribution
- Conclusion 4 VIF is less than 5 
- Conclusion 5 p-value is 0 for all indipedent variable
- Conclusion 6 Prob (F-statistic) is close to zero

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

- Pandas - version 	 1.0.5
- Numpy - version 	 1.18.5
- Matplotlib - version 	 3.2.2
- Seaborn - version 	 0.10.1
- Sklearn - version 	 0.23.1
- Statsmodels - version 	 0.11.1


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements


## Contact
Created by [@sanngh] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->