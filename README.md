# scRNA-seq-Summary

#### 总结一些我在做单细胞测序数据分析时一些收获和心得，包括常规分析的代码，常用的数据库以及遇到的具体问题怎样来处理，一些报错怎样debug等等。
#### 我比较常用的tutorial有两个，分别是OSCA和seurat。这两个采用的数据结构也是不同的，OSCA 采用的是SingleCellExperiment， 而seurat 采用的是自己的结构-seurat。
#### Introduction:
This section aims to provide a comprehensive summary of the insights and lessons I have gained from my experience in analyzing single-cell sequencing data. It encompasses essential aspects such as commonly used code for routine analyses, frequently employed databases, strategies to address specific challenges encountered, and approaches for debugging errors.
#### Key Tutorials:
Two tutorials that I frequently rely on for single-cell sequencing data analysis are OSCA and Seurat. These tutorials utilize distinct data structures: OSCA employs SingleCellExperiment, while Seurat utilizes its own custom structure called "seurat."

##### 单细胞公共数据库：
1. TISCH: http://tisch.comp-genomics.org/home/
Tumor Immune Single-cell Hub 2 (TISCH2) is a scRNA-seq database focusing on tumor microenvironment (TME). TISCH2 provides detailed cell-type annotation at the single-cell level, enabling the exploration of TME across different cancer types. The majority of the species analyzed were humans, with a small portion being mice. The predominant platforms used were 10X Genomics, with a smaller portion utilizing technologies such as Smart-seq, CITE-seq, and Microwell, among others. The treatments administered encompassed various options, including immunotherapy, chemotherapy, targeted therapy, as well as cases where no treatment was applied.
2. XENA: https://xenabrowser.net/datapages/
3. GEO
4. TCGA

##### 怎样在不同的癌种数据中选取表达稳定且表达值较高的的基因?
1. CV
2. mean
   
##### 细胞类型注释的方法有哪些?
1. singleR
2. seurat
3. 手动注释
4. Azimuth
   
##### 判断batch effect以及怎样矫正？
1. combat
2. limma
3. TAMPOR
   
#### exploratory analysis
1. pca
2. heatmap
3. boxplot
4. volcano plot
   
#### differentital expression analysis
1. edgeR
2. Deseq2
   

#### differential abundance analysis


