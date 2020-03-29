---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: Home
layout: home
---

# COVID-19 Cases and Deaths Visualizations
This repository and website is dedicated to providing visualizations of the number of cases and deaths by state and county. This website uses a variety of maps, timeseries plots, and tables to provide information to the general public. The data from this repository is updated daily based on the [New York Times county and state COVID-19 open data](https://github.com/nytimes/covid-19-data). It is extremely important at this time that data be open to the public, so crowd sourced effort can help. Many thanks goes out to the New York Times for providing their data on GitHub.

The plots on this website are **interactive**, so please hover of the plots and maps and turn off legend items to isolate the data of most interest to you.

## USA Summary

Current data table for the U.S.

{% include current_us_table.html %}

Below find the number of cases per 100,000 people by state and the cumulative cases and deaths in both absolute and log scale.

## Cases and deaths per 100,000 people

{% include cases_per_100k_by_state.html %}
{% include deaths_per_100k_by_state.html %}

## Cumulative cases and deaths

{% include usa_cumulative_cases_deaths.html %}
{% include log10_usa_cumulative_cases_deaths.html %}

## State Data Table
{% include current_state_table.html %}