---
layout: page
title: State Maps
permalink: /state_maps/
---

# Coronavirus and cases and deaths by state

Below are the number of cases and the number of deaths per state. The number of cases map below is log base 10. There are orders of magnitude differences between states, so log was used to show the difference. A value of 3 represents 1,000, and a value of 4 represents a value of 10,000.

{% include cases_by_state.html %}
{% include deaths_by_state.html %}

# Coronavirus cases and deaths per 100,000 people

The above maps can be misleading. The large number of cases are often at population centers. Looking at the number of cases per 100,000 people is a more relative metric that shows how a state is impacted relative to its population.

{% include cases_per_100k_by_state.html %}
{% include deaths_per_100k_by_state.html %}