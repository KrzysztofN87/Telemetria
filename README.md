# Telemetria
The aim of the project is to obtain a viewership prediction for a television station schedule created for a period of about two months. An important element of forecasting will be the possibility of making possible program changes in order to improve the results to a satisfactory level.

Data for building the model consists of viewership results (Prog share - SHR and '000 avg - AMR/1000) for all titles played in the last 5 years for several commercial stations (competition + station ordering modeling). In the individual columns you can find the name of the TV station, broadcast day, broadcast start time, program name, Prog Share and average number of viewers per minute ('000 avg).

The object of interest are the average viewership results in given bands, e.g. in the hours of 9-12, 12-15, 15-18. Depending on the level of audience share in the market, better advertising conditions are possible for a given TV station.

For the purposes of the project, it is necessary to:
(a) clean up the data by deleting the items identified as "broadcast error" and the last row being a redundant summary and transforming the set in which broadcast hours 00 and 01 are replaced by hours 24 and 25 of the previous day.
b) determine the influence of specific characteristics (e.g. day of the week, band, title, station) on viewership.
c) determine what type of model will be able to both:
- use the trends and seasonality of viewership changes over the analyzed period and in the relevant program bands.
- use the dependence of viewership results on the titles played by the commissioning station.
- take advantage of the dependence of viewership results on the titles played by its direct competition.
d) prepare data for modeling in accordance with the inputs defined by the given model.
e) Present the prediction result for the last two months of the schedule in the form of graphs and metrics.
