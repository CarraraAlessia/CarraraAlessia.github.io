---
layout: post
title: 'Development of a machine learning-based classifier to enable plasmid research in Acinetobacter baumannii'
---
2019-2020

*Acinetobacter baumannii* is an opportunistic pathogen with extensive antibiotic resistance, often carried on plasmids that can spread via horizontal gene transfer. Short-read whole-genome sequencing generates fragmented contigs whose origin—plasmid or chromosome—is difficult to determine with existing tools. To address this, we developed an *Acinetobacter baumannii*-specific machine-learning classifier using pentamer frequencies of contigs to distinguish plasmid- from chromosome-derived sequences. Training on 146 complete *Ab* genomes and 214 plasmids with five algorithms, the Support-Vector Machine achieved the best performance (AUC = 0.936, F1 = 0.847) when using a balanced training set, outperforming existing tools like cBar and PlasFlow.

##### Analysis code

[gitlab.com/AlessiaCarrara/master-thesis_a_baumannii_plasmids_supp-materials](https://gitlab.com/AlessiaCarrara/master-thesis_a_baumannii_plasmids_supp-materials)

##### My contribution

This project was conducted as my Master’s thesis under the supervision of Prof. Anita C. Schürch and Dr. Sergio Arredondo-Alonso.
The following *A.baumannii* model was integrated in [mlplasmids](https://doi.org/10.1099/mgen.0.000224).

A presentation of the project is available [here](https://aschuerch.github.io/posts/2020-07-08-blog-post-8).