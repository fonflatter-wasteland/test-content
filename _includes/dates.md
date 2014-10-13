# extract current month and year from site build time and convert them to number type
{% assign current_month = site.time | date: "%m" | times: 1 %}
{% assign current_year = site.time | date: "%Y" | times: 1 %}
