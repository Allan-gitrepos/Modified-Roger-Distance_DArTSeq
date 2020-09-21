# Modified-Roger-Distance_DArTSeq
This function is for calculating modified Roger's distances of 2 row DArTSeq SNP data.

This function is written in R, With C++ backend for distance matrix compuation to speed up the compuatations. 

The input data will be the raw 2 row SNP allele matrix, or the single row frequency matrix with 1,0.5,0 format for SNP homozygtes, heterozygotes and Reference allele homozygote. 
