# [DU-Bii](https://du-bii.github.io/accueil/) module 6: Integrative Bioinformatics

----------------------------------------------------------------

## Examen 2019

- **[sujet du devoir personnel 2019](examens)**
- Date-limite: dimanche 2 juin à 23h55

## Access to training material

- Web: <https://du-bii.github.io/module-6-Integrative-Bioinformatics/>
- Github (sources): <https://github.com/DU-Bii/module-6-Integrative-Bioinformatics/>


## Teaching material

| Topics | Trainers  | Access |
|--------------------------------------------|----------------------------|------------|
| Introduction to the course + functional annotation of gene sets | Jacques van Helden | [Seance1](Session1) |
| Integrating multi-omics data with multi-level matrix factorisation | Laura Cantini, Sébastien Déjean and Jérôme Mariette | [Seance2-3](Session2-3) |
| Network Analysis with Cytoscape, session I | Anaïs Baudot & Costas Boulyakis | [Seance4](Session4) |

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


### Session 1: Functional interpretation of gene sets

[Présentation](Session1/DU-Bii_2019_m6s1_Integrative-bioinformatics-intro.pdf)

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

### Sessions 2 and 3: Integrating multi-omics data with multi-level matrix factorisation
        
| Contenu | HTML | pdf | Rmd | R |
|--------------------------------------------------|------|------|-----|-----|
| Presentation Laura Cantini |  | [Slides](Session2-3/Cantini_DU-Bii_module6.pdf) |  |
| Presentation Sébastien Dejean et Jérôme Mariette |  | [Slides](Session2-3/DUBii_SD_JM.pdf) |  |
| MixOmics |  | [Slides](Session2-3/slide_mixOmics_2018.pdf) |  | [R](Session2-3/TP_mixOmics_DUBii.R) |
| Practical MOFA | [html](Session2-3/practical_MOFA.html) |  | [Rmd](https://raw.githubusercontent.com/DU-Bii/module-6-Integrative-Bioinformatics/master/2019/Session2-3/practical_MOFA.Rmd) |
| Practical mixKernel | [html](Session2-3/TP_mixKernel_DUBii.html) |  | [Rmd](https://raw.githubusercontent.com/DU-Bii/module-6-Integrative-Bioinformatics/master/2019/Session2-3/TP_mixKernel_DUBii.Rmd) |

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
- Chronic Lymphoblastic Leukemia (CLL)
- metagenomics data (Jérôme Mariette)

### Session 4: Network Analysis with Cytoscape, session I

*Teachers: Anaïs Baudot and Costas Bouyioukos*

- Introduction to network sciences in biology
- Practical with Cytoscape
    - Basics on human interactome
    - Basics on bacterial regulons
    - Keywords: interactome, regumone, network visualisation and topological analyses

- Slides: [SlidesM6S4.pdf](Session4/SlidesM6S4.pdf)
- Practicals: [TutoM6S4.pdf](Session4/TutoM6S4.pdf)


### Session 5: WGCNA, network inference

*Teachers: Costas Bouyioukos and Anaïs Baudot*

- Introduction to gene co-expression networks.
- Introduction: inferring networks from \*omics data, clustering for Gene Regulatory Networks.
- Introduction to WGCNA and the concept of eigengenes.
- Practical with R
- Inferrence of co-expression networks with the WGCNA package
    
- Slides: [SlidesM6S5.pdf](Session5/WGCNA_seance5.pdf)

 A document to familiarise with the terminology of correlation networks and WGCNA can be found [here](https://horvath.genetics.ucla.edu/html/CoexpressionNetwork/Rpackages/WGCNA/Tutorials/Simulated-00-Background.pdf)

 The document containing all the R code for the TP, together with explanations and output graphs can is here: [Network_Inference_with_WGCNA.html](Session5/Network_Inference_with_WGCNA.html)

Conclusions and mentions of Inferelator and cMonkey, two network inference tools which combine RNA-seq and Chip-Seq data.


### Session 6: Network Analysis with Cytoscape, session II

*Teachers: Anaïs Baudot and Costas Bouyioukos*

- Introduction to Network algorithms (measures, guilt-by-association, clustering), slides [here](https://github.com/DU-Bii/module-6-Integrative-Bioinformatics/blob/master/Session6/Session6.pdf)

- Practical with Cytoscape, the tutorial for parts 1 and 2 can be found [here](https://github.com/DU-Bii/module-6-Integrative-Bioinformatics/blob/master/Session6/Tutorial%20-%20Module%206%20-%20Seance%206.pdf)

       - Integrating networks: multiplex networks     
       - Integrating expression data in networks: jActive module
       - Integrating knowledge in networks: Enrichmap

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

![](../img/CC-BY-SA.png)


This content is released under the [Creative Commons Attribution-ShareAlike 4.0 ](https://creativecommons.org/licenses/by-sa/4.0/deed.en) (CC BY-SA 4.0) license. See the bundled [LICENSE](LICENSE.txt) file for details.

Ce contenu est mis à disposition selon les termes de la licence [Creative Commons Attribution - Partage dans les Mêmes Conditions 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/deed.fr) (CC BY-SA 4.0). Consultez le fichier [LICENSE](LICENSE.txt) pour plus de détails.
