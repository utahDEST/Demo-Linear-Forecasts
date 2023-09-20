# Demo-Linear-Forecasts

Prepping and displaying the linear forecasting in this repository is done in three separate jupyter notebooks:

1. Read historic estimated AADT from UDOT
2. Fit a line through the AADT using ordinary least squares regression and extend line into the future
3. Create interactive chart to visualize the data

All the data necessary for these notebooks is included in this repository. You may need to install additional libraries, such as plotly and ipywidgets, for the charts in the last notebook to function. The linear regression model is from scikit-learn: https://scikit-learn.org/stable/modules/linear_model.html.

Additionally, a fourth notebook was added to compare linear forecast with forecasts being prepared for the 2023 RTP using the travel demand model. This notebook relies mainly on matplotlib for charts.
