---
identifier: MIR:00000261
name: CABRI
description: CABRI (Common Access to Biotechnological Resources and Information) is an online service where users can search a number of European Biological Resource Centre catalogues. It lists the availability of a particular organism or genetic resource and defines the set of technical specifications and procedures which should be used to handle it.
prefix: cabri
pattern: ^([A-Za-z]+)?(\_)?([A-Za-z-]+)\:([A-Za-z0-9 ]+)$
prefixed: 0
resources:
 - identifier: MIR:00100334
   accessurl: http://www.cabri.org/CABRI/srs-bin/wgetz?-e+-page+EntryPage+[
   description: CABRI Cell Lines catalogue in Genova (SRS)
   location: Italy
   official: true
 - identifier: MIR:00100335
   accessurl: http://www.be.cabri.org/CABRI/srs-bin/wgetz?-e+-page+EntryPage+[
   description: CABRI Cell Lines catalogue in Brussels (SRS)
   location: Belgium
   official: false
---