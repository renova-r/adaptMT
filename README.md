# adaptMT

Adaptive p-value thresholding (AdaPT) for multiple hypothesis testing with side information, with a generic framework and GLM, GAM and glmnet wrappers for learning the local false discovery rate.

Compatibility updates by Renova.

Version 1.0.0.9001 replaces `class(x) == "..."` comparisons in `if()` conditions with `inherits()` (or a first-class check), converts `inst/CITATION` from `citEntry()` to `bibentry()` with the same authors and reference, writes the arXiv reference in `Description` as a DOI, and fixes Rd markup that triggered lost-brace notes. No statistical procedure was otherwise changed.

## Install

Install this release from its GitHub tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/adaptMT@renova-1.0.0.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

adaptMT is by Lihua Lei (maintainer); the method is by Lihua Lei and William Fithian, and the original project is at <https://github.com/lihualei71/adaptMT>. License: MIT + file LICENSE; see [LICENSE](LICENSE) (Copyright 2018 Lihua Lei) and [LICENSE.md](LICENSE.md) (full MIT text).
