# snakemake-scrnaseq

## About the dataset

In this mini-project, a single-cell RNA-Seq dataset will be processed and analyzed in a simple snakemake pipeline. 

This dataset comes from the "1k PBMCs from a Healthy Donor using v3 chemistry" dataset by 10x and processed by Cell Ranger 3.0.0. The stats of this dataset are:

* 1,222 cells detected 
* Sequenced on Illumina NovaSeq with approximately 54,000 reads per cell
* 28bp read1 (16bp Chromium barcode and 12bp UMI), 91bp read2 (transcript), and 8bp I7 sample barcode
* run with --expect-cells=1000

## Single-cell RNA-Seq snakemake pipeline

This is how I processed the data...
