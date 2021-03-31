# [DU-Bii](https://du-bii.github.io/accueil/) module 6: Integrative Bioinformatics

----------------------------------------------------------------


## Access to training material

<!--- - Web: <https://du-bii.github.io/module-6-Integrative-Bioinformatics/2021/>--->
- Github (sources): <https://github.com/DU-Bii/module-6-Integrative-Bioinformatics/tree/master/current>


## Teaching material

| Topics | Trainers  | Teaching material |
|--------------------------------------------|----------------------------|------------|
| Analyse multi-omique par factorisation multi-niveaux de matrices (MOFA) | Laura Cantini (helpers: Anaïs Baudot, Claire Lansonneur, Olivier Sand)| [Session 1](session1)  |
| Analyse multi-omique par factorisation multi-niveaux de matrices (mixOmics/mixKernel) | Sébastien Déjean and Jérôme Mariette (à distance) (helpers: Etienne Thévenot, Claire Lansonneur, Olivier Sand) | [Session 2](session2)  |
| Web semantique, représentation des connaissances | Alban Gaignard (helper: Olivier Sand) |[Session 3](session3)  |
| ProMetIS: : un exemple d’intégration de données protéomiques et métabolomiques | Etienne Thévenot (helpers: Camilo Broc, Olivier Sand) |[Session 4](session4)  |
| Network Analysis & Cytoscape | Anaïs Baudot (helpers: Costas Bouyioukos, Claire Lansonneur, Olivier Sand)| [Session 5](session5) |
| Network Inference & WGCNA | Costas Bouyioukos (helpers: Anaïs Baudot, Claire Lansonneur, Olivier Sand) | [Session 6](session6)  |

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

### Session 1: Integrating multi-omics data with multi-level matrix factorisation

*Teacher: Laura Cantini*

Concepts:

- Integrative bioinformatics approaches and their application to cancer
       - Motivation  
       - Which approach to answer which question (subsetting, modules, pathways) ?  
       - Main methodologies: networks, matrix factorisation  

Practical:

- MOFA

Datasets:
- Chronic Lymphoblastic Leukemia (CLL)


### Session 2: Integrating multi-omics data with multi-level matrix factorisation

*Teachers: Sébastien Déjean, Jérôme Mariette*

Concepts:

- Principles of multi-level matrix factorisation (Sébastien Déjean)
- Kernel-based approaches (Jérôme Mariette)

Practical:

- mixOmics
- JM tools (please specify)

Datasets:
- Chronic Lymphoblastic Leukemia (CLL)
- metagenomics data (Jérôme Mariette)

### Session 3: Web sémantique et représentation des connaissances

*Teacher: Alban Gaignard*


### Session 4: ProMetIS : un exemple d’intégration de données protéomiques et métabolomiques

*Teacher: Etienne Thévenot*


### Session 5: Network Analysis & Cytoscape

*Teacher: Anaïs Baudot*

- Introduction to network sciences in biology

<!---
    - Vidéo cours 1: [Cours](https://www.youtube.com/watch?v=Khv0tK6RGew&feature=youtu.be)
    - Slides cours 1: [Slides](session3/Cours1_DUBii_M6_Networks.pdf)
    - Vidéo cours 2: [Cours](https://www.youtube.com/watch?v=V5jizup7TDo&feature=youtu.be)
    - Slides cours 2: [Slides](session3/Cours2_DUBii_M6_Networks.pdf)
 -->
 
- Practical with Cytoscape
    - Basics on human interactome
    - Keywords: interactome, regulome, network visualisation and topological analyses
    - Practicals: <!---[Tuto](session3/TPCytoscape.pdf)-->


### Session 6: WGCNA, network inference

*Teacher: Costas Bouyioukos*

- Contents:
  - Introduction to gene co-expression networks.
  - Introduction to WGCNA and the concept of eigengenes.
  - Introduction: inferring networks from \*omics data, clustering for Gene Regulatory Networks.
    - Slides: [SLidesM6S5](../2020/session5/WGCNA_seance5.pdf)

Before the TP: Must read [this](https://horvath.genetics.ucla.edu/html/CoexpressionNetwork/Rpackages/WGCNA/Tutorials/Simulated-00-Background.pdf) document to familiarise with the terminology of correlation networks and WGCNA 

- Particulars [please read here](session6/README.md)

- Practical with R
  - Inferrence of co-expression network modules with the WGCNA package
  - Document containing R code for the TP, together with explanations and output graphs can be here: [Network Inference with WGCNA](session6/Network Inference with WGCNA.r)


----------------------------------------------------------------

## Credits

### Course coordinators

1. [Anaïs Baudot](https://orcid.org/0000-0003-0885-7933), CNRS, Marseille
2. [Olivier Sand](https://orcid.org/0000-0003-1465-1640), CNRS, Lille
3. [Jacques van Helden](https://orcid.org/0000-0002-8799-8584), Institut Français de Bioinformatique, Aix-Marseille Université


### Other teachers / helpers

1. [Laura Cantini](https://orcid.org/0000-0001-6360-4440)
2. [Sébastien Déjean](https://orcid.org/0000-0001-9610-5306)
3. [Jérôme Mariette](https://orcid.org/0000-0002-6161-4044)
4. [Alban Gaignard](https://orcid.org/0000-0002-3597-8557)
5. [Etienne Thévenot](https://orcid.org/0000-0003-1019-4577)
6. [Costas Bouyioukos](https://www.linkedin.com/in/costasbouyioukos)
7. [Claire Lansonneur](https://fr.linkedin.com/in/claire-lansonneur)

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
