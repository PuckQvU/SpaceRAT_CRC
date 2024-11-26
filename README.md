# SpaceRAT_CRC

The consensus molecular subtypes (CMSs) of colorectal cancer can offer valuable insights into the biological nature of a tumor and are linked to patient prognosis and treatment outcomes. However, CMS classification remains largely unused in clinical research and patient care. In this project, we aim to address the technical challenges in using this classification scheme for NanoString nCounter data.

The aims of this project were to:

1.  Simulate NanoString nCounter data from RNA-seq data;
2.  Evaluate the accuracy of existing methods for CMS classification in both RNA-seq and NanoString data;
3.  Build scaffolds for CMS classification using the SpaceRAT package;
4.  Evaluate the usefulness of the scaffolds by projecting samples with known CMS labels into them.

The data that was used for this project was obtained from the Colorectal Cancer Subtyping Consortium (CRCSC) [Synapse page](https://www.synapse.org/Synapse:syn2623706/files/) (DOI: [10.7303/syn2623706](https://doi.org/10.7303/syn2623706)). This source contains data from several RNA-seq and microarray projects, as well as CMS labels for the samples. For this project, we have used RNA-seq expression data from the TCGA dataset.

The R folder contains 10 ordered quarto files that allow you to reproduce the results of this project.

The results folder contains the scaffolds that were built in SpaceRAT. It also contains HTML files that were rendered from the files in the R folder, which contain the code as well as the results that were obtained.
