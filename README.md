This repository has commands related to Kim & De-Kayne et al. XXXX  (URL XXX)  
This paper highlights the structure of each of the three alleles of the Danaus wing-pattern supergene

The commands in `all_danaus_structure_commands.txt` cover:  
1. The polishing of the MB18102 MAT and PAT assemblies  
2. The repeat annotation and genome annotation of both MB18102 assemblies  
3. The repeat annotation and genome annotation of both SB211 assemblies  
4. The filtering of gene alignments and production of gene trees for the full genome and each of the structural rearrangements  
5. TE landscapes for chr15 equivalent  
  
A number of additional files are also included such as:  
The full gene tree:  
`gene_tree.txt`  
  
Pruned gene trees for each of the inversions:  
Region 1.2 - inverted in chrysippus only `chrysippus_inv_concat.raxmlout.BS70.nwk`  
Region 1.1 - inverted in orientis only `orientis_inv1_excl_chrysippus_inv_concat.raxmlout.BS70.nwk`  
Region 2 - inverted in orientis only `orientis_inv2_concat.raxmlout.BS70.nwk`  
Region 4 - inverted in orientis only `orientis_inv3_concat.raxmlout.BS70.nwk`  

Additional code for the production of TE landscapes (using a custom script GetTEBed) can be found [HERE](https://github.com/RishiDeKayne/GetTEBed)  
