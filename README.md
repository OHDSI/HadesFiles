# HADES files


Large files for HADES that we prefer not to have in the HADES package, to minimize download size. 

## Background

Whenever someone calls `remotes::install_github("ohdsi/Hades"), this downloads the entire Hades repo, which therefore shouldn't be too big. The repo contains both the R package and the HADES website. We move large files from the website to this repo, and link to those.

Currently only contains the PaRe reports. 
