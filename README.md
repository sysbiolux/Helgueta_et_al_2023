 date: '2022-12-27'

Code used for the analysis of the RNA-seq datasets produced in this study. Original fastq files deposited in European Nucleotide Archive (ENA) at EMBL-EBI under accession number [PRJEB59115](https://www.ebi.ac.uk/ena/browser/view/PRJEB59115).

# Getting started

Different folders are included in this repository:

* `RNA-seq_Park7_KnockOut_mice`: Contains the analysis of 6 datasets including Park7 Knockout and wildtype mice: 
  FemaleS 3 months of age, Males 3 months of age, FemaleS 8 months of age, MaleS 8 months of age first cohort, MaleS 8 months of age second cohort, MaleS 8 months of age first and second cohort together

* `RNA-seq_Sex-differences_8months_mice`: Contains the analysis of 1 dataset including male and female wildtype mice at 8 months of age

* `RNA-seq_mouse_primary_astrocytes`: Contains the analysis of 1 dataset of astrocytes treated with different siRNAs and their respective scramble: siPark7, siNfe2l2 and siCyp1b1 treated astrocytes

# Specific questions:

- Gene dispersions by sex and cell type: `RNA-seq_Sex-differences_8months_mice/Brain_sex_dispersion.qmd`
- Cell purities and inflammation state: `assess_cell_purity.qmd`, using TPM on markers

