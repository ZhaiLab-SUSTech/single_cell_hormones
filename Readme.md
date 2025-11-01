## Requirments
  1. Data Required
      - Genome file
        - Arabidopsis (Genome: TAIR10, GTF: Araport11)
     - TF info (https://github.com/VIB-PSB/MINI-EX/tree/main/data/ath)
    - Raw sequencing data, which can be accessed at NGDC database.
  2. Softwares Required

> **Dependency management**
>
> Except for **`miniex`**, all required dependencies **and their pinned versions** are specified in the **`jpy_tools`** requirements file. Installing `jpy_tools` will pull in everything else automatically. Please install **`miniex`** separately.

      - CellRanger (Used for processing 10x raw data)
      - jpy_tools (A wrapper of single-cell analysis tools, which is available here [jpy_tools](https://github.com/liuzj039/jpy_tools/tree/master/jModule)) 
      - scanpy  (Used for downstream analysis of 10X data)
      - Seurat (Used for downstream analysis of 10X data)
      - scDblFinder (Used for removing putative doublets)
      - harmonypy (Used to implement 10X data integration)
      - AUCell (Used for calculating gene set expression score)
      - miniex (Used for GRN prediction)
      - rpy2 (Used to implement invocation of R packages in python environment)
      - DESeq2 and EdgeR
      - networkx
      - pyranges
      - seaborn
      - marsilea
      - matplotlib 
      - muon
      - pyarrow
      - cellex
  
  
## Main steps

### Preprocessing
1. Get 10X cell-gene matrix using Cell Ranger. 
2. Based on the scripts used in the jupyter notebook to process the 10X gene matrix. All required external resources are annotated in the notebook.
### Analysis

These jupyter files contains the scripts needed for downstream analysis. Github often fails to preview large jupyter files, so you can preview these files using [nbviewer](https://nbviewer.org/github/ZhaiLab-SUSTech/single_cell_hormones/tree/main/). 

