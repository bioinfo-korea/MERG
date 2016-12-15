# MERG (A meta-analysis of repeat genome-wide association studies)
We show that a meta-analysis of repeat GWASs (MERG) can detect many significant results, which is difficult with a conventional GWAS, even with thousands of samples. Moreover, our MERG showed high reproducibility. Among the results, known type 2 diabetes-associated variants were enriched significantly. Source code and supplementary documentation can be found at https://github.com/bioinfo-korea/MERG.git.

# INSTALL & RUN

Install R (www.r-project.org) & Rstudio (https://www.rstudio.com/)
Install Shiny package (https://cran.r-project.org/web/packages/shiny/index.html)
command line
> install.packages("Shiny")
Download R codes (https://github.com/kimsc77/COEX-seq/issues/3)
Unzip COEX-seq.zip
load server.r and ui.r
Download Reference Dataset (https://github.com/kimsc77/COEX-seq/issues/2)
Ensemble_length.txt
Entrez_length.txt
GenBank_length.txt
GeneSymbol_length.txt
Run server.r(or ui.r) using Rstudio
Select Before Measurement : ex) Count
Select After Measurement : ex) TPM
Load Input file : ex) example file (https://github.com/kimsc77/COEX-seq/issues/1)
Click: Header, Seperator
Click Submit
