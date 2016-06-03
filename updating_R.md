## Updating R version and packages
* R package for updating r-version within R
  * https://andreacirilloblog.wordpress.com/2015/10/22/updater-package-update-r-version-with-a-function-on-mac-osx/
  * had an issue with using curl in system(command) used R native curl instead
* Blog post on updating packages with new R version
  * http://stackoverflow.com/questions/13656699/update-r-using-rstudio
  * used `rsync -ru * ../../../3.3/Resources/library/` to copy packages
