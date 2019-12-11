

`cola` is an R package that provides a general framework for consensus partitioning. This website collects
HTML reports for the cola analysis applied on public datasets.

- [on 206 GDS datasets](https://cola-gds.github.io/)
- [on 223 recount2 datasets](https://cola-recount2.github.io/)
- [On the seven datasets used in the cola manuscript](https://jokergoo.github.io/cola_examples/)

`cola` is available on [Bioconductor](http://bioconductor.org/packages/devel/bioc/html/cola.html), you can install it by:

```r
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("cola")
```

The latest version can be directly installed from [GitHub](https://github.com/jokergoo/cola):

```r
library(devtools)
install_github("jokergoo/cola")
```
