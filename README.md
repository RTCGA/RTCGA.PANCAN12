[![Build Status](http://bioconductor.org/shields/build/devel/data-experiment/RTCGA.PANCAN12.svg)](http://bioconductor.org/checkResults/devel/data-experiment-LATEST/RTCGA.PANCAN12/)
# [RTCGA.PANCAN12](http://bioconductor.org/packages/RTCGA.PANCAN12/)
A part of [RTCGA](https://github.com/RTCGA) family.

To install development version from GitHub use

````{R}
library(RTCGA)
installTCGA('RTCGA.PANCAN12')
````

Make sure you have [Rtools](https://cran.r-project.org/bin/windows/Rtools/) installed on your computer, if you are trying `devtools` on Windows.

To install Bioconductor development version use (the same as GitHub development version) - `still in the review`

````{R}
BiocInstaller::useDevel() # swiches to devel branchof Bioconductor, 
# skip BiocInstaller::useDevel() if you want release version
source("https://bioconductor.org/biocLite.R") # downloads bioClite function
biocLite("RTCGA.PANCAN12") # installs a package
````

