# Metagenomic and metatranscriptomic insight into the roles of millipede hindgut microbiome
========



Analysis of 16S, metagenomes and metatranscriptomes included in the paper: Functional similarity despite taxonomical divergence in the millipede gut microbiota points to a common trophic strategy

Overview
--------

  ├── 1_Bacterial_Colony_Counts_and_qPCR_Qunatification.Rmd
  
  
          ├── Control_qQPCR_ColonyC.ods
          
          
          ├── Control_qPCR_ColonyC.html
          
          
          ├── Control_qPCR_ColonyC.md
          
          
  ├── 2a_cutadapt_v2.0.sh
  
  
          ├── 2a_cutadapt.log
          
          
  ├── 2b_DADA2_16S_merge_V8.6.sh
  
  
          ├── 2b_run_DADA2_16S_V8.6.R
          
          
  ├── 2c_Decontamination.Rmd
  
  
          ├── 2c_Decontamination.md
          
          
          ├── 2c_Decontamination.html
          
          
  ├── 3_Community_ORFs_Classification_and Functional_Genes_Analysis.Rmd
  
  
          ├── 3_Community_ORFs_Classification_and Functional_Genes_Analysis.md
          
          
          ├── 3_Community_ORFs_Classification_and Functional_Genes_Analysis.html # Run after assembly (4a_Assembly.sh)
          
          
  ├── 4a_Assembly.sh
  
  
          ├── final.contigs.fa
          
          
          ├── options.json
          
          
          ├── log
          
          
  ├── 4b_MG_Mapping.sh
  
  
          ├── contigs.fa
          
          
          ├── name_conversions.txt
          
          
          ├── Sample.bam.bai
          
          
          ├── Sample.bam
          
          
          
          
  ├── 4c_MG_Anvio_database.sh
  
  
          ├── contigs.db
          
          
          ├── contigs-stats.csv
          
          
          ├── gene_calls.fa
          
          
  ├── 4d_MG_Centrifuge.sh
  
  
          ├── centrifuge_hits.tsv
          
          
          ├── centrifuge_report.tsv
          
          
  ├── 4e_MG_Profiling.sh
  
  
          ├── AUXILIARY-DATA.db
          
          
          ├── PROFILE.db
          
          
          ├── RUNLOG.txt
          
          
          
  ├── 5_Phylogenomics.sh
  
  
          ├── Metabat2_taxa_info-gtdb-tk.txt
          
          
          ├── Metabat2-phylogenomic-tree.txt
          
          
  ├── 6_MAG_Novelty_abundance.Rmd
  
  
          ├── 6_MAG_Novelty_abundance.md
          
          
          ├── 6_MAG_Novelty_abundance.html
          
          
  ├── 8_Abundance_of_Genes_MG_MT.Rmd
  
  
          ├── 8_Abundance_of_Genes_MG_MT.md
          
          
          ├── 8_Abundance_of_Genes_MG_MT.html
          
          
  ├── 9_CAZymes_Genes.Rmd
  
  
          ├── 9_CAZymes_Genes.md
          
          
          ├── 9_CAZymes_Genes.html


   ├── 10_Eukaryotic_abundance.Rmd
          
          
   ├── README.md # Overview of the repo
   
   
    └── references.bib  # Bibtex formatted references cited in the RMD file
    
    

Viewing and reproducing the analysis
--------
The MD files can be used to display the output on github, while HTML files can be used for offline viewing. 
The RMD files are best compiled using [knitr](https://yihui.name/knitr/) on [RStudio](https://www.rstudio.com/). 
          
