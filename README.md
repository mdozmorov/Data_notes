# Data related notes

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs) [![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) 

A continualy expanding collection of data-related notes. Please, [contribute and get in touch](CONTRIBUTING.md)! See [MDmisc notes](https://github.com/mdozmorov/MDmisc_notes) for other programming and genomics-related notes.

# Table of content

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Datasets](#datasets)
- [Datasets in R](#datasets-in-r)
- [Genomics](#genomics)
- [Machine learning](#machine-learning)
  - [Imaging](#imaging)
- [COVID-19](#covid-19)
- [Text](#text)
- [Misc](#misc)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Datasets

- [Google dataset search](https://toolbox.google.com/datasetsearch) - search for any dataset. [Overview](https://www.blog.google/products/search/making-it-easier-discover-datasets/)

- [20 Big Data Repositories You Should Check Out](https://www.datasciencecentral.com/profiles/blogs/20-big-data-repositories-you-should-check-out-1) - blog post from Data Science Central

- [Registry of Open Data on AWS](https://registry.opendata.aws/) - Amazon-hosted datasets. Genomics, satellite imagery, population statistics, many more

## Datasets in R

- `library(help = "datasets")` - shows built-in R datasets

- A list of over 1,000 datasets available in R packages, curated by @VincentAB. https://vincentarelbundock.github.io/Rdatasets/datasets.html

- `dslabs` - Data Science Labs - Datasets and functions that can be used for data analysis practice, homework and projects in data science courses and workshops. 26 datasets are available for case studies in data visualization, statistical inference, modeling, linear regression, data wrangling and machine learning. Made by Rafael Irizarry and Amy Gill. https://cran.r-project.org/web/packages/dslabs/index.html

## Genomics

- [OmicsDI](https://www.omicsdi.org/) - Omics Discovery Index platform for searching multi-omics datasets. Integrates proteomics, genomics, metabolomics, and transcriptomics datasets. Includes data from multiple databases, from GEO and EGA to LINCS, dbGaP, more. Search by organism, disease, tissue, gene identifiers, keywords.
   - Perez-Riverol, Yasset. “[Discovering and Linking Public Omics Data Sets Using the Omics Discovery Index](https://doi.org/10.1038/nbt.3790).” NATURE BIOTECHNOLOGY 35, no. 5 (2017)

- [FANTOM6](https://fantom.gsc.riken.jp/6/) data update. New noncoding RNA annotations, remapped [miRNA atlases](https://fantom.gsc.riken.jp/zenbu/reports/#FANTOM_miRNA_atlas), new [Transcription initiation peaks](https://zenodo.org/record/3856413#.X8U8LGRKgoI) data, [MotifActivity](https://fantom.gsc.riken.jp/5/suppl/Alam_et_al_2020/), KD of 285 lncRNAs - expression and phenotyping data. [RADICL-seq - RNA-chromatin interaction](https://fantom.gsc.riken.jp/6/datafiles/RADICL-Seq/) BEDPE data. [RefEx reference expression dataset](https://refex.dbcls.jp/index.php?lang=en), and more in the paper.
    - Abugessaisa, Imad, Jordan A Ramilowski, Marina Lizio, Jesicca Severin, Akira Hasegawa, Jayson Harshbarger, Atsushi Kondo, et al. “[FANTOM Enters 20th Year: Expansion of Transcriptomic Atlases and Functional Annotation of Non-Coding RNAs](https://doi.org/10.1093/nar/gkaa1054)”

- [Go Get Data (GGD)](https://gogetdata.github.io/recipes.html#recipes) - access to scientific data via Conda recipes. BED files of various genomic features, from cancer genes to structural variants and more. Homo Sapiens, Mus Musculus, Danio Rerio, various genomic assemblies. 
- Cormier, Michael, Jonathan Belyeu, Brent S Pedersen, Joseph Brown, Johannes Koster, and Aaron Quinlan. “[Go Get Data (GGD): Simple, Reproducible Access to Scientific Data](https://doi.org/10.1101/2020.09.10.291377).” Preprint. Bioinformatics, September 11, 2020

- Human Pangenome Reference Consortium - HG002 Data Freeze (v1.0). Genome sequencing data using different technologies (PacBio, Oxford Nanopore, Hi-C, Strand-seq, 10X Genomics, BioNano, Illumina). https://github.com/human-pangenomics/HG002_Data_Freeze_v1.0

- ATAC-seq in mouse tissues. Kundaje lab pipeline, reproducible peaks.https://figshare.com/collections/An_ATAC-seq_atlas_of_chromatin_accessibility_in_mouse_tissues/4436264/1
    - Liu, Chuanyu, Mingyue Wang, Xiaoyu Wei, Liang Wu, Jiangshan Xu, Xi Dai, Jun Xia, et al. “An ATAC-Seq Atlas of Chromatin Accessibility in Mouse Tissues.” Scientific Data 6, no. 1 (December 2019): 65. https://doi.org/10.1038/s41597-019-0071-0.


- `b3get` - a python module to download Broad Bioimage Benchmark Collection images. https://github.com/psteinb/b3get

- `PMLB` - A large, curated repository of benchmark datasets for evaluating supervised machine learning algorithms. https://github.com/EpistasisLab/penn-ml-benchmarks
   - Olson, Randal S., William La Cava, Patryk Orzechowski, Ryan J. Urbanowicz, and Jason H. Moore. “PMLB: A Large Benchmark Suite for Machine Learning Evaluation and Comparison.” BioData Mining 10 (2017): 36. https://doi.org/10.1186/s13040-017-0154-4.

- https://discover.repositive.io/ - Google for genomics

- `PharmacoGx` - Analysis of Large-Scale Pharmacogenomic Data, https://bioconductor.org/packages/release/bioc/html/PharmacoGx.html

- [datamicroarray](https://github.com/ramhiser/datamicroarray) - A collection of small-sample, high-dimensional microarray data sets to assess machine-learning algorithms and models

## Machine learning

- [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php) - Classical aggregator of well-curated datasets for machine learning

- 20 Big Data Repositories You Should Check Out. https://www.datasciencecentral.com/profiles/blogs/20-big-data-repositories-you-should-check-out-1

- `OpenML` - platform for sharing machine learning data, tasks, and experiments, API and an R package to access it. https://www.openml.org/home. mlr R package for machine learning in R.  https://mlr.mlr-org.com/
    - Casalicchio, Giuseppe, Jakob Bossek, Michel Lang, Dominik Kirchhoff, Pascal Kerschke, Benjamin Hofner, Heidi Seibold, Joaquin Vanschoren, and Bernd Bischl. “OpenML: An R Package to Connect to the Machine Learning Platform OpenML.” Computational Statistics, June 19, 2017. https://doi.org/10.1007/s00180-017-0742-2.

- Patent analysis using the Google Patents Public Datasets on BigQuery. https://github.com/google/patents-public-data

- Places to find CC0 photos and the like. https://github.com/jennybc/free-photos

- CORGIS Datasets Project - The Collection of Really Great, Interesting, Situated Datasets. https://think.cs.vt.edu/corgis/

-  Inter-university Consortium for Political and Social Research (ICPSR) provides leadership and training in data access, curation, and methods of analysis for the social science research community. https://www.icpsr.umich.edu/icpsrweb/ICPSR/

- U.S. General Services Administration. 2018. The home of the U.S. Government’s open data. https://www.data.gov/

- `PMLB` - A large, curated repository of benchmark datasets for evaluating supervised machine learning algorithms. https://github.com/EpistasisLab/penn-ml-benchmarks
   - Olson, Randal S., William La Cava, Patryk Orzechowski, Ryan J. Urbanowicz, and Jason H. Moore. “PMLB: A Large Benchmark Suite for Machine Learning Evaluation and Comparison.” BioData Mining 10 (2017): 36. https://doi.org/10.1186/s13040-017-0154-4.

### Imaging

- [Histology (CIMA) dataset](http://cmp.felk.cvut.cz/~borovji3/?page=dataset) - 2D histological microscopy tissue slices, stained with different stains, and landmarks denoting key-points in each slice. The [dataset-histology-landmarks](https://github.com/Borda/dataset-histology-landmarks) GitHub repo has Python code to work with this data

- Breast cancer image classification. Data from [Stanford Tissue Microarray Database (TMAD)](https://tma.im/cgi-bin/home.pl) and [Breast Cancer Histopathological Database (BreakHis)](https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/), >6K images. Different variants of ResNet and Inception architectures. Data augmentation (resizing, rotation, cropping, flipping). Training details. Classification into malignant and benign, or into subtypes. Can handle images at different magnifications. ResNet performs better. [GitHub repository](https://github.com/MachineLearning4Work/DeepBreastCancer) includes crawler to get images
    - M. Jannesari, M. Habibzadeh, H. Aboulkheyr, P. Khosravi, O. Elemento, M. Totonchi, and I. Hajirasouliha. “[Breast Cancer Histopathological Image Classification: A Deep Learning Approach.](https://doi.org/10.1109/BIBM.2018.8621307)” In 2018 IEEE International Conference on Bioinformatics and Biomedicine (BIBM), 2405–12, 2018

- [BACH, breast cancer histology images](https://iciar2018-challenge.grand-challenge.org/Home/) - Hematoxylin and eosin (H&E) stained breast histology microscopy and whole-slide images

- [Medical Data for Machine Learning](https://github.com/beamandrew/medical-data) - a curated list of medical data for machine learning, mostly imaging

- [ANTsRNet](https://github.com/ANTsX/ANTsRNet) - Medical image analysis framework merging ANTsR and deep learning. A collection of deep learning architectures ported to the R language and tools for basic medical image processing. Based on keras and tensorflow with cross-compatibility with our python analog ANTsPyNet


## COVID-19

- [owid/covid-19-data](https://github.com/owid/covid-19-data) - Data on COVID-19 (coronavirus) cases, deaths, hospitalizations, tests. All countries. Updated daily by Our World in Data. [Web site](https://ourworldindata.org/coronavirus)

- [COVID-19 RNA-Seq datasets](https://github.com/urmi-21/COVID-19-RNA-Seq-datasets) - A repository for sharing information on available COVID-19 RNA-Seq datasets. Links to GEO resources, and more 

- ["COVIDgenes" data portal](https://covidgenes.weill.cornell.edu), [Tweet by Chris Mason](https://twitter.com/mason_lab/status/1263838646593093632?s=20)

- [COVID-19 Crowd Generated Gene and Drug Set Library](https://amp.pharm.mssm.edu/covid19/) - experimental, computational, twitted drug sets, gene sets, collected by Avi Ma'ayan's lab. Analysis with EnrichR, Venn diagrams

- [COVID19: Coronavirus COVID-19 (2019-nCoV) Epidemic Datasets](https://cran.r-project.org/web/packages/COVID19/index.html) - Unified tidy format datasets of COVID-19 (2019-nCoV) epidemic across several sources. The data are downloaded in real-time, cleaned and matched with exogenous variables. [Tweet](https://twitter.com/strnr/status/1255066365012082690?s=20), [COVID-19 Data Hub](https://covid19datahub.io)

- COVID-19 Open Research Dataset (CORD-19) - full-text of COVID-related papers, PubMed, bioRxiv & medRxiv, JSON format, downloadable https://pages.semanticscholar.org/coronavirus-research

- Novel Coronavirus (COVID-19) Cases, provided by JHU CSSE, https://systems.jhu.edu/research/public-health/ncov/, https://github.com/CSSEGISandData/COVID-19

- Useful projects and resources for COVID-19. https://github.com/soroushchehresa/awesome-coronavirus

- Up-to-date data resources, analysis tools, and visualizations for COVID-19 pandemic data https://seandavi.github.io/sars2pack, https://github.com/seandavi/sars2pack

- An ongoing repository of data on coronavirus cases and deaths in the U.S. https://www.nytimes.com/interactive/2020/us/coronavirus-us-cases.html, https://github.com/nytimes/covid-19-data

- Open-Access Data and Computational Resources to Address COVID-19 https://datascience.nih.gov/covid-19-open-access-resources

- Novel Coronavirus 2019 time series data on cases https://datahub.io/core/covid-19, https://github.com/datasets/covid-19

- Repository of COVID-19 forecasts in the US, https://github.com/reichlab/covid19-forecast-hub

- The coronavirus R package provides a tidy format dataset of the 2019 Novel Coronavirus COVID-19 (2019-nCoV) epidemic. The raw data pulled from the Johns Hopkins University Center for Systems Science and Engineering (JHU CCSE) Coronavirus repository. https://github.com/RamiKrispin/coronavirus

- COVID-19 Italia - Monitoraggio situazione. https://github.com/pcm-dpc/COVID-19

- Time Series of the Covid19 epidemic data in Italy. https://github.com/DavideMagno/ItalianCovidData

## Text

- [Gitenberg](https://gitenberg.org/) is a collaborative, open source community curating and publishing highly usable and attractive ebooks in the public domain. Our books are free to use by anyone for any purpose. They contain detailed metadata and are accessible in a wide variety of formats. https://gitenberg.org/

## Misc

- Publishing data
    - "Scientific Data" - https://www.nature.com/content/5th-anniversary/index.html
    - "BMC Research Notes" - https://bmcresnotes.biomedcentral.com/about/introducing-data-notes

- Patent analysis using the Google Patents Public Datasets on BigQuery. https://github.com/google/patents-public-data

- `b3get` - a python module to download Broad Bioimage Benchmark Collection images. https://github.com/psteinb/b3get

- Places to find CC0 photos and the like. https://github.com/jennybc/free-photos

- Data Notes - making it easier to publish your hidden data. https://bmcresnotes.biomedcentral.com/about/introducing-data-notes
