---
identifier: MIR:00000345
name: GenPept
description: The GenPept database is a collection of sequences based on translations from annotated coding regions in GenBank.
prefix: genpept
pattern: ^\w{3}\d{5}(\.\d+)?$
prefixed: 0
local_id: CAA71118.1
synonyms:
 - protein genbank identifier
resources:
 - identifier: MIR:00100440
   accessurl: http://www.ncbi.nlm.nih.gov/protein/${lid}?report=genpept
   keyword: Klebsiella pneumoniae
   description: GenPept at NCBI
   homepage: http://www.ncbi.nlm.nih.gov/protein
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: false
   provider_code: ncbi
---
