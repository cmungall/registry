---
identifier: MIR:00000170
name: HOMD Sequence Metainformation
description: The Human Oral Microbiome Database (HOMD) provides a site-specific comprehensive database for the more than 600 prokaryote species that are present in the human oral cavity. It contains genomic information based on a curated 16S rRNA gene-based provisional naming scheme, and taxonomic information. This datatype contains genomic sequence information.
prefix: homd.seq
pattern: ^SEQF\d+$
prefixed: 0
local_id: SEQF1003
synonyms:
 - Human Oral Microbiome Database
resources:
 - identifier: MIR:00100216
   accessurl: http://www.homd.org/modules.php?op=modload&name=GenomeList&file=index&link=detailinfo&seqid=${lid}
   keyword: ATCC 49626
   description: HOMD sequence metainformation at The Forsyth Institute
   homepage: http://www.homd.org/index.php
   institution: The Forsyth Institute, Boston
   location: USA
   official: false
---
