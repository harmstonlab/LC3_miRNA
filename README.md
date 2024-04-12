# LC3_miRNA
* Code and data to recreate miRNA analysis from Goh et al 2024

## miRNA-seq

Set 1:
- GFP-KO (knock-out) : Control
- Atg7KO : ATG7 knockout abolishes autophagy-related exosome formation.
- Atg14KO : Control; Atg14 knockout doesn’t affect exosome pathway.

* ```set1/set1_analysis.Rmd``` -  is the script necessary for recreating the results of this analysis and contains all steps including quality control, differential expression and functional annotation.
* all results are stored in ```set1/results/```

## RNA-seq

RNA-seq data was downloaded from GEO (GSE133524 - Talbert et al 2019) and aligned against mm10, Ensembl 102 using STAR and quantified using RSEM. 

* ```talbert_et_al/Differential Expression.Rmd``` - is the script necessary for recreating the results of this analysis and contains all steps including quality control, differential expression and functional annotation. 
* all results are stored in ```talbert_et_al/results/```

## Annotation files 

* due to constraints the corresponding gtf and TargetScan data is not stored as part of this repository if this is required please contact us and we will find a way to provide this to you.




