+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "custom"  # Do not modify this line!
active = true  # Activate this widget? true/false

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Teaching"
subtitle = ""

# Order that this section will appear in.
weight = 7

+++

Members of the lab are involved in teaching in the [Molecular Biotechnology Bachelor and Master Program](https://www.uni-heidelberg.de/courses/prospective/academicprograms/Molecular_Biotechnology_en_ba.html) at the university Heidelberg.

*************

### Bachelor thesis projects 2020

Here are some possible topics/projects for students wanting do to their bachelor thesis in our group during the summer semester 2020

#### Topic 1 : using single-cell data to interpret expression data from patients

Currently, more and more single-cell RNA-seq datasets are generated to increase the resolution of transcriptomics to the single-cell level. These datasets allow to understand the mixture of cell types within a tissue sample, and have been applied to create atlases of cell types from mouse embryos. On the other hand, there are thousands of bulk RNA-seq datasets available, which lack this resolution. We are working on implementing methods to re-interpret bulk datasets using single-cell information, and map for example patient data onto trajectories defined from single-cell expression. The project would be to contribute to the development of this method, in particular, the visualization of the data, and to apply it to a large set of pediatric tumor types. Comparison to datasets of normal tumor would be used to validate the method.

Main aspects:

* data analysis of sequencing data
* interactive visualization using Shiny
* comparative genomics (mouse/human)

References

* [The single-cell transcriptional landscape of mammalian organogenesis](http://www.nature.com/articles/s41586-019-0969-x)

#### Topic 2 : single-cell multi-omics integration using auto-encoder strategies

In the last three years, a new wave of technologies that allows profiling multiple molecular levels in single-cells  at the same time has come to light, e.g.;  CITEseq,  scCAT-seq, scNMT-seq, and scDam&T. Therefore it is crucial to develop new methods that take into account multiple layers of information at the same time to find clusters of cells, identify interactions between such layers and generate signatures or factors underlying the differences between cells.

Auto-encoders are a popular way to achieve dimensional reduction in a non-linear way, and extract relevant features from a dataset. This can be applied e.g. to a single-cell dataset and can be compared to a method based on linear approaches such as principal component analysis or non-negative matrix factorization. Such approaches can also be used to perform integration of multi-omics datasets. The goal of the project ist to explore the possibilities of auto-encoders for integrating single-cell RNA-seq and single-cell ATAC-seq from different in-house and published datasets, and compare the result of these integrations to other methods implemented e.g. in popular R packages or based on integrative non-matrix factorization

Main aspects:

* machine learning using python
* handling of large single-cell datasets

References

* check [this post](https://towardsdatascience.com/deep-learning-for-data-integration-46d51601f781)
* [High-throughput sequencing of the transcriptome and chromatin accessibility in the same cell](http://www.nature.com/articles/s41587-019-0290-0)
* [Autoencoder-based cluster ensembles for single-cell RNA-seq data analysis](https://doi.org/10.1101/773903)



#### Topic 3 : improving stratification of schizophrenia patients using multi-omics datasets

Schizophrenia is a severe disease whose diagnosis is mostly based on clinical interviews. Within a large consortium, we are working on improving this by identifying molecular signatures based on multiple omics data types, for example DNA methylation, and gene expression (RNA-seq). This integration will likely improve stratification of patients based on a single data type. The goal of the project would be to implement several strategies to perform this data integration (neural networks, integrative linear methods, ...) to identify patient groups and benchmark these approaches against single data stratification.

Main aspects

* data processing of primary RNA-seq and methylation data
* implementation of data integration strategies using neural networks and matrix factorization
* biological validation of the signatures using literature-based knowledge

References

* see for example [this paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0095875#s2)
* [Multi-view Factorization AutoEncoder with Network Constraints for Multi-omic Integrative Analysis](https://doi.org/10.1101/773903)


#### Topic 4 : differential "in-silico phenotyping" of tumor and normal tissues

The existence of large RNA-seq datasets of tumor tissue and matching normal tissue allows to conduct comparative studies. In particular, recent approaches allow to determine the activity of pathways and transcription factors from the transcriptomic data, which can be used to understand how pathways and master regulators are jointly activated or seem to have mutually exclusive patterns. In recent projects, we have for example described how mesenchymal phenotypes appear to be tightly related to pathway activation, for example the RAS pathway. The goal of the project is to conduct a large scale analysis of the activity patterns of pathways and master regulators, and to understand how these patterns are perturbed in tumor tissues compared with normal counterpart. We will in particular focus on processes related to ferroptosis across various tumor types to describe how this process is related to other pathways.

Main aspects

* large scale processing of transcriptomic data from TCGA
* implementation of statistical methods to study differential correlation
* visual representation of the data and interactive data mining.


*************

### Courses

#### Winter semester 2019 / 2020

* MoBi Bachelor 1. FS :  [Mathematik A](http://bioinfo.ipmb.uni-heidelberg.de/crg/mathea/)
* MoBi Bachelor 3. FS :  [Data Analysis Course](http://bioinfo.ipmb.uni-heidelberg.de/crg/datascience3fs/)
* MoBi Bachelor 5. FS :  [Bioinformatics 1](http://bioinfo.ipmb.uni-heidelberg.de/crg/bioinfo1/)

#### Summer semester 2019 

* MoBi Bachelor 2. FS :  [Mathematik B](http://bioinfo.ipmb.uni-heidelberg.de/crg/matheb/)
* MoBi Bachelor 4. FS :  [Data Analysis Project](https://datascience-mobi.github.io)
* MoBi Bachelor 6. FS :  [Bioinformatik 2](http://bioinfo.ipmb.uni-heidelberg.de/crg/bioinfo2/)

