# Ex04 Places Around Me
AIM
To develop a website to display details about the places around my house.

DESIGN STEPS
STEP 1
Create a Django admin interface.

STEP 2
Download your city map from Google.

STEP 3
Using <map> tag name the map.

STEP 4
Create clickable regions in the image using <area> tag.

STEP 5
Write HTML programs for all the regions identified.

STEP 6
Execute the programs and publish them.

CODE
AGS.html
```
      <!DOCTYPE html>
      <html>
      <head>
          <meta charset="UTF-8">
          <title>AGS Cinemas</title>
      </head>
      <body style="background-color: rgb(189, 101, 219);">
          <h1><Center>Welcome to AGS Cinemas<Center></h1>
          
          <h2>Now Showing Movies</h2>
          <ul>
              <li>Kandukondain Kandukondain</li>
              <li>Nanban</li>
              <li>Dear Zindagi</li>
          </ul>
          
          <h2>Showtimes</h2>
          <p>Kandukondain Kandukondain : 11:00 AM, 4:30 PM, 8:00 PM</p>
          <p>Nanban : 12:00 PM, 2:45 PM, 9:15 PM</p>
          <p>Dear Zindagi: 12:30 PM, 4:00 PM, 9:30 PM</p>
          
          <h2>Facilities</h2>
          <ul>
              <li>Comfortable seating</li>
              <li>State-of-the-art audio and visual technology</li>
              <li>Concession stand with snacks and drinks</li>
          </ul>
      </body>
      </html>
```
Vadapalani.html
```
            <!DOCTYPE html>
            <html>
            <head>
                <meta charset="UTF-8">
                <title>Alurumigu Murugan Vadapalani Temple</title>
            </head>
            <body style="background-color: rgb(219, 215, 101);"></body>
                <h1>Welcome to Alurumugi Murugan Vadapalani Temple</h1>
                <h2>Upcoming Events</h2>
                <ul>
                    <li>Thaipusam Festival</li>
                    <li>Panguni Uthiram Celebration</li>
                    <li>Monthly Bhajans</li>
                </ul>
                
                <h2>Temple Timings</h2>
                <p>Weekdays: 6:00 AM - 12:00 PM, 3:00 PM - 9:00 PM</p>
                <p>Weekends: 6:00 AM - 9:30 PM</p>
                <p>Please check the calendar for special event timings.</p>
                
            </body>
            </html>
```            
Decathlon.html
```
  <!DOCTYPE html>
  <html>
  <head>
      <meta charset="UTF-8">
      <title>Decathlon Sports Store</title>
  </head>
  <body style="background-color: rgb(101, 156, 219);"></body>
      <h1><Center>Welcome to Decathlon Sports Store</Center></h1>
      <h2>Featured Products</h2>
      <ul>
          <li>Running Shoes</li>
          <li>Cycling Gear</li>
          <li>Tennis Rackets</li>
      </ul>
      
      <h2>Store Hours</h2>
      <p>Monday - Friday: 9:00 AM - 8:00 PM</p>
      <p>Saturday: 10:00 AM - 6:00 PM</p>
      <p>Sunday: Closed</p>
      
  </body>
  </html>
```
Rohini.html
```
  <!DOCTYPE html>
  <html>
  <head>
      <meta charset="UTF-8">
      <title>Rohini Silver Screen Theater</title>
  </head>
  <body style="background-color: rgb(132, 219, 101);"></body>
      <h1><Center>Welcome to Rohini Silver Screen Theater</Center></h1>
      <h2>Now Showing Movies</h2>
      <ul>
          <li>Leo</li>
          <li>Alai Payuthey</li>
          <li>Spider-Man</li>
      </ul>
      
      <h2>Showtimes</h2>
      <p>Leo Showtimes: 10:00 AM, 2:30 PM, 7:00 PM</p>
      <p>Alai Payuthey Showtimes: 11:00 AM, 3:45 PM, 8:15 PM</p>
      <p>Spider-Man Showtimes: 12:30 PM, 4:00 PM, 9:30 PM</p>
      
  </body>
  </html>
  ```
Main.html
```
  <!DOCTYPE html>
  <html>
  <head>
      <title>Mapping an Image</title>
  </head>
  <body>
      <h1><Center> EXNO:4 IMAGE MAP</Center></h1>
  <h1><Center>Danush S -212221040033</Center></h1>
  
  <img src="map3.png" usemap="#nearme">
  
  <map name="nearme">
      <area  title="Deco" href="http://127.0.0.1:8000/static/deco.html" coords="17,12,663,311" shape="rect">
      <area  title="Rohini" href="http://127.0.0.1:8000/static/rohini.html" coords="678,11,1409,319" shape="rect">
      <area  title="AGS" href="http://127.0.0.1:8000/static/ags.html" coords="16,332,663,597" shape="rect">
      <area  title="Vadapalani temple" href="http://127.0.0.1:8000/static/vadapalani.html" coords="688,356,1558,829" shape="rect">
      </map>
  </body>
  </html>
```
# OUTPUT
image image image image image

# RESULT
The program for implementing image maps using HTML is executed successfully.
