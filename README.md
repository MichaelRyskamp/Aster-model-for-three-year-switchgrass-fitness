[![DOI](https://zenodo.org/badge/589322245.svg)](https://zenodo.org/badge/latestdoi/589322245)

Supplementary material for a draft paper

> Three-year fitness of *Panicum virgatum* infected with switchgrass mosaic virus  
> Michael P. Ryskamp and Charles J. Geyer ([github.com/cjgeyer](https://github.com/cjgeyer))

To remake the PDF file do

    Rscript -e 'rmarkdown::render("Switchgrass_SwMV_3-yr-Fitness_1-15-23.Rmd")'

(needs CRAN packages `knitr`, `aster`, and `numDeriv`).

This gives warnings about xcolor which seem unavoidable, a bug in Rmarkdown
that makes it incompatible with LaTeX package tikz-cd, which is used to
draw the aster graph.  These warnings are apparently harmless.

Copyright Waiver: CC0 http://creativecommons.org/publicdomain/zero/1.0/
