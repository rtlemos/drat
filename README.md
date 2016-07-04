# drat
This is a dummy (drat) package that lets you have access to all the packages in this repository. Here are the steps:
```r
# installing the real drat package from CRAN
install.packages('drat')
# adding my repo to your list of repos (not permanently, just for your current R session)
drat::addRepo(account = 'rtlemos', alturl = 'https://rtlemos.github.io/drat/')
```
Once this is done, you can install any package (and its dependencies) seamlessly, e.g.
```r
install.packages('rcvirtual')
```
To learn more about Dirk Eddelbuettel's `drat`, read the [vignette](https://cran.rstudio.com/web/packages/drat/vignettes/DratForPackageUsers.html) and [FAQ](https://cran.rstudio.com/web/packages/drat/vignettes/DratFAQ.html).
