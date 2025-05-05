# Asthmatic Gene Expression Data Preprocessing

This project involves the preprocessing of a gene expression dataset related to asthmatic and non-asthmatic individuals. The work includes exploratory data analysis, data filtration, normalization, and summarization to prepare the dataset for further bioinformatics analysis.

## 🧬 Project Overview

Asthma is a chronic respiratory condition that causes inflammation and narrowing of the airways. It affects millions worldwide and is influenced by genetic and environmental factors. This project preprocesses microarray gene expression data to enable accurate downstream analysis.

## 📊 Dataset Details

- **Platform:** GPL570 (Affymetrix Human Genome U133)
- **Accession Number:** GSE35571
- **Organism:** *Homo sapiens*
- **Disease:** Asthma
- **Sample Size:** 131 samples (60 asthmatic, 64 non-asthmatic after filtration)
- **Number of Probes:** 54,662
- **Data Type:** Microarray
- **Dataset Link:** [GSE35571 on NCBI](https://www.ncbi.nlm.nih.gov/sites/GDSbrowser?acc=GDS5000#details)

## 🧪 Steps Performed

### 1. Exploratory Data Analysis (EDA)
- Class distribution visualization
- ![Pie chart for Class distribution before filtration](plots/boxplot_after_normalization.png)
- Boxplot and density plots to examine gene expression levels before preprocessing

### 2. Data Preprocessing
- **Filtration:** Removed samples with missing values
- **Quantile Normalization:** Standardized probe intensity distributions across samples
- **Summarization:** Converted probe-level data to gene-level by averaging probe values with the same gene name

### 3. Post-Processing Visualization
- Updated boxplots and density plots after normalization and summarization to confirm data quality improvements

## 📈 Results

- Improved consistency and comparability across samples
- Reduced technical noise and redundancy
- Prepared a clean gene-level dataset suitable for further statistical or machine learning analysis

## 👩‍💻 Contributors

- Aliaa Alaa Eldin  
- Kholoud Abdelmohsen  
- Roaa Ashraf  
- Salma Sameh  
- Shada Gamal

**Supervisor:** Dr. Rana Hossam Elden  
**Engineer:** Eng. Heidi Ahmed

---

## 📂 Repository Structure (Suggestion)

