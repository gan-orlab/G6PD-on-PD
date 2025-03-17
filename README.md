# G6PD-on-PD
#This project was to determine the association between G6PD common and rare variants with Parkinson’s disease
#All cohorts were analyzed seperated by sex and combined together
#Cohorts sequenced at McGill
 Four cohorts sequenced at McGill G6PD was captured using molecular inversion probs.The full protocol is available at https://github.com/gan-orlab/MIP_protocol.
 Standart filtering procedures were done using MIPVar pipeline (https://github.com/gan-orlab/MIPVar).

#AMP-PD data cohort
  Data was attained using Terra platform (Data was already QC'd and imputed before at https://github.com/gan-orlab/ARSA/blob/main/AMP_PD). Alignment for these data was performed using the human reference genome (hg38)
  detailed filtration in AMP-PD script
  

#UKBB cohort
  UKBB data was accessed through Neurohub using UKBRAP 
  detailed filteration in UKBB script 

#Common variants association at MAF>1% was done using logistic models in plink
  
#burden analysis and meta-analysis between cohort was performed using CMC-burden Using (Rare variant) RV test and metagen packages
 Further information is described in CMC and Meta-analysis script

  
