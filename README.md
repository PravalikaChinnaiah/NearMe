# Ex03 Places Around Me
## Date:05/12/2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
<html>
    <head>
        <title> Sample Page </title>
    </head>
    <body>
        <h1 align ="centre">CHENNAI CITY </h1>
        <h2 align ="centre"> Pravalika(25018550)</h2>
        <img src="Screenshot 2025-11-28 112642.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Sri Veera's Creations" title="Sri Veera's Creations" href="veera's.html" coords="1067,717,1317,798" shape="rect">
    <area target="" alt="Avanthika Enfield Garage" title="Avanthika Enfield Garage" href="garage.html" coords="1029,311,1212,386" shape="rect">
    <area target="" alt="Ziya fashions" title="Ziya fashions" href="fashion.html" coords="1448,293,61" shape="circle">
    <area target="" alt="Sri Raghavendra Hospital" title="Sri Raghavendra Hospital" href="hospital.html" coords="1168,8,1043,91,1261,136,1261,55,1261,130,1263,54" shape="poly">
    <area target="" alt="Public Food Shelter" title="Public Food Shelter" href="food.html" coords="1752,157,76" shape="circle">
</map>
    </body>
</html>

veera's.html           
<html>
    <head>
        <title>Sri Veera's Creations</title>
    </head>
    <body bgcolor="red">
        <h1>Sri Veera's Creations</h1>
        <p>Sri Veera's Creations in Chennai is a well known retail store a wide range of textiles,including silksarees,designer sarees, men's wear,and garments,known for afforable prices and good qualily.</p>
    </body>
</html>

garage.html  
<html>
    <head>
        <title>Avanthika Enfield Garage</title>
    </head>
    <body bgcolor="blue">
        <h1>Avanthika Enfield Garage</h1>
        <p>In Chennai there 26 to 28 Royal Enfields dealerships.These locations  include brand stores and individual showrooms,which offer the full  range of royal Enfieldmodels</p>
    </body>
</html>

fashion.html  
<html>
    <head>
        <title>Ziya fashions</title>
    </head>
    <body bgcolor="pink">
        <h1>Ziya fashions</h1>
        <p> Ziya fashions in Chennai appears to bea general name for several  fashions businessess,with locations in areas like Madipakkam and Ayappakkam.  Some Ziya fashions are of a larger network ,while others are distinct local establishment</p>
    </body>
</html>

hospital.html  
<html>
    <head>
        <title>Sri Raghavendra Hospital</title>
    </head>
    <body bgcolor= "purple">
        <h1>Sri Raghavendra Hospital</h1>
        <p>A hospital rooted in great foundation based out of Ayurveda and siddha concepts.  The reatments involves various therapeuric treatment,various herbal oils ,etc </p>
    </body>
</html>

food.html  
<html>
    <head>
        <title>Public Food Shelter</title>
    </head>
    <body bgcolor="yellow">
        <h1>Public Food Shelter</h1>
        <p>Public food shelters are facilities that provide temporary or permanent refuge and essential services to vvulnerable populations,such as the homeless, victims of domestic abuse or those displaced by disasters.</p>
    </body>
</html>

```

## OUTPUT
[alt text](<Screenshot 2025-12-05 112946.png>)

[alt text](<Screenshot 2025-12-05 113208.png>)

[alt text](<Screenshot 2025-12-05 113227.png>)

[alt text](<Screenshot 2025-12-05 113151.png>)

[alt text](<Screenshot 2025-12-05 113303.png>)

![alt text](<Screenshot 2025-12-05 113242.png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
