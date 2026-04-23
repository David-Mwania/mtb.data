# TB Mini Pipeline

![Bioinformatics Icon](https://cdn-icons-png.flaticon.com/512/3099/3099188.png)

A simplified pipeline for tuberculosis (TB) genomics analysis using Oxford Nanopore sequencing data.  
This project is designed as a learning resource to practice bioinformatics workflows and Git/GitHub version control.

---

## Features
- Organizes TB sequencing data and metadata
- Example scripts for preprocessing and analysis
- Demonstrates Git-based version control
- Includes sample files (`STARmanual.pdf`, `all_samples.replicates.tsv`, `biodata`)

---

## Requirements
- Linux/Unix environment
- Git installed
- Python 3.10+ with bioinformatics tools (e.g., NanoFilt, minimap2, TBProfiler, Clair3)

---

## Usage
Clone the repository and enter the pipeline folder:

```bash
git clone https://github.com/David-Mwania/mtb.data.git
cd mtb.data/tb-mini-pipeline

tb-mini-pipeline/
 ├── scripts/              # Example preprocessing & analysis scripts
 ├── data/                 # TB sequencing data & metadata
 ├── docs/                 # Manuals and references (e.g., STARmanual.pdf)
 ├── results/              # Output files from pipeline runs
 └── README.md             # Project overview

# TB Mini Pipeline  
*Written by Blessed Dave*

