First_rmarkdown
================
Ferdi
2025-03-05

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](first_file_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.

``` r
x <- c(10:1)*1/c(1:10)
x
```

    ##  [1] 10.0000000  4.5000000  2.6666667  1.7500000  1.2000000  0.8333333
    ##  [7]  0.5714286  0.3750000  0.2222222  0.1000000

``` r
plot(c(1:10), x)
```

![](first_file_files/figure-gfm/unnamed-chunk-1-1.png)<!-- -->
