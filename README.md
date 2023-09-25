# scRNA-analysis

The commands in the document only goes uptil the pre-processing of aligned single-cell RNA transcript files as we were not able to perform velocity analysis.

The pipeline for advanced scRNA-seq is as follows:

1. Download desired sequence(s)
2. Quality control (FastQC)
3. Trimming (fastp)
4. Align to human genome (HISTA2)
5. Sort alignment file (samtools)
6. Index alignment file (samtools)
7. Deduplicate (Picard)
8. Generate read count matrix (HTSeq)
9. Pre-process the count matrix (Seurat)
10. Advanced analysis of scRNA-seq 
