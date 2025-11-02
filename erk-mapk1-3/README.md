# 🧠 ERK1/2 Transcription Factor Binding Site Prediction

This project investigates the **MAPK1 (ERK2)** and **MAPK3 (ERK1)** signaling pathways and their potential downstream transcription factor (TF) targets in oligodendrocytes.  
Using **motif discovery** and **TF binding prediction** tools, this analysis aims to identify possible regulatory mechanisms linking ERK activation to myelination-related gene expression.

---

## 📘 Overview

- **Goal:** Identify transcription factor binding motifs in promoter regions of ERK1/2 target genes.  
- **Approach:**  
  1. Retrieve promoter sequences from UCSC Genome Browser.  
  2. Perform motif discovery using **MEME Suite**.  
  3. Compare discovered motifs with known TFs via **TOMTOM** and **JASPAR**.  
  4. Analyze potential regulatory networks in oligodendrocyte development.

---

## 📂 Files

| File | Description |
|------|--------------|
| `erk_promoters.fasta` | Promoter sequences for ERK1 and ERK2 target genes |
| `meme_results/` | Motif discovery outputs from MEME Suite |
| `tomtom_results/` | Transcription factor prediction and motif comparison results |
| `erk_motif_summary.pdf` | Summary of top motifs and TF matches |
| `erk_analysis_report.html` | Interactive analysis report |

---

## 🧬 Tools and Packages

- **MEME Suite 5.5.6** (`meme`, `tomtom`, `fimo`) (later proved to be less useful compared with iGPS)
- **pyjaspar**
- **Biopython**
- **R / ggplot2** (for visual summaries)

---

## 🧩 Key Results

- Identified conserved motifs related to **ETS** and **ELK** family transcription factors.  
- Cross-species conservation of ERK-associated motifs in **mouse** and **zebrafish** promoters.  
- Network analysis suggests a potential regulatory cascade from ERK activation to myelin gene transcription.

---

## 🔬 Biological Context

ERK1/2 signaling is known to influence **oligodendrocyte differentiation and myelination**.  
By computationally mapping promoter motifs and TF binding sites, this study contributes to understanding how phosphorylation-driven pathways regulate glial gene expression.

---

📅 **Last updated:** November 2025  
🧑‍🔬 **Author:** Y. Wei
