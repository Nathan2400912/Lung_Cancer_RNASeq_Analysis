# Replicating Figures from "Fascin Actin-Bundling Protein 1 (FSCN1) and its Role in NSCLC Progression"

This repository contains a project for the **final assignment of the Python Bioinformatics course (BF550)** at Boston University. The goal of this project is to replicate key figures from a scientific publication using Python for data analysis and visualization.

## Background 
The scientific paper guiding this project is titled:
"Fascin actin-bundling protein 1 (FSCN1) regulates non-small cell lung cancer progression by influencing the transcription and splicing of tumorigenesis-related genes."

Non-small cell lung cancer (NSCLC) is the most common subtype of lung cancer and remains a major cause of cancer-related mortality worldwide. While significant progress has been made in developing therapeutic strategies, many patients with NSCLC face challenges in achieving complete recovery. This underscores the need for innovative approaches to understanding and treating this disease. This study investigates a relatively unexplored avenue of lung cancer biology, focusing on the role of ribosome-binding proteins, particularly FSCN1, in the progression of NSCLC. FSCN1 is an actin-bundling protein that has been implicated in tumor cell migration and invasion. Interestingly, this paper delves deeper into its potential regulatory effects on gene transcription and splicing, shedding light on how it may influence tumorigenesis at a molecular level. The intersection of transcriptional regulation, post-transcriptional splicing mechanisms, and the involvement of proteins like FSCN1 offers new perspectives on therapeutic targets for NSCLC. Inspired by this, this project seeks to replicate and analyze critical figures from the study using computational approaches.

## Analysis Overview 
The analysis replicates two key figures from the publication:

1. **Principal Component Analysis (PCA) plot** comparing FASCN1 knockdown samples to control samples.
2. **Volcano plot** highlighting differentially expressed genes (upregulated and downregulated) after performing differential expression analysis using DESeq2.

### Data and Tools
- **Data Analysis and Visualization:** All analysis and figure plotting were performed using Python, leveraging libraries such as Pandas, Matplotlib, Seaborn, and Plotly.
- **Notebook:** The entire codebase is contained in the Jupyter Notebook **BF550_Project2_Nathan_Wong.ipynb**.
- **Data Source:** The raw and processed data used in this analysis are available in the **Data** directory and were retrieved from the GEO database under accession ID **GSE234859**.

## Results
Reproduced figures are included in:

- **Report**: Comprehensive methods, results, and interpretations are compiled in **BF550_Project2_Report.pdf**.
- **Figures** Directory: All generated plots are stored here in publication-quality formats.
