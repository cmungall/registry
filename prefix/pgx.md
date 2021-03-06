---
identifier: MIR:00000600
name: Progenetix
description: The Progenetix database provides an overview of copy number abnormalities in human cancer from currently 32317 array and chromosomal Comparative Genomic Hybridization (CGH) experiments, as well as Whole Genome or Whole Exome Sequencing (WGS, WES) studies. The cancer profile data in Progenetix was curated from 1026 articles and represents 364 different cancer types, according to the International classification of Diseases in Oncology (ICD-O).
prefix: pgx
pattern: ^[\w\-:,]{3,64}$
prefixed: 0
local_id: icdom:8500_3
synonyms:
 - Cancer Genome Knowledge Resource
resources:
 - identifier: MIR:00100801
   accessurl: http://progenetix.org/pgx:${lid}
   keyword: 8500/3
   description: Progenetix
   homepage: http://progenetix.org/
   institution: University of Zurich
   location: Switzerland
   official: false
---
