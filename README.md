# SingleCell-RNA-seq-Learning
This repo documents my practice in single-cell RNA-seq analysis, using 10X Genomics data to perform quality control, normalisation, dimensionality reduction (PCA/UMAP), and automated cell type assignment with cellassign. It is based on tutorials but adapted for clarity and deeper learning.

# scRNA-seq Data Analysis with cellassign

This repository documents my hands-on practice in single-cell RNA-seq analysis, using 10X Genomics data for:  
- Quality control with scater and scran  
- Normalisation & filtering
- Dimensionality reduction (PCA, UMAP)  
- Cell type assignment using cellassign 

This project follows structured methods from existing tutorials but includes personal modifications for clarity and a better learning experience.  

---

## Data Used  
- Dataset: Processed 10X Genomics single-cell RNA-seq data  
- Format: matrix.mtx, genes.tsv, barcodes.tsv
- Processing: Loaded as a SingleCellExperiment object  

---

## Key Steps in Analysis  
✔ Read & preprocess scRNA-seq data
✔ Perform quality control (mitochondrial & ribosomal genes filtering)
✔ Compute size factors and normalise expression
✔ Run PCA & UMAP for visualisation
✔ Assign cell types using cellassign

---

## References & Acknowledgments  
This project is inspired by the **Single-Cell RNA-seq Analysis Tutorial** by [Kieran R. Campbell](http://kieranrcampbell.github.io/r-workshop-march-2019), with modifications to improve understanding and workflow efficiency.  

Additional resources:  
- [`SingleCellExperiment` Bioconductor](https://bioconductor.org/packages/release/bioc/html/SingleCellExperiment.html)  
- [`scater` Documentation](https://bioconductor.org/packages/release/bioc/html/scater.html)  
- [`cellassign` GitHub Repository](https://github.com/Irrationone/cellassign)  

---

## Why I Created This  
I wanted to deepen my understanding of single-cell RNA-seq analysis by following structured methods, while making adjustments to enhance learning and workflow clarity.  

---
## Created by: Niyati Saini
