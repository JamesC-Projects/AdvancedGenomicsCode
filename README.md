# AdvancedGenomicsCode
This will contain the code and crucial datasets needed to replicate the analyses performed in Advanced Genomics

This assignment aims to take data from EBI project (Study: ERP005558) and perform quality control, followed by Kraken 2
paired-read alignments to the 8gb standard database. This will produce output files showing species identified in the samples
as determined by the Kraken2 standard database, with Bracken used to calculate the abundance of different species in the samples and
LefSe used to calculate statistically significant species expression between samples. 

In Part 2, the trimmed reads for K1 were then stitched using Flash. Afterwhich Megahit was used to determine the length of contigs which could be assembled from them - visualised using Quast. Metabat was then used to place the assembled contigs into bins based on predicted species similarity - two bins were made, K1.1.fa and K1.2.fa. Bins created from all of the Korean data was downloaded (K1.1.fa to K1.30.fa) and Bakta was used to create gff3 files from them, assigning contigs to most likely genes.
