## **[Metabolomic Analysis of Gut Metabolites in Colorectal Cancer Patients (CRC)](https://link.springer.com/article/10.1007/s00726-025-03448-3)**  
In this study, I performed in-depth metabolomic profiling of colorectal cancer (CRC) through a robust workflow.
Data was normalized using Probabilistic Quotient Normalization (PQN) to account for sample dilution effects, followed by differential expression analysis. To uncover systems-level organization, I applied Weighted Gene Co-expression Network Analysis (WGCNA), identifying metabolite modules associated with CRC phenotypes. Module eigengene differentiation was applied to identify modules that significantly distinguish CRC from healthy controls, and Intra-modular connectivity analysis was performed to characterize central drivers within these networks. Dimensionality reduction approaches (PCA, PLS-DA) were further employed to refine discriminative features. This integrative approach highlighted top metabolites distinguishing CRC patients from controls and revealed network-level metabolic dysregulation with potential biomarker and therapeutic implications.  
**[Bookdown](https://bits-and-bites.netlify.app/)**  
**[Paper Link](https://link.springer.com/article/10.1007/s00726-025-03448-3)**   

**Description:**  
This book presents a comprehensive, R-based pipeline for metabolomics data analysis, from data preprocessing and normalization to network construction, visualization, and functional enrichment analysis. By integrating state-of-the-art tools such as WGCNA and MetaboAnalyst, the workflow enables systematic exploration of metabolomics datasets to uncover biologically meaningful patterns.
The pipeline has been applied in our published study: Ramzy, A., Abdelmoneim, T.K., Arafat, M., et al. (2025). Metabolomic analysis reveals key changes in amino acid metabolism in colorectal cancer patients. Amino Acids, 57, 22. https://doi.org/10.1007/s00726-025-03448-3    
Please note:  The workflow is identical to that described in our published paper, with the exception of a minimal change in the normalization step.
- The workflow does not include the manual curation step, which involves comparing MS/MS experimental spectra against reference libraries (e.g., HMDB, METLIN, GNPS, MassBank).
- The dataset provided here is a shuffled version. The original data can only be obtained from the corresponding author.  

**Bookdown**     
You can find the rendered book at (https://bits-and-bites.netlify.app/). 
