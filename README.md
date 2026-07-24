# scrnaseq-integration

This project aims to integrate single-cell RNAseq data from 2 different 10x Genomics datasets (10k healthy and 10k diseased PBMCs) using Seurat (R) in order to remove batch effects and cluster cells by cell type. The dataset was integrated, then labeled based on canonical markers. 

## Data Information 

### **Healthy PBMCs** 
- **Dataset**: [10k Human PBMCs, 5' v2.0, Chromium X](https://www.10xgenomics.com/datasets/10-k-human-pbm-cs-5-v-2-0-chromium-x-2-standard-6-1-0)
- **Source**: 10x Genomics 

### **Diseased PBMCs**
- **Dataset**: [10k Human Diseased PBMCs (Myelofibrosis) Freshly Processed](https://www.10xgenomics.com/datasets/10k_3p_Human_diseased_PBMC_Myelofibrosis_Fresh)
- **Source**: 10x Genomics 