# Ex04 Places Around Me
## Date: 22.11.2024

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html


<html>
<head>
<title>MyCity</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>VILLUPURAM</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>JanathulFirdhous A (24900115)</b></font>
</h3>
<center>

        <img src="map.png" usemap="#image-map">

        <map name="image-map">
            <area target="" alt="golden park" title="golden park" href="park.html" coords="945,570,759,509" shape="rect">
            <area target="" alt="marudur" title="marudur" href="marudur.html" coords="1074,403,119" shape="circle">
            <area target="" alt="salamedu" title="salamedu" href="salamedu.html" coords="782,598,923,585,875,688,679,708,700,644,734,580,766,592" shape="poly">
            <area target="" alt="villupuram" title="villupuram" href="villupuram.html" coords="794,358,927,407" shape="rect">
            <area target="" alt="vandimedu" title="vandimedu" href="vandimedu.html" coords="778,318,884,353" shape="rect">
        </map>


</center>
</h3>
</body>
</html>

marudur.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">
            <font color="cyan"><b>VILLUPURAM</b></font>
            </h1>
            <h3 align="center">
                <font color="lime"><b>marudur</b></font>
            </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5" color="white">
                V. Marudur is a Locality in Villupuram City in Tamil Nadu State, India.
V. Marudur Pin code is 605602 and postal head office is Villupuram .

Mani Nagar , Mani Nagar , Narasingapuram , K K Nagar , Vvc Nagar are the nearby Localities to V. Marudur.Villupuram Junction Rail Way Station , Mundiyampakkam Rail Way Station are the very nearby railway station to V. Marudur.

                
            </font>
        </p>
    </body>
</html>

park.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="lime">
        <h1 align="center">
            <font color="red"><b>VILLUPURAM</b></font>
            </h1>
            <h3 align="center">
                <font color="blue"><b>Golden_park</b></font>
            </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5" color="white">
                At the intersection of comfort and convenience lies GOLDEN PARRK, where you can take full advantage of numerous amenities and services that are guaranteed to make your stay with us a memorable one. We seek to provide you with the attention and luxury you deserve. Featuring impeccable accommodations and an attentive staff, we guarantee you’ll have a pleasant experience here. Explore our site to see what we have to offer, and don’t hesitate to reach out with questions.       
            </font>
        </p>
    </body>
</html>

salamedu.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="lime">
        <h1 align="center">
            <font color="cyan"><b>VILLUPURAM</b></font>
            </h1>
            <h3 align="center">
                <font color="purple"><b>Salamedu</b></font>
            </h3>
        <hr size="3" color="green">
        <p align="justify">
            <font face="Georgia" size="5" color="white">
                Viluppuram is a municipality and the administrative headquarters of Viluppuram district, the largest district in the state of Tamil Nadu, India. It is well connected by both road and rail to all the important cities in Tamil Nadu. The town is a major railway junction, and National Highway 45 passes through it.


             </font>
        </p>
    </body>
</html>

vandimedu.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b>VILLUPURAM</b></font>
            </h1>
            <h3 align="center">
                <font color="blue"><b>vandimedu</b></font>
            </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                Vandimedu is a Locality in Villupuram City in Tamil Nadu State, India.
Vandimedu Pin code is 605602 and postal head office is Villupuram .

Sri Ganesh Nagar , Govindhaswamy Nagar , Vandimedu , Selva Nagar , Ragavendra Nagar are the nearby Localities to Vandimedu.

                
            </font>
        </p>
    </body>
</html>

villupuram.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
            <font color="purple"><b>VILLUPURAM</b></font>
            </h1>
            <h3 align="center">
                <font color="pink"><b>MAIN_VILLUPURAM</b></font>
            </h3>
        <hr size="3" color="cyan">
        <p align="justify">
            <font face="Georgia" size="5" color="white">
                Viluppuram is a municipality and the administrative headquarters of Viluppuram district, the largest district in the state of Tamil Nadu, India. It is well connected by both road and rail to all the important cities in Tamil Nadu. The town is a major railway junction, and National Highway 45 passes through it.


             </font>
        </p>
    </body>
</html>

```


## OUTPUT
![alt text](<Screenshot (34)-1.png>)

![alt text](<Screenshot (35).png>)

![alt text](<Screenshot (36).png>)
![alt text](<Screenshot (37).png>)
![alt text](<Screenshot (38).png>)
![alt text](<Screenshot (39).png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
