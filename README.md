# PD1-WES
**"A Single Dose of Neoadjuvant PD-1 Blockade Predicts Clinical Outcomes in Resectable Melanoma"**

<br>

Scripts for somatic variant calling and allele-specific copy number profiling in matched tumor/normal whole exome sequencing data.

Required Software:

 * Python 3.6+
 * Snakemake
 * Samtools
 * GATK 4
 * R
 * Sequenza (R Package)
 * Sequenza-utils

## Usage
```
snakemake -s mutect2.snake --configfile config.yaml
snakemake -s sequenza.snake --configfile config.yaml
```

## Author
Brad Wubbenhorst
<bwubb@pennmedicine.upenn.edu>

## Paper Citation

[![DOI](https://zenodo.org/badge/162582612.svg)](https://zenodo.org/badge/latestdoi/162582612)
