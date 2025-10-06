# SLE777Assessment_4
Assessment 4
# Genomic Analysis of Acetobacter aceti and Escherichia coli
# Overview
This repository contains R scripts for a comprehensive genomic analysis comparing Acetobacter aceti and Escherichia coli, examining sequence features, codon usage, k-mer patterns, gene expression, and growth data analysis.

# Repository Structure
# Part 1: Data Analysis and Visualization
Data Import & Processing: Downloading and importing gene expression and growth data files

Statistical Analysis: Mean calculations, t-tests, and statistical summaries

Data Visualization: Histograms, box plots, and comparative visualizations

# Part 2: Comparative Genomic Analysis
Sequence Length Analysis: CDS length calculations and distribution analysis

Base Composition: DNA and amino acid frequency analysis

Codon Usage: RSCU calculations and bias quantification

K-mer Analysis: 3-5 mer identification and comparative analysis

# Key Features
Part 1 Analysis
RNA-seq count data processing and mean expression calculations

Tree growth measurements statistical analysis

Differential expression identification

Data visualization with histograms and boxplots

# Part 2 Analysis
Coding sequence architecture comparison

GC-content and amino acid usage patterns

Codon usage bias quantification

Species-specific k-mer preference identification

Ecological adaptation analysis

# Data Sources
Escherichia coli coding sequences from Ensembl Bacteria

Acetobacter aceti coding sequences from Ensembl Bacteria

Gene expression data: gene_expression.tsv

Growth measurement data: growth_data.csv

# Prerequisites
R Packages Required
Core: seqinr (for sequence analysis)

Data Processing: R.utils, R.oo, R.methodsS3

Visualization: Base R graphics (hist(), boxplot(), barplot())

# System Requirements
R version >= 4.1.2

Ubuntu 22.04.5 LTS (compatible with other systems)

# Key Findings
Genomic Comparisons
CDS Count: E. coli (4,239) vs A. aceti (3,402)

Total Coding DNA: E. coli (3,978,528 bp) vs A. aceti (3,236,568 bp)

Sequence Length: Similar distributions with A. aceti showing more long-gene outliers

Base Composition: Both organisms GC-rich with conserved patterns

# Molecular Features
Codon Usage: Moderate bias in both (E. coli: 0.555, A. aceti: 0.529)

Amino Acid Usage: Highly conserved patterns across both proteomes

K-mer Preferences: Species-specific motifs reflecting ecological adaptations

# Usage
Run scripts in numerical order for complete analysis reproduction. Each script contains detailed comments explaining functionality and expected outputs.

# Authors
Rajkomal Kaur 

# Session Info
Analysis performed with R 4.1.2 on Ubuntu 22.04.5 LTS platform using seqinr, R.utils, and base R graphics for visualization.
