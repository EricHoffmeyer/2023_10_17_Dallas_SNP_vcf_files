# 2023_10_17_Dallas_SNP_vcf_files

This repository contains the analysis of vcf files received for Dallas' Down Syndrome samples.

Folders contain the following:

## 2023_10_17_results
Results from 2023_10_17_vcf_exploration.Rmd where a single sample was run through an annotation pipeline

## 2024_02_14_resuts
Results from 2024_02_14_Common_DS_Mutations where the changes were mapped to gene exons and then common mutations shared in all/most samples were identified.
UPDATE: This did not have quite the functionality that I wanted. Namely to identify the mutations (SNP, insertion, deletion, etc) and a way to compare across multiple samples.

## 2024_03_04_VCF_class
Results from 2024_03_04_VCF_class.qmd where I use a new workflow to read and process the VCF files.

## 2024_03_14_results
Results from 2024_03_14_VCF_to_MAF.qmd where the VCF files were wrangled, converted to annovar format using perl in a separate conda environment, then reloaded in annovar format and converted to MAF format for use with maftools.

--- Note: not seeing variants that I saw when looking at the viles on IGV. Need to troubleshoot this.

## 2024_04_15_results

I did some troubleshooting and fixed the issue where the MAF results were not matching up with IGV displays of the raw vcf and bam files. New avinput files and plots are located here.

## 2024_04_16_results

Went through the MAFtools vignette with the dataset, looking for interesting functions, plots, and other outputs. Results from that notebook are saved here.
