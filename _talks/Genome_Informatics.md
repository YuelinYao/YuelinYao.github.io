---
title: "Conference CSHL Genome Informatics 2023"
collection: presentations
type: "Presentation"
permalink: /talks/Genome_Informatics
venue: "Cold Spring Harbor Laboratory"
date: 2023-12-06
location: "1 Bungtown Rd, Cold Spring Harbor, NY 11724, United States"
---

INFO
======

Tentative Meeting Topics::

- PanGenome
- Genome Assembly and Sequencing Algorithms
- Variant Discovery
- Microbial and Metagenomics
- Single Cell and Spatial Omics
- Functional Genomics


Poster Presentation: 
======
Title: Stator: High order expression dependencies finely resolve cryptic states and subtypes in scRNA-seq data 

Advances in scRNA-seq techniques are resolving cell (sub)types among complex cell populations. However, conventional approaches are less able to reveal the continuous spectrum of cell states, such as cell cycle phases, in large part due to reliance on proximity in reduced dimensional gene expression space. We introduce Stator, a novel method that finely resolves cell types, subtypes and states among cells whose transcriptomes appear homogeneous upon clustering.  Stator takes advantage of lowly-expressed as well as not-expressed genes, and can identify rare biological states (~0.2% of 10k single cells). The approach: (i) applies a model-free estimator of higher-order interactions to quantify expression dependencies amongst n-tuples of genes (beyond pair-wise), (ii) extracts significantly deviating gene combinations (tuples) driving these higher-order gene dependencies, and finally (iii) combines tuples into Stator states when they commonly co-occur in the same cell. Typically, Stator labels a cell not just by type and sub-type but also by biological state, for example an immature interneuron in G2/M cell cycle phase. Stator generates molecular and cellular hypotheses for subsequent experimental testing. To facilitate this, we provide a Stator Shiny App (https://shiny.igc.ed.ac.uk/MFIs/). This flexible app takes the output of Stator’s Nextflow pipeline and performs downstream analyses through an interactive and user-friendly interface, such as (i) comparing Stator state labels with external annotations or experimental conditions, (ii) calculating differential gene expression per Stator state, (iii) automatically annotating states using a user-provided gene list, and (iv) analysing Gene Ontology and KEGG Pathway enrichment for tuples’ genes and DEGs. We demonstrate Stator’s ability to extract biologically meaningful cell (sub)types and states at far greater resolution than hitherto using publicly available scRNA-seq datasets of mouse developmental astrocytes or neurons, and a hepatocellular carcinoma dataset.  

[More information](/images/CSHL_GI_2023.pdf)


