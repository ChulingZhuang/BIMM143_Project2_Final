# BIMM143_Project2_Final_Chuling_Zhuang
*This is the final draft of BIMM143 Project2 by pythonista Chuling Zhuang.

Scientific question: Does the reduction of protein tyrosine phosphatase receptor type S (PTPRS) expression contribute to breast ductal carcinoma metastasis? If yes, is the Epithermal Growth Factor Receptor (EGFR) mediated EMT (epithelial-mesenchymal transition) pathway involved, or what other pathways are involved?  

Scientific Hypothesis: If PTPRS is shown as a metastatic suppressor in hepatocellular carcinoma, then it may also exhibit a similar regulatory role in breast ductal carcinoma and the loss of PTPRS may also contribute to the breast cancer metastasis by regulating similar mediators like EGFR.

3 files are needed to successfully run the code:

1) The jupytor notebook ([BIMM143_Project2_final.ipynb](https://github.com/ChulingZhuang/BIMM143_Project2_Final/blob/main/BIMM143_Project2_final.ipynb)).
2) The csv file containing TPM count results of RNA seq ([30_breast_cancer_rna_TPM.csv](https://github.com/ChulingZhuang/BIMM143_Project2_Final/blob/main/30_breast_cancer_rna_TPM.csv)).
3) The csv file containing experimental design of RNA seq ([30_breast_cancer_rna_experiment_design.csv](https://github.com/ChulingZhuang/BIMM143_Project2_Final/blob/main/30_breast_cancer_rna_experiment_design.csv))

Information about the source of csv files:
    The RNA-seq results of 30 breast cancer cancer cell lines were obtained from EBI Expression Atlas database. I found this experiment by clicking on the "browse experiment" tab in the mainpage, and search "RNAseq breast" in the "Title" query. The experiment "Variation in RNA expression in a panel of 30 breast cancer cell lines" is the first result of the query and it performed RNA-seq on 30 breast cancer cell lines of Homo Sapiens. To download these file, I first clicked "Downloads" tab in the page of this experiment, and clicked "Expression values across all genes (TPM)" for the file containing TPM count results, and "Expression Design (tsv)" containing information about experimental details. 
    
Note: The original files are tsv files, and I converted them into csv files for convenience.

    
Enjoy!
