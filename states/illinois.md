---
title: Illinois
layout: basic-page
---

<br>

Useful State Links
---

- [All About Redistricting -- Illinois](https://redistricting.lls.edu/state/illinois/?cycle=2020&level=Congress&startdate=)
- [538 -- Illinois](https://projects.fivethirtyeight.com/redistricting-2022-maps/illinois/)


Available Redistricting Plans
---

<br>

### US House

{% assign state_plans = site.plans | where: "state", "Illinois" | where: "body", "US House" | sort: "date" | reverse %}

{% for plan in state_plans %}
- [{{ plan.title }}]({{ plan.url }}), {{ plan.date | date_to_string }}
{% else %}
None at this time
{% endfor %}

### State Senate

{% assign state_plans = site.plans | where: "state", "Illinois" | where: "body", "State Senate" | sort: "date" | reverse %}

{% for plan in state_plans %}
- [{{ plan.title }}]({{ plan.url }}), {{ plan.date | date_to_string }}
{% else %}
None at this time
{% endfor %}


### State House

{% assign state_plans = site.plans | where: "state", "Illinois" | where: "body", "State House" | sort: "date" | reverse %}

{% for plan in state_plans %}
- [{{ plan.title }}]({{ plan.url }}), {{ plan.date | date_to_string }}
{% else %}
None at this time
{% endfor %}
