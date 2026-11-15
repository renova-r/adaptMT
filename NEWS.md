# adaptMT 1.0.0.9001

Renova release, based on CRAN adaptMT 1.0.0 (archived on CRAN 2026-02-24).

- `R/adapt-plot-1d.R`, `R/fit-helpers.R`, `R/main.R`: `if()` conditions comparing `class()` to a string now use `inherits()` (or `class(x)[1]` for the numeric check), as required by current R.
- `inst/CITATION`: `citHeader()`/`citEntry()` replaced by an equivalent `bibentry()` call; authors (Lihua Lei and William Fithian), title, year and URL are unchanged.
- `DESCRIPTION`: the arXiv reference in `Description` is written as `<doi:10.48550/arXiv.1609.06035>` (metadata only).
- `man/adapt.Rd`, `man/corr_lfdr.Rd`, `man/ctgm_lfdr.Rd`, `man/plot_2d.Rd`: removed a redundant `\itemize` inside `\value` and escaped/marked literal braces (documentation only).
- `DESCRIPTION`: `Version` set to `1.0.0.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `LICENSE.md` (full MIT text) was added; the `License` field is unchanged.
- `README.md` was replaced by a short Renova README and `.Rbuildignore` keeps `README.md` and `LICENSE.md` out of the built package. The upstream `NEWS.md` is extended and stays in the package.

adaptMT 1.0.0 (07/21/2018)
---------------------------------------------------
Initial release
