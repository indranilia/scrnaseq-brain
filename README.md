# scrnaseq-brain
This is a repository for applying a single-cell RNA-sequencing pipeline to mice brain cell dataset.

##Instructions
You can download the dataset [here](https://github.com/chanzuckerberg/scRNA-python-workshop/blob/master/content/data.zip) and my notebook from this repository to replicate all necessary analyses. The notebook will run on Google Colab as long as you upload the datasets onto the Drive. 

## Description
Yousry, one of my classmates, developed a single-cell RNA-sequencing (sc-RNA-seq) pipeline for his portfolio project. I found this topic deeply fascinating, so this project is my extension of Yoursry's project for brain cells (Elsadec, 2024). You can read more about his project [here](https://medium.com/@mohamed.y.elsadec_56085/a-comparative-analysis-of-clustering-scrna-seq-data-using-pca-based-and-gnn-driven-approaches-24c9fb8d5ec8).

sc-RNA-seq has many promising applications for brain cells. Through this methodology, we might be able to form a more sophisticated understanding of genetic expressions in brain cells. Such an understanding can advance the studies of neurological and neurodegenerative disease by revealing pathogenic and/or regenerative cells and pathways for drug discovery (Ofengeim et al., 2017).

## Dataset
In this exploration of single-cell RNA-sequencing models, I will use Tabula Muris as an example. The Tabula Muris is a collaborative effort to profile every mouse tissue at a single-cell level. The full dataset includes both high throughput but low-coverage 10X data and lower throughput but high-coverage Smartseq2 data.
This notebook used Smartseq2 data from the mouse brain. This data consists of:
1. An expression matrix where each column corresponds to a gene and each row corresponds to a single cell.
2. A metadata table describing each cell.

## Analysis
The analysis focuses on cleaning, preparing, reducing dimensions, and clustering gene expressions into cell types. 

For more information on the analysis, you can read the articles on [my Medium](https://medium.com/@indranil_11057). 
