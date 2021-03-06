---
identifier: MIR:00000082
name: Rhea
description: Rhea is a manually annotated reaction database, where all reaction participants (reactants and products) are linked to the ChEBI database (Chemical Entities of Biological Interest), providing detailed information about structure, formulae and charge. It is populated with the reactions found in the EC list, IntEnz and ENZYME databases), as well as other biochemical reactions, including those that are often termed "spontaneous".
prefix: rhea
pattern: ^\d{5}$
prefixed: 0
local_id: 12345
resources:
 - identifier: MIR:00100113
   accessurl: http://www.rhea-db.org/reaction?id=${lid}
   keyword: 4-amino-5-oxopentanoate
   description: Rhea
   homepage: http://www.rhea-db.org/
   institution: European Bioinformatics Institute and Swiss Institute of Bioinformatics
   location: UK
   official: true
---
