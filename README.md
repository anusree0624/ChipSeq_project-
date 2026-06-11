# 🧬 ChIP-seq Analysis Project

This repository contains a complete ChIP-seq data analysis workflow, including quality control, alignment, peak calling, annotation, and downstream functional analysis.

---

## 🔬 Workflow Summary

1. Quality Control
- FASTQ quality checked using FastQC and MultiQC
2. Read Alignment
- Reads aligned to reference genome using Bowtie2 / BWA
3. Peak Calling
- MACS3 used to identify enriched binding regions
4. Annotation
- Peaks mapped to nearest genes
5. Functional Analysis
- GO and KEGG enrichment analysis performed
6. Motif Analysis
- Identification of transcription factor binding motifs
7. Visualization
- Genome browser tracks and plots generated

---

## 🛠 Tools Used

- FastQC
- MultiQC
- Bowtie2 / BWA
- SAMtools
- MACS3
- BEDTools
- HOMER / MEME Suite
- R / Python

---

## 🚫 Files NOT included in GitHub

Large files excluded via `.gitignore`:

- raw FASTQ files
- BAM/SAM alignment files
- Conda environment (`macs2_env/`)

---

## 👩‍🔬 Author

ANUSREE PATTAMSETTY || Bioinformatics student 

