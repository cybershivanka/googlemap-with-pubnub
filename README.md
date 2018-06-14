# googlemap-with-pubnub
google map point tracking using public mesage services by free pubnub account
PUBNUB API KEY : signup for a PubNub account to get your API keys, obtain this from the url "https://admin.pubnub.com/#/register" after creating a free account. Then replace the existing with the received API KEY at "http://admin.pubnub.com/"
Google Maps API Setup: create an unique API key that can be locked down to whatever web apps you like. Once you’ve started to create a bunch of projects, you can manage your credentials in the Google API console at "https://console.cloud.google.com/apis/credentials?project=???"
Application Setup and Configuration : 
01)    <script src="https://cdn.pubnub.com/sdk/javascript/pubnub.4.19.0.min.js"></script>
02)    <script src="https://maps.googleapis.com/maps/api/js?v=3.exp&key=YOUR_MAPS_API_KEY&callback=initialize"></script>
03)    var pubnub = new PubNub({
          publishKey:   'YOUR_PUB_KEY',
          subscribeKey: 'YOUR_SUB_KEY'
       });
       
TUTORIALS:
Part 01  : https://www.pubnub.com/tutorials/javascript/mapping-javascript-tracking/
Part 02  : https://www.pubnub.com/tutorials/javascript/google-maps-api-map-markers/
Part 03  : https://www.pubnub.com/tutorials/javascript/google-maps-api-location-publishing/
Part 04  : https://www.pubnub.com/tutorials/javascript/google-maps-api-flight-paths/

