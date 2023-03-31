# land-prospector
Created in the hopes of finding an idealized land plot to purchase. 

# how it should work
gather data from different sources, included but not limited to
* point descriptors (it is `x` here) 
  * elevation
  * hydrology
  * rain
  * polution
  * biome
  * sun
  * global warming
  * flooding
  * weather patterns and averages
* region descriptors (it is `x` becuase it is contained within `y`) 
  * city laws
  * county laws
  * state laws
  * political qualities
* lot descriptors (subset of region descriptor) 
  * has house
  * has public road
  * has private road
  * is for sale
  * has grid electric
  * has grid water
  * has grid seqage
  * has grid internet
* landmark descriptors (it is `x` from `y` landmark)
  * goods
  * services
  * proximity to neighbors
  * proximity to public land
  * proximity to natural feature

ideally - just stick as much data as possible in there and let the humans forming the query sort it out from there with intuition. 
it should be easy to load new/custom sets of data in 
  
these descriptors are then queried and ultimatly grouped together with the help of a graph database to form a subset of lots that match the above characteristics for further human analysis

a query is formed from these descriptors and then each filtered - the result is then mapped to lots - using point-in-polygon and polygon-in-polygon algos - ideally this returns a list/map UI and links/integrates to a real-estate site such as zillow 
