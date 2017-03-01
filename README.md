# General Bioplex LLOQ replacement
# CJ Harbort
# 01.03.2017

This script takes a generic bioplex result file and replaces any 
out of range values with the LLOQ, and ``***`` values with NAs.
Also renames the cytokine columns with simple cytokine names.

In the end, saves a new file with replaced values and a file showing how
many replacements were made for each cytokine.

FORMAT:
       Make a tab delimited file of 24 columns: 
       first column is sample names or wells, followed by 23 cytokines in columns

Change the working directory to wherever your file is, it will save the final results as 
       Replacedvalues.csv - file of bioplex data 
       Replacementvector - list of how many changes were made for LLOQ 

Compare Replaced.df with Original.df as control
