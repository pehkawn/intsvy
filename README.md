intsvy
======
Branched from eldafani/intsvy.
So far the only difference is that that the import functions now use `haven::read_spss()` instead of `foreign::read.spss()`
<h5> Downloading intsvy package: </h5>

```{R}
if (!require(devtools)) {
    install.packages("devtools")
    require(devtools)
}
install_github("pehkawn/intsvy")
```

Make sure you have [rtools](https://cran.r-project.org/bin/windows/Rtools/) installed on your computer.

<h5> The list of available functions: </h5>

```{Ruby}
help(package="intsvy")
```
