# MethylQTL
mQTL mapping in bisulfite sequencing studies by fitting a binomial mixed model, incorporating allelic-specific methylation pattern.

# Installation
It is easy to install the development version of MethylQTL package using the 'devtools' package.
```
library(devtools)
install_github("3211895/MethylQTL")
```
# Usage
The main function is methylqtl. You can find the instructions and an example by '?methylqtl'.

Example:

data(ExampleData)
res=methylqtl(geno,data,K)


