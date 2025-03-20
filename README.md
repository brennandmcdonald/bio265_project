## BIO265 Final Project: Brennan McDonald, Jordan Kalai, Heidi Tate, Sarah Weber 

The following repository includes code to process and analyze the 48 hpf H. erythrogramma single cell RNA sequencing dataset from McDonald et al., 2024.

# Contents 
1. he48hpf_raw: folder includes zipped versions of the raw data files from the NCBI Gene Expression Omnibus database for user convenience.
2. process_data.ipynb: The first code which should be run after unzipping raw data, includes code for processing scRNA-seq data so that UMAPs and analysis between cells can be completed easily.
3. analyze_data.ipynb: The second code which can be run post-processing to reproduce the grpahs seen in our final paper.
* Note: the he48 processed data file is included in this repository for convenience of the user, but would not normally be included due to the large file size.

*References*
1. McDonald BD, Massri AJ, Berrio A, Byrne M, McClay DR, Wray GA. 2024. Contrasting the development of larval and adult body plans during the evolution of biphasic lifecycles in sea urchins. Development. 151(20): dev203015. https://doi.org/10.1242/dev.203015
2. Wolf FA, Angerer P, Theis FJ. 2018. SCANPY: large-scale single-cell gene expression data analysis. Genome Biology. 19: 15. https://doi.org/10.1186/s13059-017-1382-0.
