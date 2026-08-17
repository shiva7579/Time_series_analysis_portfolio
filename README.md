# Time_series_analysis_portfolio
1. Sunspot forecasting by AR(2) model
[Click here](https://nbviewer.org/github/shiva7579/Time_series_analysis_portfolio/blob/main/1_Sunspot_Forecasting_AR/Sunspot.ipynb)

2. Yule-walker algorithm vs Burgs algorithm<br>
This projects is about comparing the parametric spectral estimation across varying sample size. Both algorithms are coded manually from strach using linear algebra and matix mechanics.A custom biased autocorrelation loop was mapped into a symmetric Toeplitz matrix equation to solve the Yule-Walker parameters, while a stage-by-stage lattice filter recursion loop was programmed to extract Burg's reflection coefficients by natively minimizing forward and backward prediction errors.<br>

3. Hannan-Rissanen algorithm<br>
[click here]()
Hannan-Rissanen is non-expensive alogorithm with a two-step OLS approach, enabling closed-form estimation and rapid model order grid screening for mixed ARMA models.
It may replace computationally expensive non-linear MLE model. In this project, We plotted coefficients of ARMA model of different order and plotted the obtained coefficients with respect to sample size.
