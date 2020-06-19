# BiGMeC - Biosynthetic Gene cluster Metabolic pathway Constructor
Constructed metabolic pathways for information on BGCs based on antiSMASH output.


"gbk_db_output_models.zip" contain the metabolic models constructed by BiGMeC.
Many of the metabolic models are empty, as we simply ran the 
code on the antSMASH output of ALL clusters in the MIBiG database.
Code is only suitable for clusters of type NRPS, TransAT-PKS and T1PKS
This means that many clusters of e.g. type bacteriocin or terpene have been processed by BiGMeC

When unzipping the file, the file names have the same number as the BGCs index in mibig.

E.g: BGC0000028 (bafilomycin) will be called "28.json"


AntiSMASH output of the files in MiBIG can be found in the file-anthology
"antismash_output_mibig_gbk_files" 1 through 3.

