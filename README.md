<h1 align="center">
  <br>
  <a href="https://github.com/fparisio/DataScience">
  <br>
</h1>


<h4 align="center">Data Science and Machine Learning Projects, <a href="https://www.linkedin.com/in/francesco-parisio-b1b53844/" target="blank"> by Francesco Parisio</a></h4>

<p align="center">
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg"
         alt="GitHub License">
  </a>
</p>

### About

The repository contains a series of data science and machine learning projects that I carried out for training, academic and applied research purposes. The content is divided into subcategories and each project is implemented as either *[jupyter notebook](https://jupyter.org/)* or a *[python](https://www.python.org/)* script.

### Content

I have divided the projects into macro-categories based on the typology of the problem at hand.

---
#### *[Time series analysis: forecasting CO<sub>2</sub> emissions](https://github.com/fparisio/DataScience/tree/main/TimeSeriesCO2ForecastNatGas)*

**TL; DR**: The project forecasts a 1 year horizon of CO<sub>2</sub> emissions stemming from natural gas based electricity production in the United States. Through an optimized and cross-validated SARIMAX model, I predict a 6.7% increase of emitted CO<sub>2</sub> in the 1 year horizon with an uncertainty of 90%.

**Executive Summary**: Precise and accurate forecasts of CO<sub>2</sub> emissions can help policy makers devise strategies and measure their effects in reducing emissions to meet the climate targets. Collected past data can be employed to analyze the problem and data science methods can be used to make forecasts. I analyzed existing data from U.S. Energy Information Administration on CO<sub>2</sub> emissions from electricity production per-source. After introducing descriptive statistics and a preliminary data analysis, I propose to analyze CO<sub>2</sub> emissions from the largest growing source in electricity production: natural gas. I compare different algorithms (AR, MA, ARMA, ARIMA, SARIMAX) optimized to build a reliable 1 year forecasting model of the nonstationary data. I applied rolling split Monte Carlo cross-validation to evaluate the forecast accuracy. The optimized SARIMAX model is the best solution that strikes a balance between forecast precision and model complexity. The Symmetric Mean Absolute Percentage Error (SMAPE) on testing data is below 3%. The cross-validation provides a quantification of uncertainty in the forecast, showing an (expected) increasing average error with increasing time horizon of the forecast. The average error remains below 11% and roughly 75% of the forecasts are likely to have a SMAPE&lt;15%–a proof of the model’s reliability and robustness. The optimized SARIMAX model forecasts CO<sub>2</sub> emissions with a high precision. The forecast shows an increase in CO<sub>2</sub> emissions from natural gas in the coming 12 months that can serve as a basis case to measure policy effects. Future studies should consider multivariate time series analysis that includes relevant indicators of CO<sub>2</sub> emissions (e.g., energy demand, natural gas prices, carbon-bonds prices).

**Skills**: Python, Statsmodels, Pandas, Numpy, Matplotlib, Itertools, Tqdm, Scipy, Seaborn, SARIMAX, Time Series Analysis, Rolling-split Validation,  Monte Carlo Simulations.

<p align="center">
<img src="Images/past_10_y.png" alt="Training" width="300"/>
<img src="Images/SARIMAX_Optim.png" alt="Validation" width="300"/>
</p>

---
#### *[Recommendation systems: build a RS for Amazon products](https://github.com/fparisio/DataScience/tree/main/RecommendationSystem)*

**TL; DR**: The project goal is to recommend the best amazon products available to the users by using some recommendation systems techniques.

**Executive Summary**: TBW

**Skills**: Python, Collections, Surprise, Scikit-leanr, Pandas, Numpy, Matplotlib, Recommendation Systems, SVD.

<p align="center">
<img src="Images/Rec_Sys.png" alt="erros" width="500"/>
</p>
