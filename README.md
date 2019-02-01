# Integrating genetics with single cell RNA-seq

The paper is currently on bioRxiv and can be accessed [here](https://www.biorxiv.org/content/10.1101/528463v1).

The code to reproduce our results is located in this repository. The following links show the essential steps:

1) Get GWAS summary statistics in the right format for MAGMA and LDSC. [Code](Code_Paper/Code_GWAS/get_GWAS_input.md)

2) Get MAGMA and LDSC input for the Zeisel et al. data set. [Code](Code_Paper/Code_Zeisel/get_Zeisel_input.md)

3) Get MAGMA and LDSC input for the GTEx et al. data set. [Code](Code_Paper/Code_GTEx/get_GTEx_input.md)

<<<<<<< HEAD
4) Get MAGMA and LDSC input for the Skene et al. data set. [Code](Code_Paper/Code_Skene/get_Skene_input.md)

5) Get MAGMA and LDSC input for the Skene et al. data set. [Code](Code_Paper/Code_Habib/get_Habib_input.md)

6) Get MAGMA and LDSC input for the Skene et al. data set. [Code](Code_Paper/Code_Saunders/get_Saunders_input.md)

=======
>>>>>>> ea5a3788b0585a60b4af9a4e04ec7b8d8c3d3d06
## Run MAGMA

Once the GWAS sumstats are ready and the specificity files are ready, you can use the following [code](Code_Paper/Code_Zeisel/run_MAGMA.md) to test for associations using MAGMA (Zeisel data set in this example).

<<<<<<< HEAD
If you want to run your GWAS with our specificity files, you just need to get the 'Lvl5_spe_norm_no_filter.txt' files in the different MAGMA folders and run the code above.

=======
>>>>>>> ea5a3788b0585a60b4af9a4e04ec7b8d8c3d3d06
## Run LDSC

Once the GWAS sumstats are ready and the specificity files are ready, you can use the following [code](Code_Paper/LDSC_pipeline/README.md) to test for associations using LDSC.

The code to look for heritability enrichment of the top10% most specific genes was made to be run in parallele on a SLURM cluster. It would need to be adapted if you want to run it locally.

**Under construction**

To do: 
<<<<<<< HEAD
1) Add LDSC get pvalue file
=======
1) Add Saunders, Habib and Skene datasets processing files
2) Add LDSC get pvalue file
3) Clean a bit
>>>>>>> ea5a3788b0585a60b4af9a4e04ec7b8d8c3d3d06
