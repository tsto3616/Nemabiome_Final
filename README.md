# Nemabiome_Final
Nemabiome validation study. 

The fastaq files can be found in this link, as well as the accompanying reference database: 

Data was processed in the DADA2 pipeline in the NEMA.Rmd file, they were then assigned taxonomy in the manual assignment.Rmd file. This was then used to construct the Nemabiome_Raw_Masterfile.xlsx file which contains all the basic data. This file was used to creaste Nemabiome-refined.xlsx. 

After assigning taxonomy to the sequences the ASVs were merged based on species in the Merged column.Rmd file. They were then copied and pasted into the excel file (Nemabiome-refined), after that they were analysed through the Sequence_Depth.Rmd, Coverage.Rmd and Copy_number.Rmd. 
