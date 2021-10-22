---
title: "Fast enumeration of non-isomorphic chemical reaction networks"
subtitle: ""
summary: ""
authors: 
- Spaccasassi C
- Yordanov B
- Phillips A
- Dalchau N


tags: []
categories: [Dynamical Systems]
date: 2019-09-17 00:00:00
publishDate: 2019-09-17 00:00:00
featured: false
draft: false
publication: 'Computational Methods in Systems Biology (CMSB)'
publication_types: ["1"]
doi: 'https://doi.org/10.1007/978-3-030-31304-3_12'
links:
- icon: github
  icon_pack: fab
  name: Github
  url: https://github.com/CSpaccasassi/genCRN

abstract: Chemical reaction networks (CRNs) have been applied successfully to model a wide range of phenomena and are commonly used for designing molecular computation circuits. Often, CRNs with specific properties (oscillations, Turing patterns, multistability) are sought, which entails searching an exponentially large space of CRNs for those that satisfy a property. As the size of the CRNs being considered grows, so does the frequency of isomorphisms, by up to a factor N!, where N is the number of species. Accordingly, being able to generate sets of non-isomorphic CRNs within a class can lead to large computational savings when carrying out global searches. Here, we present a bijective encoding of bimolecular CRNs into novel vertex-coloured digraphs called Complex-Species graphs. The problem of enumerating non-isomorphic CRNs can then be tackled by leveraging well-established computational methods from graph theory &#91;20&#93;. In particular, we extend Nauty, the graph isomorphism tool suite by McKay &#91;22&#93;. Our method is highly parallelisable and more efficient than competing approaches, and a software package (genCRN) is freely available for reuse. Non-isomorphs are generated directly by genCRN, alleviating the need to store intermediate results. We provide the first complete count of all 2-species bimolecular CRNs and extend previous known counts for classes of CRNs of special interest, such as mass-conserving and reversible CRNs.

projects: []
---