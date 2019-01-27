---
title: "Assessment"
date: 27 January 2019
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

```{r}
library(leaflet)

my_map <- leaflet() %>%
        addTiles() %>%
        addMarkers(lat=52.933960, lng=-1.171930, popup="Should visit once here!")
my_map
```

