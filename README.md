# Nemabiome_Final
Nemabiome validation study. 

Best to ignore!!!

The fastaq files can be found in this link: https://www.dropbox.com/scl/fo/hcj3uy5wrzjnkxlhcj8o5/h?dl=0&rlkey=5vblghon690x9ghp34o93xofs
NOTE: must check if that link contains all files as I have run out of space on it despite deleting other folders. NOTE: reference sequences available in Nema_ref_ver3_at.fas.

Data was processed in the DADA2 pipeline in the NEMA.Rmd file, they were then assigned taxonomy in the manual assignment.Rmd file. This was then used to construct the Nemabiome_Raw_Masterfile.xlsx file which contains all the basic data. This file was used to creaste Nemabiome-refined.xlsx. 

After assigning taxonomy to the sequences the ASVs were merged based on species in the Merged column.Rmd file. They were then copied and pasted into the excel file (Nemabiome-refined), after that they were analysed through the Sequence_Depth.Rmd, Coverage.Rmd and Copy_number.Rmd. 
