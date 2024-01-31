<img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white">  <img src ="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white"> trstrstrstrststrstrstrstsr

![Dark Blue Modern Geometric LinkedIn Banner (3)](https://user-images.githubusercontent.com/92512533/228205919-8659c90d-ab28-4174-8301-e2a6e2e80112.gif)

<p align="justify">

Welcome to the GitHub repository related to our recent publication **Single cell analysis of the postnatal dorsal V-SVZ reveals a role for Bmpr1a-signaling in silencing pallial germinal activity** _Guillaume Marcy<sup>1</sup>, Louis Foucault<sup>1</sup>, Elodie Babina, Timothy Capeliez, Emeric Texeraud, Stefan Zweifel, Christophe Heinrich, Hector Hernandez-Vargas, Carlos Parras, Denis Jabaudon, <ins> Olivier Raineteau</ins>, <a href="https://www.science.org/doi/10.1126/sciadv.abq7553"> Science Advances </a>,_ 2023  :

 </p>

<h1 align="center"> Single-cell analysis reveals Bmpr1a regulates V-SVZ germinal activity </h1>

  <p align="center">
    This website supports documentation and script so that interested readers may reproduce the major results presented in the study.
    <br />
    <a href="https://github.com/OlivierRaineteauSBRI/scRNASeq"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/OlivierRaineteauSBRI/scRNASeq/issues">Report Bug</a>
    ·
    <a href="https://github.com/OlivierRaineteauSBRI/scRNASeq/issues">Request Feature</a>
  </p>
</div>

## Abstract

<p align="justify">
The ventricular-subventricular zone (V-SVZ) is the largest neurogenic region of the postnatal forebrain, containing neural stem cells (NSCs) that emerge from both the embryonic pallium and subpallium. Despite of this dual origin, glutamatergic neurogenesis declines rapidly after birth, while GABAergic neurogenesis persists throughout life. We performed single-cell RNA-sequencing (scRNA-Seq) of the postnatal dorsal V-SVZ for unravelling the mechanisms leading to pallial lineage germinal activity silencing. We show that pallial NSCs enter a state of deep quiescence, characterized by high BMP-signaling, reduced transcriptional activity and Hopx expression, whilst in contrast, subpallial NSCs remain primed for activation. Induction of deep quiescence is paralleled by a rapid blockade of glutamatergic neurons production and differentiation. Finally, manipulation of Bmpr1a demonstrates its key role in mediating these effects. Together, our results highlight a central role of BMP-signaling in synchronizing quiescence induction and blockade of neuronal differentiation to rapidly silence pallial germinal activity after birth.
</p>

## Files you'll find here 
###  <a href="https://github.com/OlivierRaineteauSBRI/scRNASeq/tree/main/Scripts">In Scripts</a>
- ``Fig1.Rmd`` : to retrieve figure 1.
- ``Fig1G_Velocity.Rmd`` : to retrieve figure 1G linked to velocity.
- ``Fig2.Rmd`` : to retrieve figure 2. 
- ``Fig3.Rmd`` : to retrieve figure 3. 
- ``Fig4.Rmd`` : to retrieve figure 4.
- ``Fig5.Rmd`` : to retrieve figure 5.
- ``Fig6.Rmd`` : to retrieve figure 6.
- ``FigS1.Rmd`` : to retrieve suppl 1.
- ``FigS2.Rmd`` : to retrieve suppl 2.
- ``FigS3.Rmd`` : to retrieve suppl 3.
- ``FigS4.Rmd`` : to retrieve suppl 4.
- ``FigS5.Rmd`` : to retrieve suppl 5.
- ``FigS6.Rmd`` : to retrieve suppl 6.
- ``FigS7.Rmd`` : to retrieve suppl 7.
- ``SVZ.Visium.Rmd`` : brief analysis of visium object.

### <a href="https://github.com/OlivierRaineteauSBRI/scRNASeq/tree/main/Objects">In Objects</a>
- ``P12_dSVZ_Seq.rds`` : the complete seurat object of P12 dSVZ scRNAseq.
- ``P22_dSVZ_Seq.rds`` : the complete seurat object of P22 dSVZ scRNAseq.
- ``P2_dSVZ_Seq.rds`` : the complete seurat object of P2 dSVZ scRNAseq.
- ``P2_P12_P22_dSVZ_Seq.rds`` : the complete seurat object of P2, P12, P22 dSVZ scRNAseq.
- ``SVZ.Visium.rds`` : the complete seurat object of E17.5, P2, P12 and P22 visium.
- ``Merge_Loo.rds`` : the complete merged seurat object of Loo et al. datasets.
- ``Loo_Marcy.rds`` : the complete integrated seurat object between Loo et al. dataset and our P12 dataset.
- ``Mizrak2020_Marcy.rds`` : the complete integrated seurat object of Mizrak et al. dataset and our P12 dataset.
- ``P12_Neurons.rds`` : the complete seurat object of P12 neuronal cells.
- ``aNSCs.rds`` : the complete seurat object of P12 activated neural stem cells.
- ``Lineage_GLU.rds`` : the complete seurat object of P2, P12, P22 neuronal GLU lineage.
- ``Slingshot`` : the folder containing slingshot objects of pallial and subpallial trajectories at P12.
- ``Raw`` : the folder containing raw data of P2, P12, P22 datasets.
- ``DotPlot`` : the folder containing files related to Figure 5E.
- ``Velocyto`` : the folder containing files related to Figure 1G.


## Prerequisites 

* [Python](https://www.python.org)
* [Velocyto](http://velocyto.org/)
* [RStudio](https://www.rstudio.com)
* [Seurat](https://satijalab.org/seurat/index.html)
* [Rmagic](https://github.com/cran/Rmagic)
* [ClusterProfiler](https://guangchuangyu.github.io/software/clusterProfiler/)
* [ClusterMap](https://xgaoo.github.io/ClusterMap/ClusterMap.html)
* [Slingshot](https://github.com/kstreet13/slingshot)


## To get started

Download and follow each ``.Rmd`` to retrieve our bioinformatic figures. For new beginners, make sure you download and run the script ``Install_packages.Rmd`` before starting. To download all of the rds objects used, please follow the instructions :
- download the github directory
- (for example) within "P12_dSVZ_Seq" directory, open the ``linux_command`` file on textbook
- open your shell, and type ``cd path/to/P12_dSVZ_Seq``
- copy the linux command inside the shell; if you are on Windows replace ``cat`` by ``type`` and change the backslash to '/'
- run it and enjoy the final object

## Authors

**Olivier Raineteau**  _corresponding author_
- [Profile](https://github.com/OlivierRaineteauSBRI "Olivier Raineteau")
- [Email](mailto:olivier.raineteau@inserm.fr?subject=Hi% "Hi!")

**Guillaume Marcy** _first co-author_
- [Profile](https://github.com/GuillaumeMarcy "Guillaume Marcy")
- [Email](mailto:guillaume.marcy@univ-lyon1.fr?subject=Hi% "Hi!")

**Louis Foucault** _first co-author_
- [Profile](https://github.com/LouisFoucault "Louis Foucault") 
- [Email](mailto:louis.foucault@inserm.fr?subject=Hi% "Hi!")

**Elodie Babina** _second author_
- [Profile](https://github.com/ElodieBabina "Elodie Babina") 
- [Email](mailto:elodie.babina@inserm.fr?subject=Hi% "Hi!")

**Timothy Capeliez** _third author_
- [Profile](https://github.com/TimothyCapeliez "Timothy Capeliez") 
- [Email](mailto:timothy.capeliez@inserm.fr?subject=Hi% "Hi!")


## Questions
<img src="https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg">
For any question or issue, please contact <a href="mailto:olivier.raineteau@inserm.fr?"> Olivier Raineteau
