---
identifier: MIR:00000569
name: MetaNetX compartment
description: MetaNetX/MNXref integrates various information from genome-scale metabolic network reconstructions such as information on reactions, metabolites and compartments. This information undergoes a reconciliation process to minimise for discrepancies between different data sources, and makes the data accessible under a common namespace. This collection references cellular compartments.
prefix: metanetx.compartment
pattern: ^(MNX[CD]\d+|BOUNDARY)$
prefixed: 0
local_id: MNXC15
resources:
 - identifier: MIR:00100750
   accessurl: http://www.metanetx.org/comp_info/${lid}
   keyword: Golgi apparatus
   description: MetaNetX compartment at SIB Swiss Institute of Bioinformatics
   homepage: http://www.metanetx.org/
   institution: Vital-IT group, SIB Swiss Institute of Bioinformatics, Lausanne
   location: Switzerland
   official: false
---
