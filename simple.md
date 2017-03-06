# Simple knitr Markdown example 	# Note: 1 

Two examples:

* plotting
* calculating

Plot example:
```{r plotexample, fig.width=2, fig.height=2, fig.align='center'} 	# Note: 2 
library(ggplot2) 	# Note: 3 
ggplot(data=data.frame(x=c(1:100),y=sin(0.1*c(1:100)))) +
   geom_line(aes(x=x,y=y))
``` 	# Note: 4 

Calculation example: 	# Note: 5 
```{r calcexample} 	# Note: 6 
pi*pi
```
