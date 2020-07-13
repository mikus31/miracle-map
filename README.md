# The Miracle Map
Interactive mapping project for Gwen Clark via Upwork.
Michael McNeil | 2020-05-09
 
## About

Full-page, interactive web map displaying point locations of miracles around the world.

Similar in style to this map of terrorist attacks:

![miracle-map-mockup](https://github.com/mikus31/miracle-map/blob/master/images/mockup.jpeg "Miracle Map Mockup")

The client wants a full-page web map that looks less like an out-of-the-box template, however. This map will be more of a custom build, with some of the functional elements seen above.

### Mockup Notes

A few notes from the client provided with the mockup:

* I’d like the questionnaire to be a link where the person has to click something and that takes them to it. Once they fill it out, I will review it and then determine if it will go live or not.   
* Regarding the hover tool, I am thinking that as you hover around the map it would be nice to have the Miracle Name pop up. (Notice on the terrorism map what pops up is the location name). Miracle Name isn’t part of the questionnaire, but I’d like to be the one who labels it after I’ve reviewed the questionnaire. So as you hover around you’d see miracle names popping up “tumor removed”  “covid19 healed”, etc.
* From the mockup on the terrorism map where it is total number fatalities and attacks. I like this running tally idea, but how can we apply that to the healings? Total healings? Then another tally by condition or total healed within a region? These are just some thoughts…
* From the terrorism map it doesn’t seem like one of the filters is working - the location one. I was thinking for our location filter would it make sense to have the choices be by Region? Or something else…?
* In the top right corner of the terrorism map it says “about this map” … Do you think this is good?

## Requirements

A list of requirements for the delivery:

* Custom build (the map should not look like an out-of-the-box solution)
* Web map can function as the website
* Link on the map to external web page, where users can submit a miracle via a form
* Firefly-inspired style (firefly symbology, firefly base map)
* Drop-down menus for categorical data within the dataset:
  * By condition
  * By location
* Hover / popup functionality (name of the miracle as the focus)
* A time slider

### Ideas for the Future

* A running miracle counter?
* An "About" page?

## Admin Reports

The admin requested the ability to query the data for the following information:

* By condition
* By location (including region)
* By forgiveness
* By instant or gradual
  * If gradual, by healing timeframe
* By faith (own or the faith of another)
* By church affiliation
* By church denomination (break-down)
* By already a believer or not
* By length of time a believer
* By change in mindset
* By mindset type
* By population density (rate per 100k)
* By age

## Reference

esri-leaflet:

* https://github.com/Esri/esri-leaflet
* http://esri.github.io/esri-leaflet/examples/

Firefly inspired symbology:

* https://www.esri.com/about/newsroom/arcwatch/make-your-points-glow-with-firefly-symbols/
* https://www.esri.com/arcgis-blog/products/mapping/mapping/steal-this-firefly-style-please/
* https://esri-styles.maps.arcgis.com/home/item.html?id=93a6d9ea3b54478193ba566ab9d8b748