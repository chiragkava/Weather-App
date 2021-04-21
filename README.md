
# Weather-App
Weather-App that displays realtime weather as well as forecast for a week.
<br>:link: https://chiragkava.github.io/Weather-App/

API / Framework used:
* OpenWeather API
  * Used To fetch data in JSON format from the server.  
* Charts.js
  * Used to display the temperature in form of graphical interface
* Leaflet Map
  * Used to show properties like temperature gradient , precipitation , cloudiness in embedded map 
* Bootstrap
  * Used for styling components and to make App responsive in all devices and screens 

## Screenshots
<table>
  <tr>
    <td>Small Devices</td>
    <td>Medium Devices</td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/61086004/115542978-7ed05300-a2be-11eb-9a7b-1c0350440a07.PNG" width=300 height=500></td>
    <td><img src="https://user-images.githubusercontent.com/61086004/115543886-86dcc280-a2bf-11eb-86bb-227b8973845f.PNG" width=600 height=500></td>
  </tr>
 </table>
 
<table>
  <tr>
    <td>Large screen Devices</td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/61086004/115544263-feaaed00-a2bf-11eb-8307-edb26113dd3c.PNG" height=500 width=928></td>
  </tr>
</table>


Example of API response in JSON format
                          

```js
{
  "coord": {
    "lon": -122.08,
    "lat": 37.39
  },
  "weather": [
    {
      "id": 800,
      "main": "Clear",
      "description": "clear sky",
      "icon": "01d"
    }
  ],
  "base": "stations",
  "main": {
    "temp": 282.55,
    "temp_min": 280.37,
    "temp_max": 284.26,
    "pressure": 1023,
    "humidity": 100
  },
  "visibility": 16093,
  "wind": {
    "speed": 1.5,
    "deg": 350
  },
  "clouds": {
    "all": 1
  },
  "dt": 1560350645,
  "sys": {
    "type": 1,
    "id": 5122,
    "country": "US",
  },
  "timezone": -25200,
  "id": 420006353,
  "name": "Mountain View",
  "cod": 200
}
  ```
### From above response properties like
```js
  wind speed
  humidity
  date & time
  icon
 ```
 ### can be extracted
                        
