---
title: "Research Intern"
description: "Saint Louis University, Missouri, United States of America"
dateString: May 2022 - Dec 2022
draft: false
tags: ["Research", "Machine Learning", "Deep Learning", "Computational Biology"]
showToc: false
weight: 303
--- 

## Description
**Guide:** **Dr. Jie Hou** (Assistant Professor, Dept. of Computer Science, Saint Louis University)

I worked under Dr. Hou for over 7 months, and in that time, I got to explore applications of AI that I hadn't previously known existed. In particular, our work had been concentrated on the prediction of the structure of RNA molecules. Mainly, I was involved in a project that aimed to predict the secondary structure of RNA molecules using Deep Learning. I also practiced the construction of 3D RNA structures from secondary structures using Assemble2 with UCSF Chimera. 
&nbsp; 

**RNA secondary structure prediction using a graph neural network approach**
&nbsp; 

To familiarize myself with the work done in this domain, I read a lot of papers. I also kept up with all the new innovations in this space. I performed a thorough literature analysis, and organized my findings in a tabular format delineating the important information in a quick view for further investigation. 

I wrote a Python script that automated the process of model evaluation, including the inter-file conversions from different formats and comparisons. If done manually, this would have taken a much longer time as it was done for a large dataset. 
 
 The process followed for the evaluation, which compared our predicted structures to the true structures:

(1) import .fasta files from the PDB dataset

(2) predict its structure using different models

(3) save the dot bracket files

(4) convert the bracket files into ct files (predicted structure)

(5) import .bps file (true structure)

(6) write an evaluation script which computes the true positive, false positive, true negative and false nagative as well as outputs a confusion matrix

&nbsp; \
*Some of my key findings and learnings:*

Due to my limited knowledge of computational biology, I had a very steep learning curve. But by familiarizing myself with the relevant literature, I was able to overcome this. I learned a lot more about how to evaluate Deep Learning models, and also about good model architectures. 
