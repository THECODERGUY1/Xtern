# Xtern
Xtern
Google places api was used to find the places of interest in the following types: ['amusement_park','art_gallery','bar','cafe','casino','church','city_hall','hindu_temple',
'library','museum','night_club','park','restaurant','shopping_mall','stadium','tourist_attraction','zoo']

The nearbysearch of the google places API was used with few select locations from Indiapolis and a radius of 10000 meters.
The Json from the API was then converted to csv and appended and data was cleaned. We now have a master data file with almost 1000 places of interest that a person can visit in Indinapolis with their types.

To prepare the iternaty from 9am to 9pm we can write a algorithm to take in the person's interest types and the rank the places and we can use google maps api to compute the time for one place to other and also information such as if the place will be open during the time or not. Due to lack of time the above operation has been done manually.
