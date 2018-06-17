## Introduction

This file contains all the code and data to regenerate the key results
from (Eglen et al. 2005).  Code is in a mix of R and C.


## Running locally

You will need a copy of [R](http://www.r-project.org).  Download all
the files in this folder.  Then start R and type:

```
source('install.R')  ## need do this once only.
```

to install all the R packages necessary.  Once this completes, you can
then run the analysis using:

```
rmarkdown::render('rgc-mosaics.Rmd')
```

Then open the resulting file `rgc-mosaics.html`.  This html file
should contain (at the end) the 99 PIPP simulations for each mosaic
(M623 and W81S1).  There will also be PDF files for these results.

## Running in the cloud

If binder is working, you can click the following link (you may need
to wait a few minutes):
<http://beta.mybinder.org/v2/gh/sje30/rgc-mosaics/master?urlpath=rstudio>

You should eventually see Rstudio.  Open the file `rgc-mosaics.Rmd`
and hit the "knit" button to get the HTML file containing the key results.

Following examples from <https://github.com/binder-examples/r>



## References

Eglen SJ, Diggle PJ, Troy JB (2005) Homotypic constraints dominate
positioning of on- and off-center beta retinal ganglion cells. Vis
Neurosci 22:859–871 Available at:
<https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1513157/>

