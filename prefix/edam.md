---
identifier: MIR:00000189
name: EDAM Ontology
description: EDAM is an ontology of general bioinformatics concepts, including topics, data types, formats, identifiers and operations. EDAM provides a controlled vocabulary for the description, in semantic terms, of things such as: web services (e.g. WSDL files), applications, tool collections and packages, work-benches and workflow software, databases and ontologies, XSD data schema and data objects, data syntax and file formats, web portals and pages, resource catalogues and documents (such as scientific publications).
prefix: edam
pattern: ^(data|topic|operation|format)\_\d{4}$
prefixed: 0
local_id: data_1664
synonyms:
 - EMBRACE Data and Methods Ontology
resources:
 - identifier: MIR:00100536
   accessurl: http://purl.bioontology.org/ontology/EDAM/${lid}
   keyword: Minimal Information Requested in the Annotation of Biochemical Models
   description: EDAM through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/EDAM
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100762
   accessurl: http://www.ebi.ac.uk/ols/ontologies/edam/terms?short_form=${lid}
   keyword: Minimal Information Requested in the Annotation of Biochemical Models
   description: EDAM through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/edam
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
---
