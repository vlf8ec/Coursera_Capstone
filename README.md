# Where in NYC should I open an ice cream shop?!?!
This project is for the IBM Data Science Capstone project and required us to come up with a business question that can be solved using Foursquare data.
## Business Problem
I have decided that when I retire I would love to open an ice cream shop in St Louis, MO area. Most importantly, I want to make sure that this shop is in a location without many other ice cream shops. But due to my love for parks and the outdoors I think an ice cream shop would be very successful neara park or trail. Other things to consider are a well populated neighborhood so that there are plenty of customers nearby. A lot of restaurants nearby would also increase traffic because it will be a great place to stop for dessert after.  
## Data
I will use Foursquare API as my data source for analyzing the data but will start with a list of neighborhoods from wikipedia.
#### Wikipedia
I will get the data for the list of neighborhoods and their populations from this wikipedia page, https://en.wikipedia.org/wiki/List_of_neighborhoods_of_St._Louis
#### Geospatial Data
Before we can make use of the Foursquare API we need to convert the neighbourhood names into a pair of latitude and longitude coordinates. We can acquire this with the Geocode Python library.
We can query the Foursquare API using the HTTP GET method on the explore endpoint indicating the geographical coordinates, venue categories and radius.
