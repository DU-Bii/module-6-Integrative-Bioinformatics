# [DU-Bii](https://du-bii.github.io/accueil/) module 6: Integrative Bioinformatics

----------------------------------------------------------------


## Access to training material

- Web: <https://du-bii.github.io/module-6-Integrative-Bioinformatics/2020/>
- Github (sources): <https://github.com/DU-Bii/module-6-Integrative-Bioinformatics/2020/>


## Teaching material

| Topics | Trainers  | Teaching material |
|--------------------------------------------|----------------------------|------------|
| Analyse multi-omique par factorisation multi-niveaux de matrices | Laura Cantini, Sébastien Déjean and Jérôme Mariette |  |
| Network Analysis & Cytoscape | Anaïs Baudot |  |
| Web semantique, représentation des connaissances | Alban Gaignard | |
| Network Inference | Costas Boulyakis |  |

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



## Table of contents

### Sessions 1 and 2: Integrating multi-omics data with multi-level matrix factorisation
        
| Contenu | HTML | pdf | Rmd | R |
|--------------------------------------------------|------|------|-----|-----|
| Presentation Laura Cantini |  | [Slides](Session2-3/Cantini_DU-Bii_module6.pdf) |  |
| Presentation Sébastien Dejean et Jérôme Mariette |  | [Slides](Session2-3/DUBii_SD_JM.pdf) |  |
| MixOmics |  | [Slides](Session2-3/slide_mixOmics_2018.pdf) |  | [R](Session2-3/TP_mixOmics_DUBii.R) |
| Practical MOFA | [html](Session2-3/practical_MOFA.html) |  | [Rmd](https://raw.githubusercontent.com/DU-Bii/module-6-Integrative-Bioinformatics/master/Session2-3/practical_MOFA.Rmd) |
| Practical mixKernel | [html](Session2-3/TP_mixKernel_DUBii.html) |  | [Rmd](https://raw.githubusercontent.com/DU-Bii/module-6-Integrative-Bioinformatics/master/Session2-3/TP_mixKernel_DUBii.Rmd) |

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

### Session 3: Network Analysis & Cytoscape

*Teachers: Anaïs Baudot*

- Introduction to network sciences in biology
- Practical with Cytoscape
    - Basics on human interactome
    - Keywords: interactome, regumone, network visualisation and topological analyses

- Slides: [SlidesM6S4.pdf](Session4/SlidesM6S4.pdf)
- Practicals: [TutoM6S4.pdf](Session4/TutoM6S4.pdf)

### Session 4: Web sémantique et représentation des connaissances

*Teachers: Alban Gaignard*


### Session 5: WGCNA, network inference

*Teachers: Costas Bouyioukos*

- Introduction to gene co-expression networks.
- Introduction: inferring networks from \*omics data, clustering for Gene Regulatory Networks.
- Introduction to WGCNA and the concept of eigengenes.
- Practical with R
    - Inferrence of co-expression networks with the WGCNA package
    
- Slides: <a href="https://github.com/DU-Bii/module-6-Integrative-Bioinformatics/blob/master/Session5/WGCNA_seance5%20(1).pdf">SlidesM6S5.pdf</a>  


 The document containing all the R code for the TP, together with explanations and output graphs can is here: [Network_Inference_with_WGCNA.html](Session5/Network_Inference_with_WGCNA.html)

 A document to familiarise with the terminology of correlation networks and WGCNA can be found [here](https://horvath.genetics.ucla.edu/html/CoexpressionNetwork/Rpackages/WGCNA/Tutorials/Simulated-00-Background.pdf)

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
