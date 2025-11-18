# **Trends in Frequently Studied Genes & Proteins in Alzheimer’s and Parkinson’s Disease Across Europe**

## **Project Overview**

This project aims to identify the **most frequently studied genes and proteins** associated with **Alzheimer’s Disease (AD)** and **Parkinson’s Disease (PD)** in **European populations**, based on previously published research, publicly available transcriptomic datasets, and clinical reports.

The goal is to determine **which biomolecules appear repeatedly across multiple studies** and are therefore considered **core candidates** for deeper investigation, therapeutic development, and precision medicine.

Rather than linking both diseases together, this project focuses on the **source** of scientific attention:

> *Which genes or proteins have been consistently reported, explored, or implicated in AD or PD research across Europe?*

This helps narrow down:

* Key biomarkers for targeted research
* Regional differences in gene/protein focus
* Foundational targets for drug or therapy development
* Areas where scientific consensus is emerging

---

## **Research Aims**

1. **Identify the most frequently reported genes and proteins** in AD and PD studies conducted on European populations.
2. **Analyze publication trends**, dataset distributions, and biomarker frequencies using Python and Power BI.
3. Determine if **regional patterns** exist (e.g., certain genes studied more in Western vs Eastern Europe).
4. Provide a **foundation for precision medicine**, where future therapies can be tailored to regions with known biomarker patterns.
5. Build a **reproducible pipeline** using open-source tools and public datasets.

---

## **Why This Research Matters**

Neurodegenerative disease research is highly fragmented: different groups often report different genes, making it difficult to prioritize drug targets.
By identifying **common, repeatedly studied biomarkers**, this project provides:

* A **baseline** for ongoing AD/PD research
* A **roadmap** for future molecular studies
* Insight into where scientific consensus is emerging
* A foundation for **precision therapies** for Europe

---

## 🔎 **NCBI Search Queries (For Dataset Collection)**

queries search on **NCBI GEO**, **PubMed**, or **SRA**:

### **Alzheimer’s Disease (European Samples)**

```
("Alzheimer" OR "Alzheimer's disease") AND ("Europe" OR "European") AND ("gene expression" OR "transcriptome" OR "RNA-seq")
```

### **Parkinson’s Disease (European Samples)**

```
("Parkinson" OR "Parkinson's disease") AND ("Europe" OR "European") AND ("gene expression" OR "transcriptome" OR "RNA-seq")
```

### **Gene/Protein Frequency Tracking**

```
("Alzheimer" OR "Parkinson") AND "Homo sapiens" AND "expression profiling" AND ("brain" OR "blood")

---

## **Tools & Technologies**

**Python**

* GEOparse
* pandas, numpy
* spaCy/NLTK for text mining
* matplotlib/seaborn for plotting

**Power BI**

* Regional distribution visualization
* Frequency dashboards
* Trend analysis charts

**GitHub**

* Version control
* Documentation
* Project sharing

---

## **Project Structure**

```
├── data/
│   ├── raw/
│   ├── processed/
│
├── notebooks/
│   ├── 01_download_datasets.ipynb
│   ├── 02_gene_frequency_analysis.ipynb
│   └── 03_visualizations.ipynb
│
├── scripts/
│   ├── extract_gene_mentions.py
│   ├── geo_downloader.py
│   └── trend_summary.py
│
├── powerbi/
│   └── AD_PD_Trend_Dashboard.pbix
│
└── README.md
``
Just tell me what you want next.
