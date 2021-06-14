---
layout: page
title: ツール(ja)
permalink: /tools_ja/
---

## Literate Computing tools
Literate Computing Tools are our enhancements to Jupyter for achieving the following goals:
- Giving awareness where you are; the cells are colored depending on their statuses. You can see how an operation is in progress and whether it has been succeeded. Light Cyan, Linen, and Pink represent “running”, “finished successfully” and “finished with errors” respectively.
- Preventing miss-operation; once a cell has been executed, it “freezes” against unintended execution. Frozen cells will not be executed nor edited until those will be unfrozen.
- A good operational outlook; as an enhancement for collapsible headings, collapsed code cells underneath are represented as bricks. The number of bricks represents operational complexities. Plus, you can run through whole bricks (collapsed code cells) with one click as a routine procedure. Color changes of bricks also represent the progress.
- Assure traceability; infrastructure operation can generate massive output lines. LC_wrapper kernel summarizes output lines, and simultaneously all original output lines are saved into an individual file with a timestamp at each execution. You can investigate the total output and compare it with previous results for reviewing.


## Try the Demo

You can start the Notebook server on port 8888 with the following command.

```
docker run -it --rm -p 8888:8888 niicloudoperation/notebook:latest
```

<a class="github-button" href="https://github.com/NII-cloud-operation/Jupyter-LC_docker" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>

You can login the Notebook server with the authentication token in the startup message.

## Jupyter Extensions

[LC_run_through Extension](https://github.com/NII-cloud-operation/Jupyter-LC_run_through)
<a class="github-button" href="https://github.com/NII-cloud-operation/Jupyter-LC_run_through" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>

{% include youtube.html id='pkzE_nwtEKQ' %}

[LC_wrapper Kernel](https://github.com/NII-cloud-operation/Jupyter-LC_wrapper)
<a class="github-button" href="https://github.com/NII-cloud-operation/Jupyter-LC_wrapper" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>

{% include youtube.html id='-28XG7aHYY8' %}

## Other Extensions

- [multi_outputs](https://github.com/NII-cloud-operation/Jupyter-multi_outputs)
<a class="github-button" href="https://github.com/NII-cloud-operation/Jupyter-multi_outputs" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>
- [nblineage](https://github.com/NII-cloud-operation/Jupyter-LC_nblineage)
<a class="github-button" href="https://github.com/NII-cloud-operation/Jupyter-LC_nblineage" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>
- [Jupyter-LC_index](https://github.com/NII-cloud-operation/Jupyter-LC_index)
<a class="github-button" href="https://github.com/NII-cloud-operation/Jupyter-LC_index" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>
- [i18n_cells](https://github.com/NII-cloud-operation/Jupyter-i18n_cells)
<a class="github-button" href="https://github.com/NII-cloud-operation/Jupyter-i18n_cells" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>

<dl class="dl-horizontal">
  <dt>...</dt>
  <dd>...</dd>
</dl>
## Notebooks for Reproducible Infrastructure

- [Literate-computing-Basics](https://github.com/NII-cloud-operation/Literate-computing-Basics)
<a class="github-button" href="https://github.com/NII-cloud-operation/Literate-computing-Basics" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>
- [Literate-computing-Hadoop](https://github.com/NII-cloud-operation/Literate-computing-Hadoop)
<a class="github-button" href="https://github.com/NII-cloud-operation/Literate-computing-Hadoop" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>
- [Literate-computing-Elasticsearch](https://github.com/NII-cloud-operation/Literate-computing-Elasticsearch)
<a class="github-button" href="https://github.com/NII-cloud-operation/Literate-computing-Elasticsearch" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>

{% raw %}
<font color="MidnightBlue">
<h2><i>Memo</i></h2>
</font>
{% endraw %}

The following video presents early practices back to late 2015 and 2016Q1.  Since then, we have been developed *Literate Computing Tools* as enhancement of [Jupyter](https://jupyter.org/).

{% include youtube.html id='T309jbgdaqI' %}
