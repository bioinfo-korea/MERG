# MERG (A meta-analysis of repeat genome-wide association studies)
We show that a meta-analysis of repeat GWASs (MERG) can detect many significant results, which is difficult with a conventional GWAS, even with thousands of samples. Moreover, our MERG showed high reproducibility. Among the results, known type 2 diabetes-associated variants were enriched significantly. Source code and supplementary documentation can be found at https://github.com/bioinfo-korea/MERG.git.

# INSTALL & RUN

1. Install R (www.r-project.org) & Rstudio (https://www.rstudio.com/)
2. command line
> install.packages("metap")
3. Download R codes (https://github.com/kimsc77/MERG/issues/1)
4. Unzip MERG.zip
5. Load 7 R codes(fishers.R, stouffers.R, Mstouffers.R, pooledZ.r, pooledChi.r, Re.pooledZ.r, Re.pooledChi.r)
> source("RCODE.R") ex) source("fishers.R")


