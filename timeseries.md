---
layout: page
title: Timeseries
permalink: /timeseries/
---

### Timeseries history of the number of COVID-19 cases and deaths by state

This post covers both log-scale and non-log-scale plots of the number of cases per state as a timeseries. These plots are **interactive** please hover and remove states as needed in the legend.

#### Log-scale
Below is a timeseries of the number of cases per state. The plots are shown on a log scale because there are many different magnitudes between the states. What is important to look at is the slope of these lines through time. A high slope indicate a high rate of cases while a low slope indicate a low rate of cases.

{% include log10_states_cumulative_cases_per_100k.html %}
{% include log10_states_cumulative_deaths_per_100k.html %}

In general it seems that the rate of New York cases and deaths seem to be decreasing, that may mean that the social distancing and shutdowns may be working. The other explanation is a reduced rate of testing.

#### Not log-scale
The log values may be less interpretable, but the non-log values are hard to compare as the number of cases and deaths are dwarfed by New York.

{% include states_cumulative_cases_per_100k.html %}
{% include states_cumulative_deaths_per_100k.html %}
