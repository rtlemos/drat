# drat
This is a dummy (drat) package that lets you have access to all the packages in this repository. Here are the steps:
```r
install.packages('drat')
drat::addRepo(account = 'rtlemos', alturl = 'https://rtlemos.github.io/drat/')
```
Once this is done, you can install any package (and its dependencies) seamlessly, e.g.
```r
install.packages('rcvirtual')
```
To learn more about `drat`, read the [vignette](https://cran.rstudio.com/web/packages/drat/vignettes/DratForPackageUsers.html) and [FAQ](https://cran.rstudio.com/web/packages/drat/vignettes/DratFAQ.html).
