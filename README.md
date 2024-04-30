# SiniscalcoTFR
Analysis of public scRNA-Seq data to identify TFR

### Analysis of Gribonika I et al. (2022) dataset
code:
- preprocessing: [[MD]](code/20240426_siniscalcoTFR.e-mtab-11805.md)

input:
- Cellranger H5 files: [[DIR]](input/)  
- Sample annotation: [[TSV]](input/E-MTAB-11805.sdrf.txt)  
  
output:  
- Seurat object will all cells: (data release) e-mtab-11805.seuratObj.RData  
- Seurat object with unstimulated T cells: (data release) tcellObj.cca.RData  
- Seurat object with unstimulated Foxp3 expressing cells (with Treg vs Tfr annotation): [[RDA]](output/foxp3Obj.unstim.RData)  
- Seurat object with stimulated T cells: (data release) stimObj.cca.RData  
- Seurat object with stimulated Foxp3 expressing cells (with Treg vs Tfr annotation): [[RDA]](output/foxp3Obj.stim.RData)


### Analysis of Le Cox C. et al. (2023) dataset
code:
- preprocessing: [[MD]](code/20240426_siniscalcoTFR.gse214572.md)  

input:
- Cellranger MTX files: [[DIR]](input/)  
  
output:  
- Seurat object will all cells: (data release) gse214572.seuratObj.RData  
- DEG between Treg and Tfrs: [[CSV]](output/gse214572.deg_treg_tfr.csv)  