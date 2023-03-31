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
  * polygon
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
  * polygon
  * goods
  * services
  * proximity to neighbors
  * proximity to public land
  * proximity to natural feature

  
 these descriptors are then queried and ultimatly grouped together with the help of a graph database to form a subset of lots that match the above characteristics for further human analysis
