# 🧬 ChIP-seq Analysis Project

This repository contains a complete ChIP-seq data analysis workflow, including quality control, alignment, peak calling, annotation, and downstream functional analysis.

---

## 📁 chipseq_project
chipseq_project/
│
├── raw/ # Raw sequencing data (FASTQ) - NOT uploaded to GitHub
├── qc/ # Quality control reports (FastQC / MultiQC)
├── alignments/ # Aligned reads (BAM/SAM) - excluded from GitHub
├── Peak calling/ # MACS2 peak calling results
├── annotation/ # Peak annotation results
├── Functional Analysis/ # GO enrichment analysis
├── KEGG Enrichment/ # KEGG pathway analysis
├── MOTIF ANALYSIS/ # Motif discovery results
├── TSS Enrichment/ # TSS enrichment plots
├── target gene identification/ # Target gene mapping
├── visualization/ # Genome browser tracks & plots
├── reference/ # Reference genome & annotation files
├── macs2_env/ # Conda environment (excluded from GitHub)
│
├── .gitignore
└── README.md


## 🔬 Workflow Summary

### 1. Quality Control
- FASTQ quality checked using FastQC and MultiQC

### 2. Read Alignment
- Reads aligned to reference genome using Bowtie2 / BWA

### 3. Peak Calling
- MACS3 used to identify enriched binding regions

### 4. Annotation
- Peaks mapped to nearest genes

### 5. Functional Analysis
- GO and KEGG enrichment analysis performed

### 6. Motif Analysis
- Identification of transcription factor binding motifs

### 7. Visualization
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

