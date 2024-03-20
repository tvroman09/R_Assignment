# R_Assignment
R assignment 
This code is organized in three parts: data inspection, data processing, and data visualization. Two files are analyzed, fang_et_al_genotypes.txt and snp_position.txt. Together, these files are used to explain chromosome content and position. 

Data Inspection

The data is read in and inspected. The following data inspection tells us the following pieces of information:

Fang

File size: 22681376 bytes

Dimension: 2782x986

Class: data frame

SNP

File size: 525582 bytes

Dimension: 1017x15

Class: data frame

Data Processing 

The code creates a column for each identified group of interest. It then transposes a file and moves the rownames to its own column, while joining the two files together and keeping the data aligned. I then create data frames for Chromosome, Position, and Category data. The code then filters the data to create 40 files, two per each maize and teosinte group. Ten files per group are organized by increasing SNP, and 10 files per group are organized by decreasing SNP.

Data Visualization

I create several plots, the first showing SNP count by Chromosome. The next section creates two plots, one with maize SNP count and one with teosinte SNP count - which appear to be the same. The next chunk creates a normalized plot of Homozygous, Heterozygous, and Missing data. This code looks at the plot of count per specific group previously analyzed. 
