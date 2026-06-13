# RuBisCo Large Subunit Evolution in Deep-Sea Uncultured Archaea

## Overview

This project investigates the evolutionary diversity of RuBisCo large subunit (rbcL) sequences recovered from deep-sea and uncultured archaeal lineages using metagenomic sequence mining and comparative phylogenetic analysis.

The objective is to characterize sequence divergence patterns and infer evolutionary relationships across extreme environmental niches, with emphasis on archaeal carbon fixation systems in poorly characterized habitats.

---

## Biological Motivation

RuBisCo (ribulose-1,5-bisphosphate carboxylase/oxygenase) is the key enzyme responsible for carbon fixation in the Calvin–Benson–Bassham cycle. While extensively characterized in plants, algae, and cyanobacteria, its evolutionary diversity in archaeal and deep-sea systems remains incompletely resolved.

This project focuses on:

- Expanding known RuBisCo sequence space in extreme marine environments  
- Identifying evolutionary divergence in archaeal RuBisCo homologs  
- Linking environmental origin to phylogenetic clustering patterns  

---

## Data Sources

- NCBI protein database (RuBisCo large subunit homolog retrieval)

---

## Methods

### 1. Sequence Retrieval
- Querying NCBI protein database for RuBisCo large subunit homologs
- Filtering sequences based on length, completeness, and annotation quality

### 2. Multiple Sequence Alignment
- Alignment performed using Clustal Omega
- Manual inspection of conserved catalytic motifs and active-site residues

### 3. Phylogenetic Reconstruction
- Maximum likelihood phylogeny inferred using FastTree
- Bootstrap analysis used to evaluate branch stability

### 4. Evolutionary Interpretation
- Identification of archaeal-specific clades
- Comparison with bacterial and eukaryotic RuBisCo lineages
- Environmental stratification analysis across sequence clusters

---

## Key Results

- Deep-sea archaeal RuBisCo sequences form distinct phylogenetic clusters  
- Strong sequence divergence observed relative to surface-associated homologs  
- Environmental origin correlates with phylogenetic distance and clade structure  
- Evidence for archaeal-specific evolutionary trajectories of carbon fixation enzymes  

---

## Repository Structure

```text
data/        Raw FASTA sequences
results/     Alignments and phylogenetic trees
figures/     Tree visualizations and annotated outputs
scripts/     Sequence processing and analysis pipeline
