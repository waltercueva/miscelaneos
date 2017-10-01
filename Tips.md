# Instalacion de Paquetes de version determinada
## Forma 1
>require(devtools)

>install_version("DiagrammeR", version = "0.9.0", repos = "http://cran.us.r-project.org")

## Forma 2
packageurl <- "http://cran.r-project.org/src/contrib/Archive/ggplot2/ggplot2_0.9.1.tar.gz"
install.packages(packageurl, repos=NULL, type="source")

## Forma 3.- Con Rtools para windows
wget http://cran.r-project.org/src/contrib/Archive/ggplot2/ggplot2_0.9.1.tar.gz
R CMD INSTALL ggplot2_0.9.1.tar.gz



