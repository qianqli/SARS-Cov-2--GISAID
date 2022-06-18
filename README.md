# SARS-Cov-2 data source, methods, publications summary 
This repo summarize the tools used in the analysis of SARS-Cov data. Some papers are also recommended here. 


## Data Sources
### 1, GISAID: Global Initiative on Sharing All Inflenza Data: https://www.gisaid.org/
The GISAID Initiative promotes the rapid sharing of data from all influenza viruses and the coronavirus causing COVID-19. 

### 2, COG-UK Mutation Explorer: http://sars2.cvr.gla.ac.uk/cog-uk/ 
This gives the SARS-Cov data in UK, including data update, features analysis(anigenic, drug resistance, et al), and very good visulization. 

### 3, CoV-GLUE: A Web Application for Tracking SARS-CoV-2 Genomic Variation: http://cov-glue.cvr.gla.ac.uk/ 
CoV-GLUE maintains a database of mutations, insertions and deletions which have been observed in GISAID hCoV-19 sequences sampled from ongoing COVID-19 pandemic. 

### 4, Nextstrain - ncov https://github.com/nextstrain/ncov/blob/50ceffa/defaults/annotation.gff 
Genome annotation of SARS-Cov-2 in GFF format. 
There is a link avaliable for GFF format reference. https://www.ensembl.org/info/website/upload/gff.html

### 5, CDC(Centers for Disease Control and Prevention) https://github.com/CDCgov 
Gives data about prime, sequencing data summary...
#### ITF_Power_BI : gives a summary for SARS-Cov data. 

### 6, COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University  https://github.com/CSSEGISandData/COVID-19 
very cool real-time dashboad for SARS-Cov. This also gives summary and link of lots of data sources. 

### 7， OWID(our world in data) https://github.com/owid/covid-19-data
a repo collect the published data including SARS-Cov, hospitalization, tests, vaccinations...

### 8, UCSC: http://hgdownload.soe.ucsc.edu/goldenPath/wuhCor1/UShER_SARS-CoV-2/ 
phylogenetic trees of fully public SARS-CoV-2 sequences

### 9，UShER phylogenies of public data  http://hgdownload.soe.ucsc.edu/goldenPath/wuhCor1/UShER_SARS-CoV-2/ 
phylogenetic trees of fully public SARS-CoV-2 sequences updated daily.

### 10, outbreak.info https://outbreak.info/    Github: https://github.com/outbreak-info/R-outbreak-info
SARS-Cov-2 variant mutation tracker

## Tools -- focusing on github code based on publications
### 1, Nextstrain https://github.com/nextstrain  and web 
Real-time tracking of pathogen evolution. 
There are many related tools:
#### Nextclade : Viral genome alignment, mutation calling, clade assignment, quality checks and phylogenetic placement
#### agur : Pipeline components for real-time phylodynamic analysis 
#### There are some data available. 

### 2, CoV-lineages https://github.com/cov-lineages 
#### pangolin: Software package for assigning SARS-CoV-2 genome sequences to global lineages.

### 3, CDC(Centers for Disease Control and Prevention) https://github.com/CDCgov 
#### MIcrobetrace : The Visualization Multitool for Molecular Epidemiology and Bioinformatics 
#### ITF_Power_BI ： code for dashboard 

### 4, OWID(our world in data) https://github.com/owid/covid-19-data
This repo collect scripts to generate data like vaccination, hospitail, tests... 



## Publications
### 1, Harvey, William T., et al. "SARS-CoV-2 variants, spike mutations and immune escape." Nature Reviews Microbiology, 2021
This review summarize literatures on mutations of SARS-CoV-2 spike protein, focusing on their impacts on antigenicity. There are also S-protein structrure to explain the mutations causing immune escape. 

### 2, Maher M C, Bartha I, Weaver S, et al. Predicting the mutational drivers of future SARS-CoV-2 variants of concern[J]. Science translational medicine, 2022, 14(633): eabk3445.
This paper is to predict which existing amino acid mutations in SARS-CoV-2 might contribute to future variants of concern.
code: https://github.com/cyrusmaher/MutationEpiScore 

### 3, Obermeyer F, Jankowiak M, Barkas N, et al. Analysis of 6.4 million SARS-CoV-2 genomes identifies mutations associated with fitness[J]. Science, 2021: abm1208.
developed a model-- PyR0: a hierarchical Bayesian multinomial logistic regression model that infers relative prevalence of all viral lineages across geographic regions, detects lineages increasing in prevalence, and identifies mutations relevant to fitness.
PyR0 : https://github.com/broadinstitute/pyro-cov  
