# General Bioplex LLOQ replacement
# CJ Harbort
# 01.03.2017

## This script takes a generic bioplex result file and replaces 
## out of range values with the LLOQ, and *** with NAs determined by BioRad

## FORMAT:
        ### Make a tab delimited file of 24 columns: 
        ### first column is sample names or wells, followed by 23 cytokines in columns

## Change the working directory to wherever your file is, it will save the final results as 
        ### Replacedvalues.csv - file of bioplex data 
        ### Replacementvector - list of how many changes were made for LLOQ 

## Compare Replaced.df with Original.df as control
