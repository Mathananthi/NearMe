# Ex04 Places Around Me

# Date: 31.10.2023

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
<html>
<head>
<title> Image Map </title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Viralimalai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Places Around Me</b></font>
</h3>
<center>
<img src="Screenshot (8).png" usemap="#MyCity" >
<map name="MyCity">
<area shape="rectangle" coords="445,623,647,691" href="theatre.html" title="Jothi Theatre">
<area shape="rectangle" coords="718,174,861,245" href="school.html" title="Vivega School">
<area shape="circle" coords="845,401,104" href="busstand.html" title="Viralimalai Bus Stand">
<area shape="rectangle" coords="113,801,284,852" href="ground.html" title="Cricket Ground Vanathirayanpatti">
<area shape="rectangle" coords="974,631,1098,677" href="fireworks.html" title="Ambal Fireworks">
</map>
</center>
</body>
</html>
```
```
<html>
<head>
<title>Viralimalai</title>
</head>
<body bgcolor="gray">
<h3 align="center"></h3>
<hr size="3" color="blue">
<p align="justify">
Ambal Fireworks at Viralimalai
</p>
<p>
    Ambal Fireworks Industries is a 47 year old company incepted in the year 1974 in Viralimalai, Tamil Nadu. Under the able guidance of Late Shri A. Arunachala Nadar, the company emerged as one of the leading firecracker manufacturers in India. We are also a reputed member of the International Fireworks Association (IFA) & Tamil Nadu Fireworks and Amorces Manufacturers’ Association (TANFAMA) and have a vast number of clients spread all over India.
</p>
</body>
</html>
```
```
<html>
<head>
<title>Viralimalai</title>
</head>
<body bgcolor="yellow">
<h3 align="center"></h3>
<hr size="3" color="blue">
<p align="justify">
Cricket Ground Vanathirayanpatti at Viralimalai
</p>
<p>
    A cricket field or cricket oval is a large grass field on which the game of cricket is played. Although generally oval in shape, there is a wide variety within this: some are almost perfect circles, some elongated ovals and some entirely irregular shapes with little or no symmetry – but they will have entirely curved boundaries, almost without exception
</p>
</body>
</html>
```
```
<html>
<head>
<title>Viralimalai</title>
</head>
<body bgcolor="red">
<h3 align="center"></h3>
<hr size="3" color="blue">
<p align="justify">
Viralimalai Bus Stand
</p>
<p>
    A bus stand, also called a bus bay, or bus stance, is a designated parking location where a bus or coach waits out of service between scheduled public transport services.
</p>
</body>
</html>
```
```
<html>
<head>
<title>Viralimalai</title>
</head>
<body bgcolor="white">
<h3 align="center"></h3>
<hr size="3" color="blue">
<p align="justify">
Vivega Matriculation School Viralimalai
</p>
<p>
    This school runs classes from 1 to 12 to provide education to students. 793 is approximately the current student strength of this school. This school's library has 4200 books.
</body>
</html>
```
```
<html>
<head>
<title>Viralimalai</title>
</head>
<body bgcolor="pink">
<h3 align="center"></h3>
<hr size="3" color="blue">
<p align="justify">
Jothi Theatre Viralimalai
</p>
<p>
    Jothi Theatre A/c 4k Dts, Viralimalai is a chain of theatres in India that exhibit a myriad of movies around the year. Be it a Regional, Bollywood or Hollywood movie, at Jothi Theatre A/c 4k Dts, Viralimalai you can catch them all.
</p>
</body>
</html>
```

## OUTPUT
![Alt text](<Screenshot 2023-10-31 224026.png>)
![Alt text](<Screenshot (11).png>)
![Alt text](<Screenshot (12).png>)
![Alt text](<Screenshot (13).png>)
![Alt text](<Screenshot (14).png>)
![Alt text](<Screenshot (15).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
