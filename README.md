# RTCGA.PANCAN12

A part of [RTCGA](https://github.com/RTCGA) family.

To install development version from GitHub use

````{R}
if (!require(devtools)) {
    install.packages("devtools")
    require(devtools)
}
install_github("RTCGA/RTCGA.PANCAN12", build.vignettes = TRUE)
````

Make sure you have [Rtools](https://cran.r-project.org/bin/windows/Rtools/) installed on your computer, if you are trying `devtools` on Windows.

To install Bioconductor development version use (the same as GitHub development version) - `still in the review`

````{R}
BiocInstaller::useDevel() # swiches to devel branchof Bioconductor
source("https://bioconductor.org/biocLite.R") # downloads bioClite function
biocLite("RTCGA.PANCAN12") # installs a package
````
