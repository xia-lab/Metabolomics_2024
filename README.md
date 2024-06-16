# MetaboAnalyst 6.0: a unified platform for metabolomics data processing, analysis and interpretation

![alt text](https://raw.githubusercontent.com/xia-lab/Metabolomics_2024/main/Figure1.png)

For this workshop, we will be covering four main topics: 
* Auto-Optimized LC-MS/MS spectra processing and compound identification;
* Functional analysis from LC-MS peaks;
* Statistical Analysis of One-factor experimental design and complex metadata;
* Causal Analysis. 

Details for each workflow are below. 

#### <ins>Before you start, please download [MetaboAnalyst 6.0](https://doi.org/10.1093/nar/gkae253) and [MetaboAnalystR 4.0](https://www.nature.com/articles/s41467-024-48009-6) as references.</ins>

<br/>

# Slides In Sections

- [Introduction and Key Concepts](https://github.com/xia-lab/Metabolomics_2024/blob/main/slides/1_General_intro_MetaboAnalyst.pdf).
- [LC-MS/MS spectral processing and compound indentification](https://github.com/xia-lab/Metabolomics_2024/blob/main/slides/2_LC_MSMS_spec_section.pdf).
- [Functional analysis from LC-MS peaks](https://github.com/xia-lab/Metabolomics_2024/blob/main/slides/3_Functional_analysis_section.pdf).
- [Metabolomics Statistical Analysis of One-factor experimenta and complex metadatal design](https://github.com/xia-lab/Metabolomics_2024/blob/main/slides/4_statistics_section.pdf).
- [Causal Analysis and conclusion](https://github.com/xia-lab/Metabolomics_2024/blob/main/slides/5_Causal_analysis_summarization.pdf).

<br/>

## 1) LC-MS Spectra Processing and Annotation

The aim of this workflow is to use **LC-MS Spectra Processing module** in [MetaboAnalyst](https://www.metaboanalyst.ca/) to analyze the raw spectra data from a real-world experiments. This section includes raw spectral data format conversion and centroiding. Then we will show a quick demon on how to use MetaboAnalyst for raw LC-MS/MS spectra data processing. The data was obtained using untargeted metabolomics (Q-Exactive Plus Orbitrap MS in positive ion mode) of different blood types (whole blood, serum and plasma). 6 pooled QC samples and DDA MS/MS spectra files are also included. In this section, students will learn how to run the auto-optimized raw spectra processing workflow.

(Optionally) To practice raw spectral data conversion and centroiding, users could download some raw thermo-fisher spectral data (*.raw) from this [link](https://drive.google.com/file/d/17HwDYqISi60bSUEAghQYSzikkuw89n-9/view?usp=sharing).

For this workflow, users could use the 3rd example directly from the module page or optionally download [here](https://www.dropbox.com/scl/fi/2opls296pzffz5hbvjhun/blood_samples.zip?rlkey=tknlc3iik5yhlm2gmkk423c7m). **For the learning purpose, you are strongly encouraged to use the 1st example directly to run the whole process quickly.**

The tutorial of this module is available [here](https://api2.xialab.ca/api/download/metaboanalyst/1_LC_MS_Spectra_Processing.pdf) for further reference. Watch this [video](https://youtu.be/NSwc7Ywvbpw) to see a live demo of raw spectra data processing with MetaboAnalyst.

<br/>

## 2) Functional Analysis and Integration 

The aim of this workflow is to introduce the pathway analysis of untargeted metabolomics data using the **Functional Analysis module**. The theory and processing steps of mummichog is described. Users can use the first examples directly from the module page for practicing. 
The tutorial of this module is available [here]([https://www.xialab.ca/api/download/metaboanalyst/2_Functional_Analysis.pdf]) and [here](https://api2.xialab.ca/api/download/metaboanalyst/5_Functional_Analysis_with_MS2_results.pdf) for further reference. Watch this [video](https://youtu.be/8_CbKcE7iwA) to see a live demo of functional analysis with MetaboAnalyst.

<br/>

## 3) Statistical Analysis of One-factor experimental design and complex metadata

The aim of this workflow is the use the **Statistical Analysis [One Factor] module** in [MetaboAnalyst](https://www.metaboanalyst.ca/) to analyze a concentration table with a simple experimental design. By simple experimental design, we mean a dataset with a single, categorical metadata (ie. Treatment: Control, Drug A, Drug B). This section includes outlier and batch effect detection, missing value imputation, filtering, normalization, transformation, and statistical analysis. Then we will show a quick demo with **Example Data 3** to show how the pipeline works. 


The aim of this workflow is to perform statistical analysis based on complex metadata. Covariate analysis will be used to deal with a metabolomics data, which is highly affected by multiple metadata factors. This study mainly focus on a peak intensity table from a COVID-19 study (**Example Data 1**) for covariate analysis. The data consists of untargeted metabolomics (a peak table) of 2054 metabolites and a metadata table. The data are from 59 individuals (20 healthy, 39 with COVID-19), and there are metadata values for age, sex, diagnosis, and treatment. 

<br/>

## 4) Causal Analysis

The causal relationships between metabolites and phenotypes is of great interest in both metabolomics and exposomics. In this section, we are going to use module **Causal Analysis [Mendelian Randomization]** from MetaboAnalyst 6.0, which provides diverse statistical methods (currently 12), each of which has its own strengths and limitations. In this section, we are going to perform a causal analysis on the associations between one of the significant metabolites identified to be related to the diabetes, L-Cystathionine and type 2 diabetes (GWAS ID: finn-b-E4_DM2). Here is the   [tutorial](https://api2.xialab.ca/api/download/metaboanalyst/4_Causal_Analysis.pdf) for this module.


<br/>

## Additional Reference Documents

To understand more background knowledge on metabolomics data analysis further, you can follow these documents/protocols below. 

#### MetaboAnalyst latest Nature Protocols
[Using MetaboAnalyst Nature Protocol](https://doi.org/10.1038/s41596-022-00710-w)

#### Latest tutorials of MetaboAnalyst
[All tutorial series](https://www.metaboanalyst.ca/MetaboAnalyst/docs/Tutorials.xhtml)


#### Latest tutorials of MetaboAnalystR
[MetaboAnalystR tutorial](https://www.metaboanalyst.ca/MetaboAnalyst/docs/RTutorial.xhtml)


#### Multi-omics integration and protocols
[Web-based multi-omics integration using the Analyst software suite](https://www.nature.com/articles/s41596-023-00950-4)

#### Protocols of Other Modules in MetaboAnalyst
[Using MetaboAnalyst 4.0 for Comprehensive and Integrative Metabolomics Data Analysis](https://currentprotocols.onlinelibrary.wiley.com/doi/10.1002/cpbi.86)

#### Critical Algorithms and concepts
[asari](https://www.nature.com/articles/s41467-023-39889-1);
[MetaboAnalystR 3.0](https://pubmed.ncbi.nlm.nih.gov/32392884/);
[Mummichog](https://pubmed.ncbi.nlm.nih.gov/23861661);
