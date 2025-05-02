# Glomeruli-Sc-seq-analysis
# set uo new lib path for sctransform
dir.create("~/R_clean_lib", showWarnings = FALSE)
.libPaths(c("~/R_clean_lib", .libPaths()))
install.packages("sctransform", lib = "~/R_clean_lib")
library(sctransform, lib.loc = "~/R_clean_lib")
