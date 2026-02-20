# Bioinformatics Portfolio of Vanessa Gonzalez
Hi there 👋 I'm Vanessa, a bioinformatics scientist leveraging omics analyses to translate complex biological data into clear biological insights on disease-relevant biomarkers & mechanisms, supporting discovery and translational research with the ultimate goal of helping to treat patients. 

## 🧬 Featured Publication
**Gonzalez V, […]. Single-cell transcriptomics reveals Nodal-responsive cytoskeletal programs driving asymmetric heart morphogenesis.**  
*Nature Communications, under revision.*  [Manuscript Link](https://drive.google.com/file/d/1SpKT2Vmv1Zxjo50zVgzsNWeb-fehZVfD/view?usp=drive_link)  
- Goal: Conduct bioinformatics analyses of integrated single-cell transcriptomic datasets to identify disease-relevant biomarkers and gene programs driving vertebrate asymmetric heart development.
- Contributions: Generated the scRNA-seq datasets. Performed scRNA-seq preprocessing, QC filtering, normalization/scaling, clustering/annotation, etc. to process the data. Carried out extensive analysis of the scRNA-seq datasets, including differential expression analysis, multi-timepoint dataset integration, signaling pathway activity scoring, and pseudotime/trajectory inference, enabling identification of disease-relevant biomarkers and gene programs driving vertebrate asymmetric heart development. One such novel biomarker gene was knocked out with CRISPR-Cas9 *in vivo*, resulting in heart abnormalities and validating its functional impact on asymmetric heart development. 
- Tools: Seurat, Slingshot, AUCell, tidyverse, ggplot2, etc. 
- Code: https://github.com/vgonzalez1596/zebrafish-heart-scrnaseq

## 🔬 Additional Publications
**Patel AL, Gonzalez V, […]. Disrupted developmental signaling induces novel transcriptional states.**  
*Proceedings of the National Academy of Sciences (PNAS), 2025.*  [Publication Link](https://www.pnas.org/doi/10.1073/pnas.2418351122)  
- Contributions: Applied perturbation analysis to characterize transcriptional changes driven by ectopically increased MEK signaling during embryonic development and verified enrichment of vasculature-associated gene programs in these perturbed cells *in vivo*.

**Reneker BM, Gonzalez V, […]. A spatial-temporal transcriptomic atlas reveals a novel cell population in the left-right organizer.**  
*In preparation.*
- Contributions: Identified and isolated a rare cell type of interest from heterogeneous scRNA-seq datasets, characterizing both the cell type itself and identifying a novel cell population within containing unique transcriptional signatures. Additionally, mentored and trained a junior researcher with no prior coding experience, enabling her to independently perform bioinformatics analyses contributing to this study. 

## 🧪 Projects
### Project #1: Utilizing multi-omic integration to interrogate molecular etiology of leukemia.  
Applied multi-omic integration to interrogate the molecular etiology of leukemia, predicting patient mutation status using machine learning.
- Performed multi-omic integration of DNA mutation, DNA methylation, mRNA expression, and drug response data from 200 patients, trained the MOFA model, analyzed the integrated data via variance decomposition analysis to quantify the percentage of variance explained by each factor across each data modality, identified most important features according to feature weight, and utilized randomForest to predict the mutation status of a specific feature for patients missing that data point.
- Tools: R, Seurat, Banksy, msigdbr, ggplot2.
- Code: https://github.com/vgonzalez1596/multi-omic-integration-cancer

### Project #2: Spatial Transcriptomics Analysis of the Mouse Brain.  
Applied spatial transcriptomics to define gene expression in distinct regions of the mammalian mouse brain, enabling transcriptomic characterization of tissues such as the white matter and the hippocampus.
- Performed dataset processing, applied BANKSY algorithm to define biologically relevant domains of brain, analyzed the resulting clusters to determine differential gene expression in distinct regions of the brain, and utilized KEGG pathway enrichment analysis to determine enriched functions in distinct brain domains. 
- Tools: R, MOFA2, randomForest, ggplot2, tidyverse.
- Code: https://github.com/vgonzalez1596/spatial-transcriptomics-mouse-brain

### Project #3: Music Genre Classification Using Machine Learning.  
Applied machine learning to classify music genres based on quantitative song features from the Spotify Tracks dataset. 
- This was part of a Python training course I took at Princeton University to advance my practical programming skills and real-world data science applications. Here, I gained deep experience with core libraries such as pandas, NumPy, and matplotlib/seaborn for data handling and visualization. Built, evaluated, and optimized machine learning models using scikit-learn, including ensemble methods like Random Forest, and developed workflows with PyTorch. This course strengthened my ability to write clean, efficient Python code and apply ML techniques to complex datasets, preparing me to take on advanced data science and ML challenges in research and professional environments.
- Performed dataset filtering, feature preprocessing and scaling, model training and evaluation, and comparative testing of classification algorithms, achieving 86% prediction accuracy using a Random Forest classifier.
- Tools: Python, pandas, scikit-learn, numpy, matplotlib.
- Code: https://github.com/vgonzalez1596/music-genre-classifier

(More coming soon)

## 💻 Technical Skills
### Bioinformatics & Omics Analysis  
- Transcriptomics, Genomics, Proteomics
- Extensive single-cell RNA sequencing analysis experience 
- Biomarker and gene program discovery
- Differential expression analysis
- Dataset integration across conditions and timepoints
- Pathway enrichment analysis and pathway response scoring
- Trajectory and pseudotime inference
- Perturbation analysis
- Rare cell population discovery and characterization

### Programming & Data Science  
- Python: pandas, NumPy, Matplotlib, Seaborn, etc.
- R: Seurat, DESeq2, tidyverse, ggplot2, etc.
- Machine learning workflows (scikit-learn, Random Forest, PyTorch)
- Data processing, analysis, and visualization
- Reproducible computational pipelines and scripting
- Cloud computing environments

### Omics Platforms & Experimental Background  
- Single-cell RNA sequencing, NGS sequencing, and mass spectrometry
- Mammalian cell culture and vertebrate model systems experience
- Drug and genetic perturbation assays
- CRISPR gene editing and functional genomics
