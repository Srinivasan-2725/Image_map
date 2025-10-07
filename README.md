# Ex04 Places Around Me
1. # Date:07.10.2025
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
```
sri.html

<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="magenta"><b>TIRUNELVELI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>SRINIVASAN.P(25017988)</b></font>
</h3>
<center>
<map name="MyCity">
<img src="Screenshot 2025-10-07 214509.png" usemap="#image-map">

<map name="image-map">
    <area target="_self" alt="temple" title="temple" href="C:\Users\acer\Desktop\experiment4.web\Image_map\srini\imageapp\static\temple.html" coords="903,139,1086,277" shape="rect">
    <area target="_self" alt="mahal" title="mahal" href="C:\Users\acer\Desktop\experiment4.web\Image_map\srini\imageapp\static\mahal.html" coords="1112,290,1286,338" shape="rect">
    <area target="_self" alt="my town" title="my town" href="C:\Users\acer\Desktop\experiment4.web\Image_map\srini\imageapp\static\mytown.html" coords="5,360,195,526" shape="rect">
    <area target="_self" alt="theatre" title="theatre" href="C:\Users\acer\Desktop\experiment4.web\Image_map\srini\imageapp\static\theatre.html" coords="439,460,608,522" shape="rect">
    <area target="_self" alt="swimming pool" title="swimming pool" href="C:\Users\acer\Desktop\experiment4.web\Image_map\srini\imageapp\static\swimmingpool.html" coords="1146,170,1368,236" shape="rect">
</map>
</center>
</body>
</html>

mahal.html

<html>
<head>
<title>Mani mahal</title>
</head>
<body bgcolor="yellow">
<h3 align="center">
<font color="red"><b>Mani mahal</b></font>
</h3>
<hr size="8" color="red">
<p align="justify">
<font face="Georgia" size="10">
Mani Mahal in Tirunelveli appears to be a wedding and event venue with air-conditioned halls, ample parking, and facilities for decorations, catering, and other event needs. The venue aims to provide a seamless experience for events like marriages, with dedicated staff and various amenities to assist with planning and execution. It is highlighted as a stunning and technologically advanced venue for various celebrations. 
</p>
</body>
</html>

mytown.html

<html>
<head>
<title>TIRUNELVELI</title>
</head>
<body bgcolor="silver">
<h3 align="center">
<font color="red"><b>TIRUNELVELI</b></font>
</h3>
<hr size="8" color="red">
<p align="justify">
<font face="Georgia" size="10">
Tirunelveli, also known as Nellai and historically as Tinnevelly, is a major city in the Indian state of Tamil Nadu. It is the administrative headquarters of the Tirunelveli District. It is the fourth-largest municipal corporation in the state after Chennai, Coimbatore, and Madurai
</p>
</body>
</html>

swimmingpool.html

<html>
<head>
<title>SDAT Swimming Pool</title>
</head>
<body bgcolor="lightblue">
<h3 align="center">
<font color="red"><b>SDAT Swimming Pool</b></font>
</h3>
<hr size="4" color="red">
<p align="justify">
<font face="Georgia" size="10">
The The SDAT Swimming Pool in Tirunelveli is a government-run facility featuring both 25-meter and 50-meter pools, offering a clean, well-maintained environment with professional coaching and a moderate fee for hourly use. It serves as a valuable infrastructure for sports development in the district, providing a place for students and the public to learn and participate in swimmingin Tirunelveli is a government-run facility featuring both 25-meter and 50-meter pools, offering a clean, well-maintained environment with professional coaching and a moderate fee for hourly use. It serves as a valuable infrastructure for sports development in the district, providing a place for students and the public to learn and participate in swimming
</p>
</body>
</html>

temple.html

<html>
<head>
<title>Venkatachalapathy temple</title>
</head>
<body bgcolor="lightgreen">
<h3 align="center">
<font color="red"><b>Venkatachalapathy temple</b></font>
</h3>
<hr size="8" color="red">
<p align="justify">
<font face="Georgia" size="10">
A "Venkatachalapathy temple" refers to a temple dedicated to Lord Venkatachalapathy (also known as Venkateswara or Srinivasa), a form of the Hindu deity Lord Vishnu. While the most famous is the Sri Venkateswara Temple on Tirumala Hills in Andhra Pradesh, many other temples with the same deity, or local variations, exist throughout India, including the Sri Venkatachalapathy
</p>
</body>
</html>


theatre.html

<html>
<head>
<title>PSS Multiplex</title>
</head>
<body bgcolor="white">
<h3 align="center">
<font color="red"><b>PSS Multiplex</b></font>
</h3>
<hr size="8" color="red">
<p align="justify">
<font face="Georgia" size="10">
PSS Multiplex is a movie theater located in both Tenkasi and Tirunelveli, Tamil Nadu, offering a modern multiplex experience with features like Dolby Atmos sound, 4K projection, and spacious parking. It is known for its comfortable seating, clean interiors, and diverse film selection, though some patrons note high snack prices and parking challenges in Tirunelveli. 
</p>
</body>
</html>
```
# OUTPUT

![alt text](<Screenshot (16).png>)
![alt text](<Screenshot (20).png>)
![alt text](<Screenshot (21).png>)
![alt text](<Screenshot (22).png>)
![alt text](<Screenshot (23).png>)
![alt text](<Screenshot (24).png>)


# RESULT
The program for implementing image maps using HTML is executed successfully.
