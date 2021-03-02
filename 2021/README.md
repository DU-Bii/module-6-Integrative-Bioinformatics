# [DU-Bii](https://du-bii.github.io/accueil/) module 6: Integrative Bioinformatics

----------------------------------------------------------------


## Access to training material

- Web: <https://du-bii.github.io/module-6-Integrative-Bioinformatics/2021/>
- Github (sources): <https://github.com/DU-Bii/module-6-Integrative-Bioinformatics/2021/>


## Teaching material

| Topics | Trainers  | Teaching material |
|--------------------------------------------|----------------------------|------------|
| Analyse multi-omique par factorisation multi-niveaux de matrices (MOFA) | Laura Cantini (helper Olivier Sand, Anaïs Baudot)| [Sessions 1](session1-2)  |
| Analyse multi-omique par factorisation multi-niveaux de matrices (mixOmics/mixKernel) | Sébastien Déjean and Jérôme Mariette (à distance) (helper Olivier Sand) | [Sessions 2](session1-2)  |
| Web semantique, représentation des connaissances | Alban Gaignard (helper Olivier Sand) |[Session 3](session3)  |
| ProMetIS | Etienne Thévenot (helper Olivier Sand) |[Session 4](session4)  |
| Network Analysis & Cytoscape | Anaïs Baudot (helper Olivier Sand)| [Session 5](session5) |
| Network Inference & WGCNA | Costas Bouyioukos (helper ?) | [Session 6](session6)  |

## Description

This course takes place in the 1-month training "Diplôme Universitaire en Bioinformatique Intégrative" ([DU-Bii](https://du-bii.github.io/accueil/)) organised by Université Paris-Diderot and the Institut Français de Bioinformatique (IFB).

<!--- 
### Pre-requisites

All participants are encouraged to follow the two introductory videos and read the review in the Paris Diderot course "Moodle" page.
<https://moodlesupd.script.univ-paris-diderot.fr/mod/page/view.php?id=167920>

### Skills acquired during this course

At the end of this course, trainees should be able to do the following: $

- ...


### Concepts covered

- ....

--->

## Table of contents

### Sessions 1 and 2: Integrating multi-omics data with multi-level matrix factorisation
        
| Contenu | HTML | pdf | Rmd | R |
|--------------------------------------------------|------|------|-----|-----|
| Presentation Laura Cantini |  | <!---[Slides](../2019/Session2-3/Cantini_DU-Bii_module6.pdf) --> |  |
| Practical MOFA |<!--- [html](../2019/Session2-3/practical_MOFA.html) |  | [Rmd](https://raw.githubusercontent.com/DU-Bii/module-6-Integrative-Bioinformatics/master/2019/Session2-3/practical_MOFA.Rmd) --> |
| Presentation Sébastien Dejean et Jérôme Mariette |  | <!---[Slides](../2019/Session2-3/DUBii_SD_JM.pdf) --> |  |
| MixOmics |  |<!--- [Slides](../2019/Session2-3/slide_mixOmics_2018.pdf)--> |  | <!---[R](../2019/Session2-3/TP_mixOmics_DUBii.R)  -->|
| Practical mixKernel | <!---[html](../2019/Session2-3/TP_mixKernel_DUBii.html)--> |  | <!---[Rmd](https://raw.githubusercontent.com/DU-Bii/module-6-Integrative-Bioinformatics/master/2019/Session2-3/TP_mixKernel_DUBii.Rmd) --> |

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


### Session 3: Web sémantique et représentation des connaissances

*Teachers: Alban Gaignard*


### Session 4: ProMetIS : un exemple d’intégration de données protéomiques et métabolomiques

*Teachers: Etienne Thévenot*


### Session 5: Network Analysis & Cytoscape

*Teachers: Anaïs Baudot*

- Introduction to network sciences in biology
<!---
    - Vidéo cours 1: [Cours](https://www.youtube.com/watch?v=Khv0tK6RGew&feature=youtu.be)
    - Slides cours 1: [Slides](session3/Cours1_DUBii_M6_Networks.pdf)
    - Vidéo cours 2: [Cours](https://www.youtube.com/watch?v=V5jizup7TDo&feature=youtu.be)
    - Slides cours 2: [Slides](session3/Cours2_DUBii_M6_Networks.pdf)
 -->
- Practical with Cytoscape
    - Basics on human interactome
    - Keywords: interactome, regumone, network visualisation and topological analyses
    - Practicals: <!---[Tuto](session3/TPCytoscape.pdf)-->


### Session 6: WGCNA, network inference

*Teachers: Costas Bouyioukos*

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

1. [Anaïs Baudot](https://orcid.org/0000-0003-0885-7933), CNRS, Marseille
2. [Olivier Sand](https://orcid.org/0000-0003-1465-1640), CNRS, Lille
3. [Jacques van Helden](https://orcid.org/0000-0002-8799-8584), Institut Français de Bioinformatique, Aix-Marseille Université


### Other teachers

1. Laura Cantini
2. Sébastien Déjean
3. Jérôme Mariette
4. Alban Gaignard
5. Etienne Thévenot
6. Costas Bouyioukos

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
