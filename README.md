# AnnData Tutorial - Single Cell Data Structure

## Overview
This project demonstrates the creation, manipulation, and visualization of AnnData objects for single-cell RNA-seq data analysis. AnnData is the core data structure used by the scverse ecosystem.

## What is AnnData?
AnnData (Annotated Data) is a Python package for handling annotated data matrices. It stores:
- **X**: Main data matrix (cells × genes)
- **obs**: Cell/observation metadata
- **var**: Gene/variable metadata
- **uns**: Unstructured metadata
- **obsm**: Multi-dimensional cell annotations (PCA, UMAP)
- **layers**: Multiple data matrices
- **obsp**: Pairwise cell annotations

## Tutorial Contents
1. Creating AnnData from scratch
2. Adding layers and metadata
3. Subsetting and slicing
4. Reading and writing H5AD files
5. Real data visualization (PBMC dataset)
6. Cell type annotation

## Key Results
| Operation | Result |
|-----------|--------|
| Synthetic dataset | 100 cells × 2000 genes |
| T cells identified | 21 cells |
| B cells identified | 27 cells |
| HVGs selected | 976 genes |
| Real PBMC dataset | 700 cells × 765 genes |
| T cells in PBMC | 130 cells |

## Tools Used
| Tool | Version | Purpose |
|------|---------|---------|
| AnnData | 0.12.10 | Data structure |
| Scanpy | 1.12.1 | Visualization |
| NumPy | - | Array operations |
| Pandas | - | Metadata handling |

## Repository Structure
├── README.md
├── notebook/
│   └── AnnData_Tutorial.ipynb
└── data/
├── anndata_tutorial.h5ad
├── cell_metadata.csv
└── gene_metadata.csv

## References
- [AnnData Documentation](https://anndata.readthedocs.io/en/latest/)
- [scverse AnnData Tutorial](https://scverse-tutorials.readthedocs.io/en/latest/notebooks/anndata_getting-started.html)
