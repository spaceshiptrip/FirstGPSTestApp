# FirstGPSTestApp
Testing out the GPS capabilities in Swift apps

Create a text button and on press, display the current GPS Lat Lon.

Things that I've learned:

* Need to set the privacy descriptions in Info.plist for:
  * Privacy - Location When In Use Usage Description
  * Privacy - Location Always and When In Use Usage Description
* Default App template in XCode 12x are structs
  * Is this the norm?  Previous codes utilize classes and MVC type architecture
* In order to deploy, need to set up a Team
  * Still reading up on what that means
  
  
Todo:
* Figure out how to make it a watch app
* Figure out how to have it update in the background


References:
* The class LocationManager comes from this GitHub repo:
https://github.com/JohnYezub/Location-Manager-Example
  * I used it to format the place and the LatLon to a readable string
  * Also used it to help initialize through the LocationManager wrapper
