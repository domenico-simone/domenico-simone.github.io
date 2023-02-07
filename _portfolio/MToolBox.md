---
title: "MToolBox"
subtitle: "A pipeline for mitochondrial SNP calling and annotation"
layout: single
excerpt: "Workflow for mitochondrial SNP calling and functional annotation from <b>NGS data</b> **NGS data**"
#<br><button type="button" name="button" class="btn">Button element</button>
# btn_class: "btn--primary"
# btn_label: "Go to section"
header:
  # image: /assets/images/mitochondrion.png
  teaser: /assets/images/mitochondrion.png
sidebar:
  - title: "Links"
    # image: http://placehold.it/350x250
    # image_alt: "logo"
    text: "<i class='fab fa-fw fa-github'></i>[MToolBox](https://github.com/mitoNGS/MToolBox)<br>
    <i class='fab fa-fw fa-github'></i>[MToolBox (snakemake)](https://github.com/mitoNGS/MToolBox_snakemake)"
---
#### A pipeline for mitochondrial SNP calling and annotation

<figure>
<img src="/assets/images/mt_genome.png" alt="Human mitochondrial genome" style="height: 500px; width: auto">
<figcaption>The human mitochondrial genome.</figcaption>
</figure>

**Mitochondria** are the powerhouses of eukaryotic cells and harbour their own genome (mtDNA), encoding essential genes related to OXPHOS. Therefore, mtDNA mutations are often linked to degenerative diseases (_e.g._ LHON, MELAS, MERRF, NARP). The availability of NGS technologies offers an outstanding opportunity to gain insights into mtDNA mutations and their role in highly heterogeneous diseases.<br>
<br>
**MToolBox** was developed in order to provide a highly automated pipeline to reconstruct and analyze human mitochondrial DNA from high-throughput NGS data. Originally developed as a [Bash script](https://github.com/mitoNGS/MToolBox), it is now being re-implemented as a [Snakemake pipeline](https://github.com/mitoNGS/MToolBox_snakemake) to leverage the flexibility of WMS and scale the pipeline to HPC clusters.<br>
<br>
As per early 2023, MToolBox has been used in **nearly 100 peer-reviewed clinical studies**.<br>
<br>

<p style="font-size:16px"><b>Tags</b>: mtDNA, Python, Bash, Snakemake<br>
<br>
<b>References:</b><br>
- CNRI/Science Photo Library/Getty Images<br>
- https://febs.onlinelibrary.wiley.com/doi/10.1002/1873-3468.12956
</p>