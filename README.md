# olympics-synthetic-control
In this repository, we use the Synthetic Control Method to study the causal effect that hosting the Olympic games has on the country's economy

## Note on how to run the code
Upon the Synth package archived on Apr 14, 2023, we need to use the following codes to install Synth.
```r
devtools::install_github('cran/LowRankQP')
devtools::install_github('cran/Synth')
library(Synth)
```

instead of the following. 
```r
instsall.packages('Synth')
library(Synth)
```