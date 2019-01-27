# R Markdown and Leaflet
## 27 January 2019

library(leaflet)

my_map <- leaflet() %>%
        addTiles() %>%
        addMarkers(lat=52.933960, lng=-1.171930, popup="Should visit once here!")
my_map
