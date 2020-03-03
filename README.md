Peer-graded Assignment: R Markdown and Leaflet
Francesco Canuto
May 25, 2018
Scope of the assignment
Create a web page using R Markdown that features a map created with Leaflet.

Host your webpage on either GitHub Pages, RPubs, or NeoCities.

Your webpage must contain the date that you created the document, and it must contain a map created with Leaflet. We would love to see you show off your creativity!

library(leaflet)

my_map <- leaflet() %>%
  addTiles() %>%  
  addMarkers(lng=7.68465, lat=45.0432, popup="Salsa Rossa - Really good pizza in Turin")
my_map 
