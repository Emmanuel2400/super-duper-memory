# Title: A predictive model for climate change in the state of Oklahoma using Python
Abstract:
Motivated by major challenges arising from the rapid change in the climate behavior around the world, the goal of this research project is to develop a predictive model for understanding the climate change in the state of Oklahoma using a common programming language called python. To this end, we study the last fifty years of historic climate data in the state of Oklahoma collected by the National Oceanic and Atmospheric Administration. To build a robust predictive model, we first need to clean the data to minimize the errors in them such as some missing dates then; we consider three main forecasting models, including the moving average scheme, the standard exponential smoothing, and Holt-Winters exponential smoothing. After implementing preliminary data cleaning and data preparation steps, we train each of the three models to tune their parameters. In the next step, we validate the best model within each category on the climate data of the recent few years. It was shown that the Holt-Winters model fits the Oklahoma climate data the best. This finding is further utilized to forecast the change of climate in Oklahoma in next few years. In addition to the developed predictive model, implementing a decomposition scheme, we discover that the average monthly temperature in Oklahoma has been consistently decreasing in the past few decades, particularly, in the 90s. This also proved that global warming was not the correct terminology to describe the change in the Oklahoma’s climate. This research project is supported by Oklahoma Louis Stokes Alliance for Minority Participation (OK-LSAMP), conducted by the two undergraduate research scholars, Emmanuel Akinwale and Courtney Williams, and under the supervision of Dr. Farzad Yousefian a faculty member at the School of Industrial Engineering and Management in Oklahoma State University.

Motivation:
The scholars wanted to predict the future weather. In order to do so, the two had to understand the past in order to predict the future.

Data Source:
NOAA website: https://www.noaaclimate.gov/
The data spans the information about the weather in Oklahoma between the years
from 1969 to 2019 

Methodology:
Data Preparation
Visualization and Time series Decomposition
Training the model----- using MA, ES and HW-ES forecasting methods
Testing the model
Forecasting using the best model
