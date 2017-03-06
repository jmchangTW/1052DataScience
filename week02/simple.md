# Simple knitr Markdown example

Two examples:

* plotting
* calculating

Plot example:

```r
library(ggplot2) 
```

```
## Warning: package 'ggplot2' was built under R version 3.2.5
```

```r
ggplot(data=data.frame(x=c(1:100),y=sin(0.1*c(1:100)))) +
   geom_line(aes(x=x,y=y))
```

<img src="figure/plotexample-1.png" title="plot of chunk plotexample" alt="plot of chunk plotexample" style="display: block; margin: auto;" />

Calculation example: 

```r
pi*pi
```

```
## [1] 9.869604
```
