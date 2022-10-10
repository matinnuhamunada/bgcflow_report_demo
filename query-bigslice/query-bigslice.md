# BiG-FAM Query
Summary of [BiG-FAM Query](https://bigfam.bioinformatics.nl/home) results from project: [{{ project().name }}] 

## Description
Query against 1.2 Million BGCs in the BiG-FAM database using BiG-SLICE

## References
{% for i in project().rule_used['query-bigslice']['references'] %}
  - *{{ i }}*
{% endfor %}
