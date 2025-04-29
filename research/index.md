---
title: Research
nav:
  order: 1
  tooltip: Our science
---

# {% include icon.html icon="fa-solid fa-dna" %}Our research
## <br>


{% capture text %}

Our research employs a **multiscale approach** to develop and apply methods for the classification and analysis of large-scale biomedical datasets. </br>

At the **molecular level**, we focuse on developing tools and databases to classify and analyze protein domain features and their intercations with small molecules and drugs.
At the **cellular level**, we focus on analyzing expression profile variations within cancer types to uncover the factors that lead to diverse clinical outcomes.
At the **tissue level** we develope deep learning methods to identify cancer subtypes using tissue histopathology and linking tissue morphology to molecular features to improve diagnosis and treatment selection.

{% endcapture %}

{%
  include feature.html
  image="images/logo.png"
  link="publications"
  title="RNA editing & RNA repair"
  text=text
%}

<hr>
**DrugDomain datbase** <br>
DrugDomain database includes both experimentally determined PDB structures and AlphaFold models enriched with ligands from experimental data. It is the first recourse in offering structural context for small molecule binding-associated Post-Translational Modifications on a large scale.

{%
  include feature.html
  image="images/drugdomain_logo_fin.png"
  link="publications"
  title="DrugDomain datbase"
  text=text
%}

{% include citation.html lookup="Repair of CRISPR-guided RNA breaks enables site-specific RNA excision" style="rich" %}

<hr>
**Recombinant RNA technologies** <br>
We have combined sequence-specific RNA cleavage by CRISPR ribonucleases with programmable RNA repair to make precise deletions and insertions in RNA. This *in vitro* recombinant RNA technology enables rapid and facile engineering of RNA viruses, and we use this approach to dissect the effect of recurring mutations in viral genomes on viral phenotypes.

{% include citation.html lookup="CRISPR-based engineering of RNA viruses" style="rich" %}


**Mechanisms of viral RNA replication**

The paradigm "*Why repair RNA if you can re-synthesize it?*" does not work in the case of RNA viruses because RNA is all they have. We are interested in mechanisms that RNA viruses have evolved to maintain the integrity of their genomes, counteract innate immunity, and promote viral replication.


{% include citation.html lookup="SARS-CoV-2 genomic surveillance identifies naturally occurring truncation of ORF7a that limits immune suppression" style="rich" %}
