# Calculate siRNA for Gene Sequences

This script takes gene sequences and calculates all possible siRNA interactions. An siRNA interaction site is defined as a 22-nt sequence of $$AWWWW-D--U------A-----$$ where 

$D=[A,G,U],

W=[A,U]$ 

and $-$ denotes a complement. 


The corresponding siRNA is defined as $$UWWWW-H--A------U-----$$ where $$H=[A,C,U]$$

This tool enables efficient calculation of siRNA-target pairs, facilitating RNA interference (RNAi) research and gene silencing studies.

Gene Data can be downloaded at https://www.ensembl.org/info/data/biomart/index.html. Just go to Ensembl12 -> Zebrafish Gene (GRCz11) and select 'Structure' under attributes. 
