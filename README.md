# Reconstruction of temperature's time-series based on multiple linear regression model
This project proposes a multiple linear regression model for the reconstruction of historical time-series of local air temperature in Oslo (Norway). In comparison with previous studies, the methodology suggests to include large scale predictors to estimate hourly local temperature. The model is trained from weather observations spread over Norwegian stations, to infer a regression function and predict local air temperature in Oslo 1-day ahead. The foremost objective of this preliminary study is to develop a data-driven model able to reconstruct historical time-series of air temperature at an hourly time resolution with few input information needed, essentially at times and places where data are missing. An analysis of main predictors explaining the most variance in the response is assessed, thus allowing to identify key meteorological variables that govern seasonal atmospheric circulation in Oslo. Statistical scores are computed to estimate prediction's accuracy of the model and build the "best" one. Based on residuals analysis and scores, a multi-linear model applied to a more general weather forecasting system as well as paths of improvements are discussed.
