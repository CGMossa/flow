
<!-- README.md is generated from README.Rmd. Please edit that file -->
flow
====

Visualize as flow diagrams the logic of functions, expressions or scripts and ease debugging.

-   Call `flow_view()` on a function, a quoted expression, or the path of an R script to visualize it.

-   Call `flow_run()` on a call to a function to visualize which logical path in the code was taken. Set `browse = TRUE` to debug your function block by block (similar to `base::browser()`) as the diagram updates.

-   Export to *html*, *png*, *jpeg*, or *pdf*.

-   Use the Rstudio addins to run `flow_view()` or `flow_run()` on your selection.

Installation
------------

Install with:

``` r
devtools::install_github("moodymudskipper/flow")
```

Example
-------

``` r
library(flow)
flow_view(median.default)
```

<img src="man/figures/README-unnamed-chunk-3-1.png" width="100%" />