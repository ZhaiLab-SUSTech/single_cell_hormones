## Requirments
  1. Data Required
      - Genome file
        - Arabidopsis (Genome: TAIR10, GTF: Araport11)
        - TF info (https://github.com/VIB-PSB/MINI-EX/tree/main/data/ath)
  2. Softwares Required
      - CellRanger (Used for processing 10x raw data)
      - scanpy  (Used for downstream analysis of 10X data)
      - Seurat (Used for downstream analysis of 10X data)
      - scDblFinder (Used for removing putative doublets)
      - harmonypy (Used to implement 10X data integration)
      - AUCell (Used for calculating gene set expression score)
      - miniex (Used for GRN prediction)
      - jpy_tools (A wrapper of single-cell analysis tools, which is available here [jpy_tools](https://github.com/liuzj039/jpy_tools/tree/master/jModule))
      - rpy2 (Used to implement invocation of R packages in python environment)

## Main steps

### Preprocessing
1. Get 10X cell-gene matrix using Cell Ranger

### Analysis

These jupyter files contains the scripts needed for downstream analysis. Github often fails to preview large jupyter files, so you can preview these files using [nbviewer](https://nbviewer.org/github/ZhaiLab-SUSTech/single_cell_hormones/tree/main/). 

## Others
- The gene expression pattern can be explored at our [website](https://zhailab.bio.sustech.edu.cn/single_cell_hormone/)
  - If you found any bugs in our website, please reported [here](https://github.com/ZhaiLab-SUSTech/single_cell_hormones/issues/new)

