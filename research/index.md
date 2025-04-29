---
title: Research
nav:
  order: 1
  tooltip: Our science
---

# {% include icon.html icon="fa-solid fa-dna" %}Our research
## <br>

{% include figure.html image="images/lab_summary.jpg" width="100%" %}

Our research employs a **multiscale approach** to develop and apply methods for the classification and analysis of large-scale biomedical datasets. </br>

1. At the **molecular level**, we focuse on developing tools and databases to classify and analyze protein domain features and their intercations with small molecules and drugs.
2. At the **cellular level**, we focus on analyzing expression profile variations within cancer types to uncover the factors that lead to diverse clinical outcomes.
3. At the **tissue level** we develope deep learning methods to identify cancer subtypes using tissue histopathology and linking tissue morphology to molecular features to improve diagnosis and treatment selection.

<hr>
**DrugDomain database and drug discovery** <br>
DrugDomain database includes both experimentally determined PDB structures and AlphaFold models enriched with ligands from experimental data. It is the first recourse in offering structural context for small molecule binding-associated Post-Translational Modifications on a large scale. <br>
We plan to use DrugDomain database for identification of novel protein targets for **drug repurposing** and off-target interaction effects based on evolutionary classification of protein domains.

{% include citation.html lookup="The evolutionary context of drugs and small molecules bound to domains" style="rich" %}

<hr>
**Identification of cancer subtypes** <br>
Testicular germ cell tumors (TGCT) are the most prevalent solid malignancy among adolescents and young men, ranking second in terms of the average life years lost per person dying of cancer. We conducted a computational study of all pure seminomas available at The Cancer Genome Atlas. Our work resulted in the discovery of **two subtypes of seminoma** differ in pluripotency stage, activity of double stranded DNA breaks repair mechanisms and rates of loss of heterozygosity. These findings have revealed two previously unknown subtypes of pure seminoma, showcasing their potential clinical relevance.

{% include citation.html lookup="Integrated Molecular Analysis Reveals 2 Distinct Subtypes of Pure Seminoma of the Testis" style="rich" %}
{% include citation.html lookup="Seminoma subtypes differ in the organization and functional state of the immune microenvironment" style="rich" %}

<hr>
**Digital Pathology**

Because clinical pathologists failed to distinguish seminoma subtypes on immunohistochemical slides, I have developed a deep learning (DL) image classifier for the identification of seminoma subtypes using histopathological slides. The results revealed histopathological differences between the two subtypes of pure seminoma. These findings provide additional confirmation and support the notion that seminoma can be further stratified into distinct subtypes.

{% include citation.html lookup="Deep Learning for Subtypes Identification of Pure Seminoma of the Testis" style="rich" %}
