

# `{{ project().name }}`
Summary report for project `{{ project().name }}`. Generated using [**`BGCFlow v{{ project().bgcflow_version}}`**](https://github.com/NBChub/bgcflow){:target="_blank"}

## Project Description
- {{ project().description }}
- Sample size **{{ project().sample_size }}**


## Available reports
| BGCFlow_rules                                     | description                                                                                     |
|:--------------------------------------------------|:------------------------------------------------------------------------------------------------|
| [seqfu](seqfu/){.md-button}                       | Calculate sequence statistics using SeqFu.                                                      |
| [mash](mash/){.md-button}                         | Calculate distance estimation for all samples using MinHash.                                    |
| [fastani](fastani/){.md-button}                   | Do pairwise Average Nucleotide Identity (ANI) calculation across all samples.                   |
| [antismash](antismash/){.md-button}               | Summarizes antiSMASH result.                                                                    |
| [bigscape](bigscape/){.md-button}                 | Cluster BGCs using BiG-SCAPE                                                                    |
| [bigslice](bigslice/){.md-button}                 | Cluster BGCs using BiG-SLiCE (https://github.com/medema-group/bigslice)                         |
| [automlst-wrapper](automlst-wrapper/){.md-button} | Simplified Tree building using autoMLST (https://github.com/NBChub/automlst-simplified-wrapper) |


## References
<font size="2">
{% for i in project().references %}
  - *{{ i }}*
{% endfor %}
</font>
