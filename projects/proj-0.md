---
layout: post
title: 'Development of a machine learning-based classifier to enable plasmid research in Acinetobacter baumannii'
---
2019-2020

*Acinetobacter baumannii* is an opportunistic pathogen with extensive antibiotic resistance, often carried on plasmids that can spread via horizontal gene transfer. Short-read whole-genome sequencing generates fragmented contigs whose origin—plasmid or chromosome—is difficult to determine with existing tools. To address this, we developed a machine-learning classifier using pentamer frequencies of contigs to distinguish plasmid- from chromosome-derived sequences. Training on 146 complete genomes and 214 plasmids with five algorithms, the Support-Vector Machine achieved the best performance (AUC = 0.936, F1 = 0.847) when using a balanced training set. Our approach outperformed existing tools like cBar and PlasFlow and provides a reliable method for classifying contigs, identifying plasmid-borne antibiotic resistance genes, and generating species-specific models for other pathogens.


##### Analysis code

[https://gitlab.com/AlessiaCarrara/master-thesis_a_baumannii_plasmids_supp-materials](https://gitlab.com/AlessiaCarrara/master-thesis_a_baumannii_plasmids_supp-materials)


##### My contribution

This project was conducted as my Master’s thesis under the supervision of Prof. Anita C. Schürch and Dr. Sergio Arredondo-Alonso. 