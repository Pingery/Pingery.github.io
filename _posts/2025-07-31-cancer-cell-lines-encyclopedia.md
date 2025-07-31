# What is a cancer cell line?
- A cancer cell line is a population of cancer cells that can be grown in a lab.

# Why can it be grown forever?
- Normal scells stop dividing after a few rounds (called senescence).
- Cancer cells often have mutations that allow them to bypass normal limits on growth.
- These cells can grow into petri dishes or flasks, a process known as cell culture. 

# History of first cancer cell line: HeLa cell
- First successfully grew in 1951
- Source: derived from a cervical cancer tumor of Henrietta Lacks, a young African American woman passed away from the disease that year.
- Location: Johns Jopkins Hospital, Baltimore, MD.
- Scientist: Dr. George Gey.
- First human cells grown to divide indefinitely.
- Revolutionized biomedical research.

# Why use cell lines?
- easy to grow and manipulate in the lab
- Represent various human cancers (e.g., breast, lung, colon).
- Serve as models to: study tumor genetics, discover cancer vulnerabilities, test therapeutic compounds

# Cancer cell lines
- used to study Molecular Mechanism of Cancer Cells
- Study signaling pathways in caner (e.g., PI3K/AKT, RAS/MAPK, Wnt).
- Knockwdown or overexpress genes to observe functional changes.
- Investigate the role of oncogenes (e.g., KRAS, MYC) or tumor suppressors (e.g., TP53, RB1)

# Modeling specific cancer subtypes
- Cancers are geterogenous diseases. For example, breast cancers have different subtypes.
- Subtypes are defined based on the presence orr absence of certain receptors and gene expression profiles
- Main breast cancer subtypes based on the presence of receptors
  - Luminal A (ER+, PR+, HER2-): best prognosis
  - Luminal B (ER+, PR+-, HER+-), moderate
  - HER2+ (ER-, PR-, HER2+)
  - Triple negative (ER-, PR-, HER2-); poor pronosis
 
# Development of PAM50 classifier
- 2009 - parket et al., in Journal of Clinical Oncology
  - refined Perou's gene set to 50 genes (PAM50) for clinical use.
  - Classified tumors into the same 5 subtypes using qRT-PCR/NanoString
  - These subtypes can guide the choice of therapy
  - Also introduced Risk of Recurrence (ROR) score.
- Led to the clinical test Prosigna, used in ER+/HER2- breast cancer.
- Prosigna diagnostic assay was developed and commercialiozed by NanoString Technologies, Inc.
- Dr. Charles perou, now a professor at UNC-Chapel is the co-inventor for Prosigna.

# NanoStrongs Tehcnologies Inc
- A bioteceh company, founded in 2003, under the leadership of Dr. Leroy Hood (spun off as an independent company)
- Technology platforms:
- nCounter: a digital gene expression platform that uses color-coded molecular barcodes to directly count RNA, DNA
- Prosigna Assay: a FDA-cleared diagnostic teset for early-stage, hormone receptor-positive breast cancer based on the PAM50 gene signature
- GeoMx Digital Spatial Profiler (DSP): A spatial transcriptomics and protemics platform launched in 2019.
- began in 2003 with early seed funding (~$3.8M).
- In 2012, a crucial Series E of $15.3M helped fund Prosigna development
- IPO in mid-2013 raised $54M, culminating in about $82M total funding before becoming a public company
- 2021-2023: faced lawsuits from 10xGenomics
- 2024: Filed for Chapter 11 bankruptcy, assets sold off
- Bruker Corporation, a global leader in life0science instrumentation, acquired its assets at $392.6M (nCounter, GeoMx, CosMx, AtoMx, Prosigna)
- Bruker aims to integrate NanoString's gene expression and spatial biology platforms into its broader CellScape proteomics systems

# What is CCLE?
- A public resource of cancer cell lines developed by the Broad Institute
- Contains multi-omics data (genomic, transcriptomic, proteomic, pharmacologic).
  - genomic = DNA, transcriptomic = RNA, proteomic = protein 
- Used to study cancer biology and predict drug sensitivity.

# Drug screening using cancer cell lines
- To evaluate the efficacy, potency, and selectivity of drugs against different cancer types.
- First, select cell lines
- Seed cell line into multo-well plates (96-well, 384-well). Allow cells adhere and grow to a certain density under standard conditions.
- A library of canditate drugs (or concentrations of a drug) is applied to cells.
- Cells are incubated with drugs for 24-72 hours (or more)
- Assay Readouts (viability, apoptosis, and proliferation) and data analysis: Generate Dose-Response Curves

# What is a drug does response curve?
- Dose-response graphs typically have the dose on the x-axis and the measured effect (i.e. the measured response) on the y-axis. Plotting the logarithm of the concentration generally results in sigmoidal plots.
- The main parameters that can be identified by dose-response curves are:
  - Potency - the position of the curve along the x-axis
  - Maximal efficacy - the greatest response attainable
  - Slope - change in response per unit dose

# What drug sensitivity data available?
- The Cancer Cell Line Encyclopedia (CCLE), through teh DepMap portal, provides drug sensitivity data from several large-scale screening projects.
- PRISM Repurposing Dataset (Broad Institute)
  - Pooled barcoded screening of ~500 cell lines
  - >4,500 compounds (many FDA-approved or invesetigational)
  - Relative viability (log fold change) at multiple concentrations

# Breast cancer drugs on the market
- Chemotherapy: doxorubicin; paclitaxel
- Hormone therapy: tamoxifen, Anastrozole (Arimidex), exemestane (Aromasin)
- Targeted therapy: trastuzumab, pertuzumab, and palbociclib

# Information About my Jupyter Notebook
We were able to filter out specific cancers in the CCLE dataset. I filtered out breast and skin cancer, and I was able to find the different subtypes in breast cancer as well. However, I could not filter the different subtypes for skin cancer because the data had not been updated yet. But, I was able to find the Oncotree Subtype for skin cancer because that information is in the data table. 

[My Jupyter Notebook](https://github.com/Pingery/Pingery.github.io/blob/main/_posts/CCLE.html)
