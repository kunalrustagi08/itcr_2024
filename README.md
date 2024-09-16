# Acute Myeloid Leukemia Heatmap

## Overview
This analysis uses a dataset of acute myeloid leukemia (AML) samples to generate an annotated heatmap. The goal is to visualize the clustering of samples and genes based on gene expression data.

## Requirements
- R (version 4.0 or higher)
- The following R packages:
  - `pheatmap`
  - `magrittr`
  - `readr`
  - `dplyr`
  - `tibble`
  - `sessioninfo`

## Dependencies
The analysis relies on the AML dataset from the [refine.bio](https://www.refine.bio/) platform, which has been pre-processed and quantile normalized.

## Usage
1. Clone the repository or download the R Markdown file.
2. Open the R Markdown file in an R environment (e.g., RStudio).
3. Run the code chunks in the file to generate the heatmap.

## Outputs
The analysis will generate the following outputs:
- A heatmap plot saved as a PNG file in the `plots` directory.
- A TSV file containing the top 90 most variable genes, saved in the `results` directory.

## Directory Structure
- `data`: Contains the downloaded AML dataset files.
- `plots`: Directory where the heatmap plot is saved.
- `results`: Directory where the TSV file with the top 90 most variable genes is saved.

## Session Info
The session information is printed at the end of the analysis, providing details on the R version and packages used.