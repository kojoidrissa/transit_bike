Can I combine bus and bike routes?
===================================

This is a repo for my idea that started at the Open Houston Hackathon. Google Maps will let you choose transit directions via public transit or bike, but I want to combine them.

Notes/Links
------------
-  `Houston Metro Developer Portal <https://developer-portal.ridemetro.org/>`_

    +  I'm not sure if I'm going to use this or not. I maybe able to get everything in one place from the Google Maps Directions API.

If I'm going to use Google maps, I'll need an API key and the following info:
-  `Google Maps API pricing and plans <https://developers.google.com/maps/pricing-and-plans/>`_
-  `Google Maps Directions API <https://developers.google.com/maps/documentation/directions/>`_

    +  The link to get an API key is on that page.

    +  I'll want to combine the two `travel modes <https://developers.google.com/maps/documentation/directions/intro#TravelModes>`_: bicycling and transit.
-  `Python Client for Google Maps Services <https://github.com/googlemaps/google-maps-services-python/>`_


Ideal Bike Map: From Open Houston
---------------------------------
Using the [Strava bike heatmap](http://labs.strava.com/heatmap/#12/-95.43815/29.76784/blue/bike) and existing bike lane maps, determine the ideal bike communiting patterns and recommend street changes to the City. Would be good to get [PWE](http://www.publicworks.houstontx.gov/home) on board & releasing datasets

I also wonder if I could combine the above data with bus data or Google Maps Transit data to create transit directions that COMBINE bike and bus routes?