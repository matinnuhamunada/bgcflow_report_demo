# MASH
Summary of [MASH](https://github.com/marbl/Mash) results from project: [{{ project().name }}] 

## Description
Fast genome and metagenome distance estimation using MinHash

## References
{% for i in project().rule_used['mash']['references'] %}
  - *{{ i }}*
{% endfor %}
