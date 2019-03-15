# LDanalysis
Pipeline in R used to calculate linkage disequilibrium (LD) and data vizualization of LD. 
That was one of steps used for results of the LD's research in Santa Inês ovine population : https://www.nature.com/articles/s41598-018-27259-7


*** Description of files ***
# geno:
            1. SNP ID
            2. Chromosome
            3. SNP position
            4. Genotype of animal 1, nitrogene basis. Example: GG, CC, AC, etc.
            5. Genotype of animal 2, nitrogene basis. Example: GG, CC, AC, etc.  
            ...
            column i.  Genotype of animal i, nitrogene basis. Example: GG, CC, AC, etc.
Assuming i is the number of animals.
Missing values assumed as "--".

# feno_teste2.txt:
            1. Animal ID
            2. Sex, as 1 and 0
            3. Trait

# SNP_Map.txt:
            1. SNP ID
            2. Chromosome
            3. SNP position
