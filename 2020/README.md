# [DU-Bii](https://du-bii.github.io/accueil/) module 6: Integrative Bioinformatics

----------------------------------------------------------------


## Access to training material

- Web: <https://du-bii.github.io/module-6-Integrative-Bioinformatics/2020/>
- Github (sources): <https://github.com/DU-Bii/module-6-Integrative-Bioinformatics/2020/>


## Teaching material

| Topics | Trainers  | Teaching material |
|--------------------------------------------|----------------------------|------------|
| Analyse multi-omique par factorisation multi-niveaux de matrices | Laura Cantini, Sébastien Déjean and Jérôme Mariette | [Session 1 & 2](session1-2)  |
| Network Analysis & Cytoscape | Anaïs Baudot | [Session 3](session3) |
| Web semantique, représentation des connaissances | Alban Gaignard |[Session 4](session4)  |
| Network Inference & WGCNA | Costas Bouyioukos | [Session 5](session5)  |

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

### Session 1 & 2: Integrating multi-omics data with multi-level matrix factorisation
        
| Contenu | HTML | pdf | Rmd | R |
|--------------------------------------------------|------|------|-----|-----|
| Presentation Laura Cantini |  | [Slides](../2019/Session2-3/Cantini_DU-Bii_module6.pdf) |  |
| Practical MOFA | [html](../2019/Session2-3/practical_MOFA.html) |  | [Rmd](https://raw.githubusercontent.com/DU-Bii/module-6-Integrative-Bioinformatics/master/2019/Session2-3/practical_MOFA.Rmd) |
| Presentation Sébastien Dejean et Jérôme Mariette |  | [Slides](../2019/Session2-3/DUBii_SD_JM.pdf)  |  |
| MixOmics |  | [Slides](../2019/Session2-3/slide_mixOmics_2018.pdf) |  | [R](../2019/Session2-3/TP_mixOmics_DUBii.R)  |
| Practical mixKernel | [html](../2019/Session2-3/TP_mixKernel_DUBii.html) |  | [Rmd](https://raw.githubusercontent.com/DU-Bii/module-6-Integrative-Bioinformatics/master/2019/Session2-3/TP_mixKernel_DUBii.Rmd)  |


*Teachers: Laura Cantini, Sébastien Déjean, Jérôme Mariette*

Concepts:

- Integrative bioinformatics approaches and their application to cancer
       - Motivation  
       - Which approach to answer which question (subsetting, modules, pathways) ?  
       - Main methodologies: networks, matrix factorisation  
- Principles of multi-level matrix factorisation (Sébastien Déjean)
- Kernel-based approaches (Jérôme Mariette)

Practicals:

- MOFA
- mixOmics
- JM tools (please specify)

Datasets:
- Chronic Lymphoblastic Leukemia (CLL)
- metagenomics data (Jérôme Mariette)


### Session 3: Network Analysis & Cytoscape

*Teacher: Anaïs Baudot*

- Introduction to network sciences in biology

    - Vidéo cours 1: [Cours](https://www.youtube.com/watch?v=Khv0tK6RGew&feature=youtu.be)
    - Slides cours 1: [Slides](session3/Cours1_DUBii_M6_Networks.pdf)
    - Vidéo cours 2: [Cours](https://www.youtube.com/watch?v=V5jizup7TDo&feature=youtu.be)
    - Slides cours 2: [Slides](session3/Cours2_DUBii_M6_Networks.pdf)
 
- Practical with Cytoscape
    - Basics on human interactome
    - Keywords: interactome, regulome, network visualisation and topological analyses
    - Practicals: [Tuto](session3/TPCytoscape.pdf)

### Session 4: Web sémantique et représentation des connaissances

*Teacher: Alban Gaignard*


### Session 6: WGCNA, network inference

*Teacher: Costas Bouyioukos*

- Particulars [please read here](session5/README.md)

- Introduction to gene co-expression networks.
- Introduction to WGCNA and the concept of eigengenes.
- Introduction: inferring networks from \*omics data, clustering for Gene Regulatory Networks.
    - Slides: [SLidesM6S5](session5/WGCNA_seance5.pdf)

 A document to familiarise with the terminology of correlation networks and WGCNA can be found [here](https://horvath.genetics.ucla.edu/html/CoexpressionNetwork/Rpackages/WGCNA/Tutorials/Simulated-00-Background.pdf)

- Practical with R
    - Inferrence of co-expression networks with the WGCNA package

 The document containing the R code for the TP, together with explanations and output graphs can is here: [Network_Inference_with_WGCNA.html](session5/Network_Inference_with_WGCNA.html)


Conclusions and mentions of Inferelator and cMonkey, two network inference tools which combine RNA-seq and Chip-Seq data.



----------------------------------------------------------------

## Credits

### Course coordinators

1. [Anaïs Baudot](https://orcid.org/0000-0003-0885-7933)
2. [Olivier Sand](https://orcid.org/0000-0003-1465-1640)
3. [Jacques van Helden](https://orcid.org/0000-0002-8799-8584)
4. [Costas Bouyioukos](https://orcid.org/0000-0002-7443-3736)


### Other teachers

1. [Laura Cantini](https://orcid.org/0000-0001-6360-4440)
2. [Sébastien Déjean](https://orcid.org/0000-0001-9610-5306)
3. [Jérôme Mariette](https://orcid.org/0000-0002-6161-4044)
4. [Alban Gaignard](https://orcid.org/0000-0002-3597-8557)

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
