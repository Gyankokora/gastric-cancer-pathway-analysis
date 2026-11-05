# Gastric Cancer Pathway Signatures Across Independent GEO Datasets

*Replication and extension of published gastric cancer findings through transcriptomics, pathway enrichment, and network-based analysis.*

## Why I Explored This

When researchers analyse cancer gene-expression data, they often identify genes and biological pathways associated with disease progression. But I was curious about something else: would those same findings hold up if the analysis were repeated using different datasets and bioinformatics tools?

This question became the starting point for my project.

Building on the study by Chivu-Economescu et al. (2022), I explored whether the molecular patterns they identified in gastric cancer could also be found in three independent datasets from the Gene Expression Omnibus (GEO).

Rather than focusing only on finding the exact same genes, I wanted to understand whether the broader biological processes remained consistent. I was particularly interested in extracellular matrix remodelling, collagen organisation, focal adhesion, and the interactions between cancer cells and their surrounding environment.

## What I Found

Using three independent GEO datasets (GSE19826, GSE54129, and GSE118916), I identified **24 commonly upregulated genes and 60 commonly downregulated genes**.

Interestingly, although the gene lists were not identical to those reported in the original study, many of the same biological pathways emerged.

Extracellular matrix organisation, collagen remodelling, and focal adhesion repeatedly appeared in the enrichment analyses, suggesting that these processes remain important features of gastric cancer across the datasets examined.

I then explored how the identified genes were connected through protein–protein interaction networks and whether selected hub genes were associated with patient survival.

The Kaplan–Meier analysis showed that higher expression of **COL1A1, COL6A3, and THBS2** was significantly associated with poorer overall survival, with THBS2 showing the strongest association among the genes examined.

## What I Took Away

What stood out to me most was that different datasets did not always lead to the same genes, yet they continued to tell a similar biological story.

This highlighted something I find particularly interesting about bioinformatics: meaningful insights do not always come from looking at individual genes in isolation. Sometimes, understanding how genes work together within pathways and molecular networks provides a clearer picture of the biological processes involved.

The project also reminded me of the importance of interpreting computational findings carefully. Although the analysis helped prioritise potentially relevant biomarkers, further experimental and clinical validation would be needed to establish their biological roles and clinical usefulness.

Ultimately, this experience strengthened my interest in using computational approaches to move beyond identifying molecular patterns towards understanding what those patterns might tell us about human disease.
