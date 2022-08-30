# geocoding_gkh
### Ready to use geocoding solution for data exported from reformagkh.ru


Exporting data from https://www.reformagkh.ru/ is probably the most __BASED__ step of pre-project analysis for urban planners in Russia.
It is by far the greatest source of data on apartment buildings located in any part of the country. Nevertheless, each and every time exporting it you have to think about geocoding to add a context of space to data by matching addresses and coordinates.


The solution is a jupyter notebook which tries its best to identify the location of a point by rewriting an address in the most proper way and passin it to... __Nominatum__ geocoder which knows _almoast_ nothing about limits (hurrah!) but uses only OpenStreetMap data (nah...) The number of requests is limited to around 2 per second meaning that a middle-sized city of Tver with population of 425k will be fully geocoded in 23,3 minutes. The quality was tested on this city with a result of 93% geocoded addresses.



_VBA comes soon..._
