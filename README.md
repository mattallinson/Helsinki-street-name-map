# Road Names in Helsinki
This colours the streets of Helsinki based on the ending of the street name.

![the map](/images/Greater_Helsinki_with_scale.png)

## Future Work
My eventual goal is to make a coloured map of downtown Helsinki based on if streets named after people are named after a Finnish speaking person, a Swedish speaking person, or a Russian speaking person – but that will be hard and maybe will require getting to grips with Finnish natural language processing (lol) so this was my starting point to teach myself osmnx.

### Things to fix on the current map
* Some of the roads have weird gaps at the boundaries between the three cities. These gaps are more likely on motorways and bridges. I can't work out a way to get open streetmap to return one result for the whole helsinki metropolitan area, so I've got it stitching together the results for Espoo, Helsinki and Vantaa separately, this is probably the cause, needs more experimenting. 
* Better colour options?

## Giants' Shoulders

This work was inspired by [Giuseppe Sollazzo](https://twitter.com/puntofisso/status/1213135545121099777), who in turn was inspired by previous work by Erin Davis and Cedric Scherer.

### References
* [The beautiful hidden logic of cities](https://erdavis.com/2019/07/27/the-beautiful-hidden-logic-of-cities/)
* [#Berlin road network by name/suffix forming colorful networks](https://twitter.com/CedScherer/status/1195420409434382336)
* [Erin's code](https://github.com/erdavis1/RoadColors)
* [Cedric's code](https://github.com/Z3tt/30DayMapChallenge)
* [Giuseppe's code](https://github.com/puntofisso/OSMnxNotebooks/blob/master/Street%20colouring.ipynb)

