# bootpenal
R package: Bootstrap Penalization for variable selection with big data

# bootpenal

This is the R package `bootpenal' (Bootstrap penalization for variable selection with big data) written and maintained by Kuangnan Fang (xmufkn@xmu.edu) and Shuangge Ma(shuange.ma@yale.edu)


# Installation

You can install the stable version on CRAN:

install.packages('bootpenal', dependencies = TRUE)

Or download the zip ball or tar ball, decompress and run  R CMD INSTALL  on it.

Alternatively, you can install the development version but before doing so Windows users have to first install Rtools, while OS X users have to first install Xcode and the command line tools (in OS X 10.9 or higher, once you have Xcode installed, open a terminal and run xcode-select --install). Note also that versions of e.g. Rtools are paired with versions of R so ensure you have the latest version of R installed prior to commencing this process.

After installing Rtools/Xcode and devtools (via install.packages("devtools")), install the development package using the following command:

library(devtools); install_github('ruiqwy/R-Package-bootpenal')

Note also that if you wish a fast install without the building of vignettes (or if you do not have TeX installed on your system), add the option build_vignettes=FALSE to the install_github() call.

