# scRNA-seq analysis of MSC-Exos–treated and control expanded NK cells

## Overview
This repository contains the single-cell RNA-seq (scRNA-seq) analysis scripts for comparing MSC-Exos–treated expanded NK cells with control expanded NK cells, including quality control (QC), NK-only subsetting, batch correction and Harmony integration, dimensionality reduction and clustering (UMAP/Leiden), differential expression (DE) analysis, and figure generation.

## Files

### `NK25_EXO_raw_250811.h5ad`
AnnData file containing NK single-cell data after initial quality control and removal of non-NK cell populations.

### `NK25_EXO_250811-1.h5ad`
AnnData file containing NK single-cell data after quality control and batch correction, but without cell subtype annotation.

In the `condition` column:
- `EXO`: MSC-Exos–treated expanded NK cells
- `CON`: control expanded NK cells

### `NK25_EXO_250811_annotated.h5ad`
AnnData file containing NK single-cell data after quality control, batch correction, and cell subtype annotation.

### Data availability
The following `.h5ad` files are available via a Quark cloud link:
- `NK25_EXO_raw_250811.h5ad`
- `NK25_EXO_250811-1.h5ad`
- `NK25_EXO_250811_annotated.h5ad`

> https://pan.quark.cn/s/40fc95275b32

### `meta_260225.csv`
Metadata file used for donor ID annotation and grouping.

### `computing environment (package versions).docx`
Software environment and package version information used in the scRNA-seq analysis workflow.

### `20260330_NK_EXO_article.ipynb`
Main notebook for the scRNA-seq analysis workflow, including scripts for generating:
- Figure 3–4
- Supplementary Figure 3–4

### `analysis data_260323.xlsx`
Analysis data for generating:
- Figure 1
- Figure 2
- Figure 5

### `analysis data_Supplementary Figure_260325.xlsx`
Analysis data for generating:
- Supplementary Figure 1–3
- Supplementary Figure 5
