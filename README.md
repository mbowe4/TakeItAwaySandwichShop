## Take It Away Sandwich Shop Mobile Ordering Application
### Phase I: Menu & Order Functionality 
* Create Spring Boot application back-end to allow for mobile ordering
* Set up database to store menu items using AWS
* Add functionality to allow customer to browse and interact with menu and view prices/options

### Phase II: Maintenance Application
* Create separate platform for business owner to maintain database with price / menu additions and alterations

### Phase III: Fax Ordering
* Add fax ordering capability so customers can order on the go
* Orders will print to business fax line
* Utilize Java libraries to facilitate email reception of faxes

### Phase IV: Scheduled Pick-Up
* Allow customer to specify a pick-up time
* Submit order through via fax

### Phase V: Mobile Payments
* Allow customer to pay for their order through the application
* Utlize Square library for payment authorization

### Phase VI: Geofencing
* Allow customer to place order and have notification sent to business to begin prepation once they enter a pre-defined distance away
* Tools: Google's Geofencing API
  * https://developers.google.com/location-context/geofencing/
