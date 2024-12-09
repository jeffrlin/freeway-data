# Freeway data

This repo contains spatial data on freeway building in U.S. cities since the mid-1950s. 

If you find these data useful, please cite "Freeway Revolts! The Quality of Life Effects of Highways," by Jeffrey Brinkman and Jeffrey Lin. Link to paper: <https://jlin.org/papers/BL-FR.pdf>

# What's available

## 1947 Intercity Plan
	
We digitized the 1947 Interstate plan for this project. The Federal-Aid Highway Act of 1944 had called for the designation of a National System of Interstate Highways, to include up to 40,000 miles. This is the map used in Baum-Snow (2007) as an instrument for completed Interstates. States were asked to submit proposals for their portion of the Interstate highway system. They then negotiated with the Bureau of Public Roads and the Department of Defense over routing and mileage. In 1947, the BPR announced the selection of the first 37,000 miles. Baum-Snow’s coding of these planned Interstate routes was precise only to metropolitan-level variation, so was unsuitable for our analysis. Instead, we digitized the 1947 plan map to within-metropolitan area precision.

Because the 1947 plan map was drawn at a national scale, there is little detail inside metropolitan areas. In fact, metropolitan areas are represented as open circles. This is a virtue for our instrumental variables analysis, since information about neighborhood factors did not enter into the routing of the 1947 plan map highways. (The 1947 highway plan makes no mention of trans- portation within cities or future development.) On the other hand, the size of the open circles and the poor resolution of the 1947 plan map mean that in practice it is challenging to precisely assign the routes of plan highways according to the 1947 map. To the extent possible, we use the center of the drawn lines of the 1947 map. When drawn lines terminate at open circles, we extend these lines to principal city centers from Fee and Hartley (2013). We do this to ensure relevant variation in proximity to plan routes—without these extensions, all 1947 plan routes would terminate at the edge of the metropolitan area. In addition, Interstate design principles enshrined later (e.g., AASHO, 1957) codified the radial structure of U.S. city highway networks seen today, where multiple rays converge to locations just outside of central business districts.
