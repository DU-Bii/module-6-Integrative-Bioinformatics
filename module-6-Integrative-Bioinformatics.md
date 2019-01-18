
# [DU-Bii](https://du-bii.github.io/accueil/) module 6 : Integrative Bioinformatics

----------------------------------------------------------------

## Description

This course takes place in the 1-month training "Diplôme Universitaire en Bioinformtaique Intégrative" ([DU-Bii](https://du-bii.github.io/accueil/)) organised by Université Paris-Diderot and the Institut Français de Bioinformatique (IFB). 


### Pre-requisites

All participants are encouraged to follow the two inroductory videos, read the review and answer to two simple questions for comprehension in the Paris Diderot course "Moodle" page.
<https://moodlesupd.script.univ-paris-diderot.fr/mod/page/view.php?id=167920>

### Skills acquired during this course

At the end of this course, trainees should be able to do the following: $

- ...


### Concepts covered

- ....


(For Costas to verify PPI and RNA-Seq integration?)


## Table of contents


### Course 1: Functional interpretation of gene sets

*Teachers: Jacques van Helden and Olivier Sand*

Concepts: 
- functional annotations, 
- Gene Ontology, 
- pathways (metabolic, signaling),
- biomolecular networks (protein-protein, co-expression, molecular complexes, metabolic reactions)

Resources:
- databases containing these data types.
- g:Profiler (Web site + R library)
- metabolic mapping tools (KEGG pathway coloring). 

Enrichment tests: 
- goals, 
- principles and approaches: enrichment, GSEA, ...
- statistics (seen in the course Stat with R), 
- good practices (choice of an appropriate background, multiple testing correction),
- interpretation of the results)

Application:
- Annotation of groups of genes produced by the other courses (e.g. differentially expressed genes from RNA-seq, disease-associated genes, ...)

### Course 2 and 3: Integrating multi-omics data with multi-level matrix factorisation

*Teachers: Sébastien Déjean, Jérôme Mariette et Laura Cantini*

Concepts: 
- Integrative bioinformatics approaches and their application to cancer (Laura Cantini)
       - Motivation
       - Which approach to answer which question (subsetting, modules, pathways) ?
       - Main methodologies: networks, matrix factorisation
- Principles of multi-level matrix factorisation (Sébastien Déjean)
- Kernel-based approaches (Jérôme)

Practical:
- mixOmics
- JM tools (please specify)

Datasets: 
- TCGA
- metagenomics data (Jérôme Mariette)

### Course 4: Network Analysis with Cytoscape, session I

*Teachers: Anaïs Baudot and Costas Bouyioukos*

- Introduction to network sciences in biology (~ 30 minutes)
- Practical, part A (~ 90 minutes)
    - improve the first part of Anais’s TP
- Practical, part B 
    - improve Costas TP 
    - Dataset: bacterial regulons
    - Topics: topological analysis of networks


### Course 5: WGCNA, network inference

*Teachers: Costas Bouyioukos and Anaïs Baudot*

- Intro inferring networks from *omics data.
- Intro to clustering for GRNs.
- Intro to eigen decomposition (eigenvalues, eigenvectors)
- Thresholding correlation matrices.
- Visualization of the network and interactions.
- Refinement of network topology by using a smart thresholding technique with concept of eigengene. 
- Closing by mentioning Inferelator and cMonkey combined network inference by RNA-seq and Chip-Seq.


### Course 6: Network Analysis with Cytoscape, session II

*Teachers: Anaïs Baudot and Costas Bouyioukos*

- Short intro to network measures (graphical explanation)
- Guilt by association algorithms, clustering for community identification and random walks
- Multiplex / multiscale
- Integration of expression data into networks, jActive module
- Integration of ontologies
- Cytoscape apps
- Integration of different types of interactions, miRNA and mRNA transcription, combine.

----------------------------------------------------------------

## Planning DU-Bii 2019

<https://tinyurl.com/dubii19-planning>

----------------------------------------------------------------

## Credits

### Course coordinators

1. AnaÏs Baudot, CNRS, Marseille
2. Bertrand Cosson, Université Paris-Diderot, Paris
3. [Costas Bouyioukos](https://orcid.org/0000-0002-7443-3736), Université Paris-Diderot, UMR7216

### Other teachers

4.  [Jacques van Helden](https://orcid.org/0000-0002-8799-8584), Institut Français de Bioinformatique, Aix-Marseille Université

----------------------------------------------------------------

## Access to training material

- Web: <https://du-bii.github.io/module-6-Integrative-Bioinformatics/>
- Github (sources): <https://github.com/DU-Bii/module-6-Integrative-Bioinformatics/>

## Installation


### Contributors (members of the teaching team)

```{bash}
git clone git@github.com:DU-Bii/module-6-Integrative-Bioinformatics.git
```
### Other people

```{bash}
git clone https://github.com/DU-Bii/module-6-Integrative-Bioinformatics.git
```


## License

![](img/CC-BY-SA.png)


This content is released under the [Creative Commons Attribution-ShareAlike 4.0 ](https://creativecommons.org/licenses/by-sa/4.0/deed.en) (CC BY-SA 4.0) license. See the bundled [LICENSE](LICENSE.txt) file for details.

Ce contenu est mis à disposition selon les termes de la licence [Creative Commons Attribution - Partage dans les Mêmes Conditions 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/deed.fr) (CC BY-SA 4.0). Consultez le fichier [LICENSE](LICENSE.txt) pour plus de détails.

