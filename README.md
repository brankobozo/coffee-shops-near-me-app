# Caffeine rush
## List of coffee shops based on geolocation, using foursquare API

List of closest coffee shops around, within distance of 1km, nice and responsive

### Functionality

After user accepts to share his location he should see the listing that from Foursquare API. Listing should be nice looking and sorted by distance. If the user didn't allow usage of geolocation, he should see an error that it is necessary to allow it to use the app. If Coffe Shop is closed should be removed from the list.

The list should display up to 10 coffee shops with following data:
  * Place Name
  * Place Address
  * Distance

Click on list item open Coffee Shop details page. Page should be created with:
  * Place Name, Address, Contact information (or more info)
  * Place image(s)
  * Tips for the place
  
### Technical Stack
  - Needs to be **responsive** and work in newer versions of **Chrome** and **Firefox**
  - **CSS3** transitions and effects would be nice
  - Usage of **geolocation API**, to detect user location
  - **Vanilla JavaScript prefered** but not required
  - If there is an error user sshould know about it nicely
  - Usage of **build tools**
    - Webpack, Babel, EsLint with Airbnb style, Sass
  
 ### Bonus 
  - Display Coffee Shops on map (Google, OSM...)
