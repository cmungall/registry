---
identifier: MIR:00000596
name: ClinVar Variant
description: ClinVar archives reports of relationships among medically important variants and phenotypes. It records human variation, interpretations of the relationship specific variations to human health, and supporting evidence for each interpretation. Each ClinVar record (RCV identifier) represents an aggregated view of interpretations of the same variation and condition from one or more submitters. Submissions for individual variation/phenotype combinations (SCV identifier) are also collected and made available separately. This collection references the Variant identifier.
prefix: clinvar
pattern: ^\d+$
prefixed: 0
local_id: 12345
resources:
 - identifier: MIR:00100796
   accessurl: https://www.ncbi.nlm.nih.gov/clinvar/variation/${lid}
   keyword: null
   description: ClinVar Variant at NCBI
   homepage: http://www.ncbi.nlm.nih.gov/clinvar/
   institution: National Center for Biotechnology Information (NCBI), NIH, Maryland
   location: USA
   official: false
   provider_code: ncbi
---
