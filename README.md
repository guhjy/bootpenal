# bootpenal
R package: Bootstrap Penalization for variable selection with big data

# bootpenal

This is the R package `bootpenal' (Bootstrap penalization for variable selection with big data) written and maintained by Kuangnan Fang (xmufkn@xmu.edu) and Shuangge Ma(shuange.ma@yale.edu)


# Installation

You can install the stable version on CRAN:

install.packages('bootpenal', dependencies = TRUE)

Or download the zip ball or tar ball, decompress and run  R CMD INSTALL  on it.

You can also install the development version from Github, but before doing so, Windows users have to first install Rtools, while OS X users have to first install Xcode and the command line tools (in OS X 10.9 or higher, once you have Xcode installed, open a terminal and run xcode-select --install). Note also that versions of e.g. Rtools are paired with versions of R so ensure you have the latest version of R installed prior to commencing this process.

After installing Rtools/Xcode and devtools (via install.packages("devtools")), install the development package using the following command:

library(devtools)
install_github('ruiqwy/R-Package-bootpenal')


#License

This package is free and open source software, licensed under GPL (>= 2).

