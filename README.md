# Weather-App
Here is a weather app I made!  The app uses API referencing, JSON parsing, cocoapods, data modeling, locationManager and location services, and advanced delegation.  Uses the openWeatherMap website for data. 

The app first asks for permission to access the users location, then uses API referencing and JSON parcing to use the location data to find the weather.  Making the view controller the delegate, the app then displays the weather on the screen.  If you click the arrow button you are then brought to another view controller that enables the user to search the weather of whatever city they want.  This also uses the API reference and JSON parcing to search as well.  

The code makes sure not to use too much of the users data by stopping the weather data collection once it recieves an accurate enough reading.  

![screen shot 2018-10-17 at 19 36 05](https://user-images.githubusercontent.com/43976402/47081286-27605080-d245-11e8-961e-4e804eac04e8.png)

![screen shot 2018-10-17 at 19 36 24](https://user-images.githubusercontent.com/43976402/47081343-49f26980-d245-11e8-9ed8-61292079aa7d.png)


