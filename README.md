# readgdf

[![Build Status](https://travis-ci.org/mikaelpoul/readgdf.svg?branch=master)](https://travis-ci.org/mikaelpoul/readgdf)

Extract network data from gdf files and import it into R.

Install the package using devtools (use `install.packages("devtools")` if you don't have it installed):

``` R
devtools::install_github("mikaelpoul/readgdf", dependencies = TRUE)
```

Then simply load the package and read your gdf file with `read_gdf`:

``` R
library(readgdf)
data <- read_gdf("path/to/gdf_file.gdf")
```

It will return an igraph graph object by default, but you can set `as_igraph = FALSE` to make it return a list with the node and edge data, respectively. it is `verbose = TRUE` by default.



