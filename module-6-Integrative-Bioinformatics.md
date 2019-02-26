
# [DU-Bii](https://du-bii.github.io/accueil/) module 6 : Integrative Bioinformatics

----------------------------------------------------------------

## Description

This course takes place in the 1-month training "Diplôme Universitaire en Bioinformatique Intégrative" ([DU-Bii](https://du-bii.github.io/accueil/)) organised by Université Paris-Diderot and the Institut Français de Bioinformatique (IFB).


### Pre-requisites

All participants are encouraged to follow the two introductory videos and read the review in the Paris Diderot course "Moodle" page.
<https://moodlesupd.script.univ-paris-diderot.fr/mod/page/view.php?id=167920>

### Skills acquired during this course

At the end of this course, trainees should be able to do the following: $

- ...


### Concepts covered

- ....


(For Costas to verify PPI and RNA-Seq integration?)


## Table of contents


### Course 1: Functional interpretation of gene sets

[Présentation](Seance1/DU-Bii_2019_m6s1_Integrative-bioinformatics-intro.pdf)

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
        
| Contenu | HTML | pdf | Rmd | R |
|--------------------------------------------------|------|------|-----|-----|
| Presentation Laura Cantini |  | [Slides](Seance2/Cantini_DU-Bii_module6.pdf) |  |
| Presentation Sébastien Dejean et Jérôme Mariette |  | [Slides](Seance2/DUBii_SD_JM.pdf) |  |
| MixOmics |  | [Slides](Seance2/slide_mixOmics_2018.pdf) |  | [R](Seance2/TP_mixOmics_DUBii.R) |
| Practical MOFA | [html](Seance2/practical_MOFA.html) |  | [Rmd](Seance2/practical_MOFA.Rmd) |
| Practical mixKernel | [html](Seance2/TP_mixKernel_DUBii.html) |  | [Rmd](Seance2/TP_mixKernel_DUBii.Rmd) |

*Teachers: Sébastien Déjean, Jérôme Mariette et Laura Cantini*

Concepts:
- Integrative bioinformatics approaches and their application to cancer (Laura Cantini)  
       - Motivation  
       - Which approach to answer which question (subsetting, modules, pathways) ?  
       - Main methodologies: networks, matrix factorisation  
- Principles of multi-level matrix factorisation (Sébastien Déjean)
- Kernel-based approaches (Jérôme Mariette)

Practical:
- mixOmics
- JM tools (please specify)

Datasets:
- TCGA
- metagenomics data (Jérôme Mariette)

### Course 4: Network Analysis with Cytoscape, session I

*Teachers: Anaïs Baudot and Costas Bouyioukos*

- Introduction to network sciences in biology
- Practical with Cytoscape
    - Basics on human interactome
    - Basics on bacterial regulons
    - Keywords: interactome, regumone, network visualisation and topological analyses


### Course 5: WGCNA, network inference

*Teachers: Costas Bouyioukos and Anaïs Baudot*

- Introduction: inferring networks from \*omics data, clustering for Gene Regulatory Networks
<!--
- Intro to eigen decomposition (eigenvalues, eigenvectors)
- Thresholding correlation matrices.
- Refinement of network topology by using smart thresholding techniques,
  the concept of eigengene.
-->
- Practical with R
       - Inferrence of co-expression networks with the WGCNA package
       
 A document to familiarise with the terminology of correlation networks and WGCNA can be found [here](https://horvath.genetics.ucla.edu/html/CoexpressionNetwork/Rpackages/WGCNA/Tutorials/Simulated-00-Background.pdf)

Conclusions and mentions of Inferelator and cMonkey, two network inference tools which combine RNA-seq and Chip-Seq data.


### Course 6: Network Analysis with Cytoscape, session II

*Teachers: Anaïs Baudot and Costas Bouyioukos*

- Introduction to Network algorithms (measures, guilt-by-association, clustering)
- Cytoscape apps
- Integration of different types of interactions, miRNA and mRNA transcription
- Practical with Cytoscape
       - Integrating knowledge in networks: Enrichmap
       - Integrating expression data in networks: jActive module
       - Integrating networks: multiplex networks

----------------------------------------------------------------

## Planning DU-Bii 2019

<https://tinyurl.com/dubii19-planning>

----------------------------------------------------------------

## Credits

### Course coordinators

1. [Anaïs Baudot](https://orcid.org/0000-0003-0885-7933), CNRS, Marseille
2. [Costas Bouyioukos](https://orcid.org/0000-0002-7443-3736), Université Paris-Diderot, UMR7216
3. Olivier Sand 

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
