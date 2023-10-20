# MedellinPollutantsTS
Repository with time series data from the [SIATA (Sistema de Alerta Temprana de Medellín y el Valle de Aburrá)](https://siata.gov.co/) for some criteria pollutants in Colombia.

The $PM_{2.5}$ and $PM_{10}$ series are created by taking the daily average by station and then the maximum for all of them while for the $O_3$ series the daily maximum and then the maximum for all stations is taken. 

On the other hand, the $PM_{2.5}$ is approximately distributed as $log-normal(\mu, \sigma)$ as was studied by [Rumburg et al. (2001)](https://doi.org/10.1016/S1352-2310(00)00554-9) and as per empirical tests carried out using the [fitdistrplus](https://doi.org/10.18637/jss.v064.i04) package in [R](https://www.r-project.org/).
