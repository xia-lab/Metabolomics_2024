# Metabolomics 2024: a unified platform for metabolomics data processing, analysis and interpretation tool - MetaboAnalyst 6.0

![alt text](https://raw.githubusercontent.com/xia-lab/Metabolomics_2024/main/Figure1.png)

For this workshop, we will be covering four main topics: 
* Auto-Optimized LC-MS/MS spectra processing and compound identification;
* Functional analysis from LC-MS peaks;
* Statistical Analysis of One-factor experimental design and complex metadata;
* Causal Analysis. 

Details for each workflow are below. 

#### <ins>Before you start, please download our Protocols for MetaboAnalyst 5.0 [here](https://www.nature.com/articles/s41596-022-00710-w) as a reference.</ins>

<br/>

# Slides Summary

- [Introduction and Key Concepts](https://github.com/xia-lab/Metabolomics_2023/blob/main/intro.pdf).
- [Metabolomics Raw Spectra Data and Processing](https://github.com/xia-lab/Metabolomics_2023/blob/main/section_1_LCMS_processing.pdf).
- [Metabolomics Statistical Analysis of One-factor experimental design](https://github.com/xia-lab/Metabolomics_2023/blob/main/section_2_basic_stats.pdf).

- [Functional analysis from LC-MS peaks](https://github.com/xia-lab/Metabolomics_2023/blob/main/section_3_functional_analysis.pdf).
- [Statistical Analysis with Complex Meta-Data](https://github.com/xia-lab/Metabolomics_2023/blob/main/section_4_complex_stats.pdf).

<br/>

## 1) LC-MS Spectra Processing and Annotation

The aim of this workflow is to use **LC-MS Spectra Processing module** in [MetaboAnalyst](https://www.metaboanalyst.ca/) to analyze the raw spectra data from a real-world experiments. This section includes raw spectral data format conversion and centroiding. Then we will show a quick demon on how to use MetaboAnalyst for raw data processing in the auto-optimized mode. The data was obtained using untargeted metabolomics (Q-Exactive Plus Orbitrap MS in positive ion mode) of blood samples from 6 malaria semi-immune patients and 6 naive controls. 6 pooled QC samples are also included. In this section, students will learn how to run the auto-optimized raw spectra processing workflow.

(Optionally) To practice raw spectral data conversion and centroiding, users could download some raw thermo-fisher spectral data (*.raw) from this [link](https://drive.google.com/file/d/17HwDYqISi60bSUEAghQYSzikkuw89n-9/view?usp=sharing).

For this workflow, users could use the 2nd example directly from the module page or optionally download [here](https://www.dropbox.com/s/ift0zrkh0rx3v80/malaria_raw.zip?dl=0). **For the learning purpose, you are strongly encouraged to use the 1st example directly to run the whole process quickly.**

The tutorial of this module is available [here](https://www.xialab.ca/api/download/metaboanalyst/1_Raw_Spectral_Processing.pdf) for further reference. Watch this [video](https://youtu.be/NSwc7Ywvbpw) to see a live demo of raw spectra data processing with MetaboAnalyst.

<br/>

## 2) Statistical Analysis of One-factor experimental design

The aim of this workflow is the use the **Statistical Analysis [One Factor] module** in [MetaboAnalyst](https://www.metaboanalyst.ca/) to analyze a concentration table with a simple experimental design. By simple experimental design, we mean a dataset with a single, categorical metadata (ie. Treatment: Control, Drug A, Drug B). This section includes outlier and batch effect detection, missing value imputation, filtering, normalization, transformation, and statistical analysis. Then we will show a quick demo with **Example Data 3** to show how the pipeline works. 



<br/>

## 3) Functional Analysis and Integration 

The aim of this workflow is to introduce the pathway analysis of untargeted metabolomics data using the **Functional Analysis module**. The theory and processing steps of mummichog is described. Users can use the first examples directly from the module page for practicing. 
The tutorial of this module is available [here]([https://www.xialab.ca/api/download/metaboanalyst/2_Functional_Analysis.pdf]) for further reference. Watch this [video](https://youtu.be/NSwc7Ywvbpw) to see a live demo of functional analysis with MetaboAnalyst.

<br/>

## 4) Metabolomics Statistical Analysis with Complex Metadata

The aim of this workflow is to perform statistical analysis based on complex metadata. Covariate analysis will be used to deal with a metabolomics data, which is highly affected by multiple metadata factors. This study mainly focus on a peak intensity table from a COVID-19 study (**Example Data 1**) for covariate analysis. The data consists of untargeted metabolomics (a peak table) of 2054 metabolites and a metadata table. The data are from 59 individuals (20 healthy, 39 with COVID-19), and there are metadata values for age, sex, diagnosis, and treatment. 

<br/>

## Additional Reference Documents

To understand more background knowledge on metabolomics data analysis further, you can follow these documents/protocols below. 

#### MetaboAnalyst & other omics tools
[Using MetaboAnalyst for Metabolomics Data Analysis](https://www.dropbox.com/s/7uxzeacpgx6zjux/Metabolomics_MetaboAnalyst_Intro_2022.pptx?dl=0)

#### Key statistical concepts & approaches
[General Concepts & Workflow in Omics Data Analysis](https://www.dropbox.com/s/stsp01glned47gg/Metabolomics_Stats_Intro_2022.pptx?dl=0)

#### Protocols of Other Modules in MetaboAnalyst
[Using MetaboAnalyst 4.0 for Comprehensive and Integrative Metabolomics Data Analysis](https://currentprotocols.onlinelibrary.wiley.com/doi/10.1002/cpbi.86)
