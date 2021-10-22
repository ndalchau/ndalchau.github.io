---
title: "A Deep Learning Model for Predicting NGS Sequencing Depth from DNA Sequence"
subtitle: ""
summary: ""
authors: 
- Zhang J
- Yordanov B
- Gaunt A
- Wang M
- Dai P
- Chen Y-J
- Zhang K
- Fang J
- Dalchau N
- Li J
- Phillips A
- Zhang D


tags: []
categories: [DNA Computing]
date: 2021-07-19 00:00:00
publishDate: 2021-07-19 00:00:00
featured: false
draft: false
publication: 'Nature Communications'
publication_types: ["2"]

doi: 'https://doi.org/10.1038/s41467-021-24497-8'
abstract: Targeted high-throughput DNA sequencing is a primary approach for genomics and molecular diagnostics, and more recently as a readout for DNA information storage. Oligonucleotide probes used to enrich gene loci of interest have different hybridization kinetics, resulting in non-uniform coverage that increases sequencing costs and decreases sequencing sensitivities. Here, we present a deep learning model (DLM) for predicting Next-Generation Sequencing (NGS) depth from DNA probe sequences. Our DLM includes a bidirectional recurrent neural network that takes as input both DNA nucleotide identities as well as the calculated probability of the nucleotide being unpaired. We apply our DLM to three different NGS panels&#58; a 39,145-plex panel for human single nucleotide polymorphisms (SNP), a 2000-plex panel for human long non-coding RNA (lncRNA), and a 7373-plex panel targeting non-human sequences for DNA information storage. In cross-validation, our DLM predicts sequencing depth to within a factor of 3 with 93% accuracy for the SNP panel, and 99% accuracy for the non-human panel. In independent testing, the DLM predicts the lncRNA panel with 89% accuracy when trained on the SNP panel. The same model is also effective at predicting the measured single-plex kinetic rate constants of DNA hybridization and strand displacement.

projects: []
---