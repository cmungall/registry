---
identifier: MIR:00000155
name: TriTrypDB
description: TriTrypDB is one of the databases that can be accessed through the EuPathDB (http://EuPathDB.org; formerly ApiDB) portal, covering eukaryotic pathogens of the genera Cryptosporidium, Giardia, Leishmania, Neospora, Plasmodium, Toxoplasma, Trichomonas and Trypanosoma. While each of these groups is supported by a taxon-specific database built upon the same infrastructure, the EuPathDB portal offers an entry point to all these resources, and the opportunity to leverage orthology for searches across genera.
prefix: tritrypdb
pattern: ^\w+(\.)?\w+(\.)?\w+
prefixed: 0
local_id: Tb927.8.620
synonyms:
 - Kinetoplastid Genomics Resource
resources:
 - identifier: MIR:00100200
   accessurl: http://tritrypdb.org/tritrypdb/showRecord.do?name=GeneRecordClasses.GeneRecordClass&source_id=${lid}
   keyword: Trypanosoma brucei TREU927
   description: TriTrypDB at EuPathDB
   homepage: http://tritrypdb.org/tritrypdb/
   institution: Wellcome Trust Sanger Institute, Hinxton
   location: UK
   official: false
---
