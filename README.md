bluehill.github.io
==================

Fynbos endemic bird presentation

In this presentation I introduce the Fynbos, show some pictures of the birds that are only found
in the Fynbos (the six endemics), and I plot a chart in R based on summary statistics from group
encounter information from a survey conducted in 2012. I hide the code in order to adequately display 
the plot, but this is it:  

```{r, echo=FALSE}
endemic <- 2.6; other_birds <- 7.9; temp <- cbind(endemic, other_birds)
barplot(temp, ylab="groups per count", main="relative abundance of endemics and other birds in the Fynbos biome")

In the final slide I provide a link to the shiny app, as well as a link to blog that contains mostly stories about life in the Fynbos, and the tail of the survey in 2012 archives. 

I hope you enjoy it. 