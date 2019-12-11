

`cola` is an R package that provides a general framework for consensus partitioning. This website collects
HTML reports for the cola analysis applied on public datasets.

- [GDS](https://cola-gds.github.io/): analysis on xxx [GDS]() datasets,
- [recount2](https://cola-recount2.github.io/): analysis on xxx [recount2]() datasets,
- [Other datasets](https://jokergoo.github.io/cola_examples/): analysis on the seven datasets used in the cola manuscript.

`cola` is available on [Bioconductor](http://bioconductor.org/packages/devel/bioc/html/cola.html), you can install it by:

```r
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("cola")
```

If you want to try the latest version, install it directly from GitHub:

```r
library(devtools)
install_github("jokergoo/cola")
```
