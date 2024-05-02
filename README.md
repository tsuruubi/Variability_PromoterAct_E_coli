# Mutational Variability in E. coli　 promoters

## Descriptions of folders
ENV_DataSet: the Env dataset comprising of transcriptome profiles (PRECISE 2.0) obtained from iModulonDB (http://imodulondb.org/)  
EVO_DataSet: the Evo dataset comprising of transcriptome profiles obtained from Rousset et al (https://doi.org/10.1038/s41564-020-00839-y)  
MUT_DataSet: the Mut dataset comprising of transcriptome profiles of our MA experiment  
RegulonDB: the regulatory relationships between transcriptional regulators and target genes obtained from RegulonDB (https://regulondb.ccg.unam.mx)  
W3110_cds: essential genes and gene names of E. coli W3110 strain used in the Mut dataset
MG1655_cds: gene names and locus tags of E. coli MG1655 strain  
BW25113_cds: essential genes of E. coli BW25113 strain  
Meta: metadata of promoters with ids, DNA sequences, categories, the means and sds of the GFP distributions, etc.  
pUA66_mCherry: plasmid map (the SnapGene format) of pUA66-mCherry  
RMF_output: outputs of the numerical evolutionary simulation on a rugged fitness landscape  
MutationRate: raw sequencing data (the ab1 format) in validation of mutation rate at error-prone PCR  
Stats_of_FlowData: statistics obtained by flow cytometry  
FCS2CSV_check: codes for testing conversion from the fcs format to the csv format  
OverExprs_Toxicity: the delay factor in over expressed genes (https://doi.org/10.3390/genes9080414)  


## Descriptions of scripts
Main_Analysis.Rmd: codes for analysis and figures  
FlowData_Analysis.Rmd: codes for calculating the means and sds of the GFP distributions  
RMF.Rmd (in RMF_outputN): codes for numerical evolutionary simulation on a rugged fitness landscape  
## Requirements:
R 4.3.2 or greator  