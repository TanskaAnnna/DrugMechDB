---
title: "Cefmetazole - Pneumonia"
sidebar: mydoc_sidebar
permalink: cefmetazolepneumonia.html
toc: false 
---

{% include image.html url="images/cefmetazolepneumonia.png" file="cefmetazolepneumonia.png" alt="cefmetazolepneumonia" %}

## Concepts

|------------|------|---------|
| Identifier | Name | Type    |
|------------|------|---------|
| MESH:D015311 | Cefmetazole | Drug |
| InterPro:IPR005311 | Penicillin binding proteins | GeneFamily |
| GO:0009252 | Peptidoglycan biosynthetic process | BiologicalProcess |
| GO:0009273 | Peptidoglycan-based cell wall biogenesis | BiologicalProcess |
| GO:0051301 | Cell division | BiologicalProcess |
| NCBITaxon:2 | Bacteria | OrganismTaxon |
| MESH:D011014 | Pneumonia | Disease |
|------------|------|---------|

## Relationships

|---------|-----------|---------|
| Subject | Predicate | Object  |
|---------|-----------|---------|
| Cefmetazole | DECREASES ACTIVITY OF | Penicillin Binding Proteins |
| Penicillin Binding Proteins | POSITIVELY REGULATES | Peptidoglycan Biosynthetic Process |
| Peptidoglycan Biosynthetic Process | POSITIVELY REGULATES | Peptidoglycan-Based Cell Wall Biogenesis |
| Peptidoglycan-Based Cell Wall Biogenesis | POSITIVELY CORRELATED WITH | Cell Division |
| Cell Division | IN TAXON | Bacteria |
| Bacteria | CAUSES | Pneumonia |
|---------|-----------|---------|

Reference: [https://go.drugbank.com/drugs/DB00274#mechanism-of-action](https://go.drugbank.com/drugs/DB00274#mechanism-of-action){:target="_blank"}