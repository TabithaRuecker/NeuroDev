# RNA seq data analysis
## In this folder, both metaData as well as countData for the RNA-seq analyses are stored.
The countData will be removed soon, once GEO has confirmed the application and provided an accession number.
* * countTable_RNAseq.csv is the countData resulting from the preprocessing pipeline (TrimGalore!, STAR, featureCounts)
  * metaE_Annotation.csv is the matching metaData. Use this table together with the countData to reproduce the analyses presented in the dissertation.

- For the DEG analyses focused on the "special" population, the following outputs were created:
  * ConsecutiveAnalysis_special.xlsx
  * MulticomparisonAnalysis_special.xlsx
 
- For the DEG analyses on both "ctrl" and "special" population, the following outputs were created:
  * with enhanced Age contrast:
  * * E14toP7_PopulationAge_redPopulation.xlsx
  * with enhanced Cell Population contrast:
  * * E14toP7_AgePopulation_redAge.xlsx

- For analyses around the birth time point (E19):
  * Birth_DEGs.xlsx
   
- For the DEG analyses with WGCNA (Treatment-based contrast):
  * MIA_DEGs.xlsx
