---
title: News
nav:
  order: 6
  tooltip: Lab News
---

# Lab News
<hr>
<strong>September, 2026</strong> <br>
In our <a href="https://link.springer.com/article/10.1007/s10822-026-00936-w">new paper</a>  published in Journal of Computer-Aided Molecular Design (JCAMD), we combined ECOD domain classification, AlphaFold3 modeling, and molecular dynamics to predict off-targets for Seladelpar (a PPARδ agonist) and Zanamivir, then took the top predictions to the bench.
 
💡 <strong>AlphaFold3 confidence did not track pose accuracy.</strong> For PPARγ, four of five AF3 models placed Seladelpar ~8 Å from its position in the experimental structure (8HUP). The one model that reproduced the correct binding mode had the lowest AlphaFold3 ranking score - filtering on confidence would have discarded it.

💡 <strong>The protein was right; the ligand was wrong.</strong> Binding sites were reproduced accurately across all six receptors with an experimental complex (Cα RMSD 0.37-2.84 Å), including PPARγ. The error was specific to ligand placement, not to the modelled pocket.

💡 <strong>Not an AlphaFold3-specific problem</strong>. Boltz-2 missed the same PPARγ pose. Both methods reproduced PPARα (8HUN). The difficulty is a property of the target.

💡 <strong>Prediction met reality</strong>. FXR, RARγ and ERRγ ranked closest to the on-target PPARδ control by trajectory features, and none showed functional activity in reporter assays - despite stable simulations and, in some cases, more hydrogen bonds with Seladelpar than the control formed.

💡 <strong>Positive controls exposed the gap</strong>. PPARα and PPARγ, both weakly activated by Seladelpar, ranked further from the control than the receptors that proved inactive.
 
💡 <strong>Where the signal actually was</strong>. Residue-level comparison with agonist-bound structures showed Seladelpar's carboxylate reaching each receptor's own recognition site but completing only part of the canonical contacts - invisible to every global trajectory descriptor we computed.

Huge kudos to our amazing collaborators <strong>Tom Kean</strong> and <strong>Rachel Kemp</strong> from UCF College of Medicine!

<hr>
<strong>August, 2026</strong> <br>
We welcome <a href="https://medvedevlab.org/members/pratham-lotia.html">Pratham Lotia </a> - our new PhD student!

<hr>
<strong>January, 2026</strong> <br>
<a href="https://medvedevlab.org/members/barsha-roy.html">Barsha Roy</a> officially joins as the lab's first PhD student!

<hr>
<strong>November, 2025</strong> <br>
<strong>Academic Upbringing in Siberia Inspires Computer Science Professor's Career</strong> <br>
Article text: <a href="https://www.cecs.ucf.edu/academic-upbringing-in-siberia-inspires-kirill-medvedevs-career/">Read full article</a>

<div class="text-img" style="text-align: left;">
  <img width="450" src="/images/KM_UCF.jpg" style="float: left; margin-right: 20px; margin-bottom: 10px;">
  
  Deep in the pine forest of Siberia lies a unique scientific community that was envisioned as the New Atlantis of science. At its peak, the town was home to more than 65,000 scientists who worked at 35 research institutes dedicated to molecular biology, chemistry, physics and cybernetics. Neighbors and friends would gather at the local cafes or courtyards, not only to exchange pleasantries, but also to discuss the latest discoveries and to debate new scientific trends. 
  <br><br>
  While this sounds like the setting for a sci-fi novel, it's actually the hometown of Assistant Professor Kirill Medvedev, a new faculty member in the <a href="https://www.cs.ucf.edu/">Department of Computer Science</a>. Medvedev grew up in Akademgorodok, which literally translates to "Academic Town," a place that sparked his interest in bioinformatics and inspired his career.
  <br><br>
  "The constant exposure to open, curiosity-driven inquiry made the language of science feel as natural as the Siberian forest around us," Medvedev says. "My passion for bioinformatics and computational biology was ignited by a fascination with three-dimensional protein structures. I realized that computational approaches are indispensable for decoding life's molecular machines, and it set me on the path toward research in the field of computational structural biology and bioinformatics."
  <br><br>
  Medvedev's work focuses on the classification and analysis of large-scale biomedical data sets that span the molecular, cellular and tissue levels. With that expertise, he is teaching a Discrete Mathematics course at UCF this fall. He says he hopes to instill both practical and technical knowledge in his students.
  <br><br>
  "I believe that integrity is the defining characteristic of a scientist," he says.
  <br><br>
  Medvedev's work focuses on the classification and analysis of large-scale biomedical data sets that span the molecular, cellular and tissue levels. Within the past decade, he developed the DrugDomain database, which lists the domain features of human proteins that are targets for small molecules and drugs. He augmented the DrugDomain database with artificial intelligence‑powered protein structure prediction, creating a first‑of‑its‑kind resource that maps thousands of post‑translational modifications to their drug targets across the human proteome. He also uses computational modeling to analyze variations within cancer types and employs deep learning methods to identify cancer subtypes.
  <br><br>
  The opportunity to collaborate with the next generation of scientists, as well as established colleagues, is what Medvedev says drew him to UCF.
  <br><br>
  "Today, truly groundbreaking science cannot be done by one person, or even one lab, but only through collaboration among multidisciplinary teams," Medvedev says.
  <br><br>
  Medvedev earned his doctoral degree in mathematical biology and bioinformatics from the Institute of Cytology and Genetics in 2015. Following that, he's worked with Professor Nick Grishin at the University of Texas Southwestern Medical Center as a postdoctoral researcher.
</div>
<div style="clear: both;"></div>
<hr>

