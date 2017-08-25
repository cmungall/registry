---
identifier: MIR:00000530
name: FooDB Compound
description: FooDB is resource on food and its constituent compounds. It includes data on the compound’s nomenclature, its description, information on its structure, chemical class, its physico-chemical data, its food source(s), its color, its aroma, its taste, its physiological effect, presumptive health effects (from published studies), and concentrations in various foods. This collection references compounds.
prefix: foodb.compound
pattern: ^FDB\d+$
prefixed: 0
resources:
 - identifier: MIR:00100689
   accessurl: http://foodb.ca/compounds/${id}
   test_id: FDB002100
   description: FooDB database of food additives at University of Alberta
   homepage: http://foodb.ca/foods
   institution: University of Alberta, Edmonton, AB
   location: Canada
   official: false
---
