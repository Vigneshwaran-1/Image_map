# Ex04 Places Around Me
# Date:28/04/2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
map.html
~~~~
<html>
<head>
  <title>My City</title>
</head>
<body>
  <h1 align="center">
    <font color="red"><b>my village</b></font>
  </h1>

  <h3 align="center">
    <font color="blue"><b>VIGNESHWARAN.P(24900068)</b></font>
  </h3>
<center>
    <img src="map -4.png" usemap="#MyCity" height="610" width="1450">
    <map name="MyCity">
      <area shape="rect" coords="700,250,850,400" href="map.html" title="Hanumantheertham">
      <area shape="circle" coords="570,230,45" href="river.html" title="Thenpennaiyar river">
      <area shape="circle" coords="640,200,30" href="petrol bank.html" title="Bharat petroleum">
      <area shape="circle" coords="1120,360,25" href="temple.html" title="hanuman temple">
      <area shape="rect" coords="950,120,1100,140" href="wedding hall.html" title="balusamy thirumana mahal">
    </map>
  </center>
</body>
</html>
~~~~
temple.html
~~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hanumantheertham Temple</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(120deg, #f57c00, #ffcc80);
            font-family: Arial, sans-serif;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .container {
            max-width: 600px;
            background: rgba(0, 0, 0, 0.6);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.4);
        }
        h1 {
            font-size: 28px;
            margin-bottom: 15px;
        }
        p {
            font-size: 18px;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hanumantheertham Temple</h1>
        <p>The Hanumantheertham Temple, located on the banks of the Thenpennai River, is a sacred site dedicated to Lord Hanuman. It is believed that Lord Hanuman himself performed penance here, making this temple highly revered among devotees.</p>
        <p>The temple’s architecture reflects traditional South Indian styles, featuring beautifully carved sculptures and a serene atmosphere. Pilgrims visit to seek blessings, witness ancient rituals, and experience the spiritual energy that surrounds Hanumantheertham.</p>
        <p>The temple becomes especially vibrant during religious festivals, attracting visitors from far and wide. The scenic beauty of the river beside the temple enhances the divine experience, making it a must-visit location for devotees and travelers alike.</p>
    </div>
</body>
</html>
~~~~
river.html
~~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thenpennai River - Hanumantheertham</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(120deg, #4a90e2, #56b4d3);
            font-family: Arial, sans-serif;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .container {
            max-width: 600px;
            background: rgba(0, 0, 0, 0.6);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.4);
        }
        h1 {
            font-size: 28px;
            margin-bottom: 15px;
        }
        p {
            font-size: 18px;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Thenpennai River - Hanumantheertham</h1>
        <p>The Thenpennai River, also known as South Pennar, is an important river flowing through Tamil Nadu. At Hanumantheertham, this river is known for its serene beauty and religious significance. The area is believed to be associated with Lord Hanuman, making it a sacred pilgrimage site.</p>
        <p>The river nourishes nearby agricultural lands and supports local biodiversity. Its calm waters and picturesque surroundings make Hanumantheertham an ideal spot for devotion and relaxation.</p>
    </div>
</body>
</html>
~~~~
wedding hall
~~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wedding Hall in Hanumantheertham</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(120deg, #ff6f61, #ffcc80);
            font-family: Arial, sans-serif;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .container {
            max-width: 600px;
            background: rgba(0, 0, 0, 0.6);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.4);
        }
        h1 {
            font-size: 28px;
            margin-bottom: 15px;
        }
        p {
            font-size: 18px;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Wedding Hall in Hanumantheertham</h1>
        <p>The wedding hall in Hanumantheertham is a grand venue designed to host traditional weddings and ceremonies. Its spacious interiors, elegant décor, and modern amenities make it a preferred choice for celebrations.</p>
        <p>Surrounded by serene landscapes and cultural richness, this wedding hall provides the perfect setting for sacred unions. Guests enjoy a warm and festive atmosphere, making every event memorable.</p>
        <p>Equipped with catering, seating arrangements, and stage facilities, the venue ensures seamless wedding experiences that blend heritage with modern comforts.</p>
    </div>
</body>
</html>
~~~~
petrol bank.html
~~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Petrol Bank in Hanumantheertham</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(120deg, #0073e6, #009688);
            font-family: Arial, sans-serif;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .container {
            max-width: 600px;
            background: rgba(0, 0, 0, 0.6);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.4);
        }
        h1 {
            font-size: 28px;
            margin-bottom: 15px;
        }
        p {
            font-size: 18px;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Petrol Bank in Hanumantheertham</h1>
        <p>The petrol bank in Hanumantheertham serves as an important fuel station for commuters, pilgrims, and residents in the region. Conveniently located, it ensures a steady supply of fuel for vehicles passing through the area.</p>
        <p>With easy access, clean surroundings, and efficient service, the petrol bank plays a crucial role in supporting transportation needs in Hanumantheertham. Many travelers stop here for refueling before continuing their journey towards nearby religious and tourist destinations.</p>
        <p>Maintaining quality fuel and service, the petrol bank is an essential facility that contributes to local mobility and convenience.</p>
    </div>
</body>
</html>
~~~~
# OUTPUT
![alt text](<vignesh/vignesh/static/map -4.png>)
![alt text](petrol.png)
![alt text](river.png)
![alt text](temple.png)
![alt text](<wed hall.png>)
# RESULT
The program for implementing image maps using HTML is executed successfully.
