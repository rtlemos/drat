# drat
If you want to have access to all the packages in this repository (rtlemos), here are the steps:
```r
# install the real drat package from CRAN
install.packages('drat')
# add my repo to your list of repos (for your current R session only), thanks to my drat package
drat::addRepo(account = 'rtlemos', alturl = 'https://rtlemos.github.io/drat/')
# installing a package (and its dependencies) from the repo
install.packages('rcvirtual')
```
My local version of `drat` is just a dummy package that lets you do the above seamlessly. 
You don't need to download it or use it explicitly.
To learn more about the real `drat` package, by Dirk Eddelbuettel, read the [vignette](https://cran.rstudio.com/web/packages/drat/vignettes/DratForPackageUsers.html) and [FAQ](https://cran.rstudio.com/web/packages/drat/vignettes/DratFAQ.html).
