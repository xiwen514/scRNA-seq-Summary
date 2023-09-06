# scRNA-seq-Summary

#### Introduction:
This section aims to provide a comprehensive summary of the insights and lessons I have gained from my experience in analyzing single-cell sequencing data. It encompasses essential aspects such as commonly used code for routine analyses, frequently employed databases, strategies to address specific challenges encountered, and approaches for debugging errors.
#### Key Tutorials:
Two tutorials that I frequently rely on for single-cell sequencing data analysis are OSCA and Seurat. These tutorials utilize distinct data structures: OSCA employs SingleCellExperiment, while Seurat utilizes its own custom structure called "seurat."

##### Public databases：
1. TISCH: http://tisch.comp-genomics.org/home/
Tumor Immune Single-cell Hub 2 (TISCH2) is a scRNA-seq database focusing on tumor microenvironment (TME). TISCH2 provides detailed cell-type annotation at the single-cell level, enabling the exploration of TME across different cancer types. The majority of the species analyzed were humans, with a small portion being mice. The predominant platforms used were 10X Genomics, with a smaller portion utilizing technologies such as Smart-seq, CITE-seq, and Microwell, among others. The treatments administered encompassed various options, including immunotherapy, chemotherapy, targeted therapy, as well as cases where no treatment was applied.
2. XENA: https://xenabrowser.net/datapages/
3. GEO
4. TCGA

   
##### cell type annotation
1. singleR
2. seurat
3. mannually annotation
4. Azimuth
   
##### Batch effect correction
1. combat
2. limma
3. TAMPOR
   
##### Exploratory analysis
1. pca
2. heatmap
3. boxplot
4. volcano plot
   
##### Differentital expression analysis
1. edgeR
2. Deseq2
   

##### Differential abundance analysis


