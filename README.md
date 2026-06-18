## 🧬 ChIP-seq Analysis of NR2F2 in HepG2 Cells

---

## 📌 Project Overview

This project focuses on the genome-wide identification of binding sites of the transcription factor **NR2F2** in the human liver cancer cell line **HepG2** using ChIP-seq data. The study follows a standard bioinformatics pipeline from raw sequencing data to biological interpretation.

---

## 🧾 Dataset Information

* **Assay Type:** TF ChIP-seq
* **Target:** NR2F2
* **Organism:** *Homo sapiens*
* **Cell Line:** HepG2
* **Platform:** Illumina HiSeq 2000
* **Nucleic Acid:** DNA
* **Replication Type:** Isogenic
* **Control Dataset:** ENCSR000BPH
* **Description:** NR2F2 ChIP-seq protocol v042211.1 in HepG2 cells

---

## 🔬 Workflow Summary

* Quality control of raw sequencing reads
* Alignment of reads to the human reference genome
* Identification of NR2F2 binding peaks
* Annotation of peaks to nearby genes and genomic regions
* Functional enrichment analysis (GO and KEGG)
* Motif discovery and transcription factor analysis
* Visualization using genome browsers and plots

---

## 📊 Overall Results Summary

* Raw sequencing data passed quality control with good read quality
* High percentage of reads successfully aligned to the reference genome
* Significant NR2F2 binding peaks were identified across the genome
* Most peaks were enriched in regulatory regions such as promoters and introns
* Functional analysis showed enrichment in gene regulation and signaling pathways
* Motif analysis confirmed NR2F2 binding preferences and potential co-factors
* Visualizations supported clear genome-wide binding patterns

---

## 🛠 Tools Used

* FastQC, MultiQC (Quality Control)
* Bowtie2 / BWA, SAMtools (Alignment)
* MACS3 (Peak Calling)
* BEDTools, HOMER (Annotation)
* R / Python (Functional Analysis)
* HOMER, MEME Suite (Motif Analysis)
* IGV, R, Python (Visualization)

---

## 🚫 Files Excluded

* Raw FASTQ files
* BAM/SAM alignment files
* Large environment folders (e.g., conda/mac tools environments)

---

## 👩‍🔬 Author

**Anusree Pattamsetty**
Bioinformatics Student

---

