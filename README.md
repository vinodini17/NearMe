# Ex04 Places Around Me
## Date: 1.4.2024

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
        <title>Map</title>
    </head>
    <body>
        <h1 align="center">RETTERI</h1>
        <h2 align="center">VINODINI</h2>
        <h2 align="center">212223040244</h2>
        <center><img src="Screenshot 2024-04-01 105407.png" usemap="#img-map"></center>
        <map name="img-map">
            <area target="" alt="hotel" title="hotel" href="hotel.html" coords="400,712,591,589" shape="rect">
            <area target="" alt="school" title="school" href="school.html" coords="379,329,118" shape="circle">
            <area target="" alt="cini" title="cini" href="cini.html" coords="1480,433,1749,550" shape="rect">
            <area target="" alt="chess" title="chess" href="chess.html" coords="967,102,1281,183" shape="rect">
            <area target="" alt="cafe" title="cafe" href="cafe.html" coords="1074,842,115" shape="circle">
</map>



        
    </body>
</html>
```
## HOTEL
```
<html><head><title>hotel</title></head>
<body bgcolor="purple">
    <h1 align="center">RETTERI</h1>
    <h2 align="center">hotel</h2>
    <p>AR Garden Road, 200 feet road ,North, 8, NH 716, Behind Poovanthi Rehabilitation Centre, Korattur, Chennai, Tamil Nadu 600080</p>
    
</body></html>
```
## CINEMA
```
<html>
    <head><title>cini</title></head>
    <body bgcolor="lightgreen">
        <h1 align="center">RETTERI</h1>
        <h2 align="center">cinema</h2>
        <p>Sri Ganga Cinemas is considered to be a major landmark at its locality in Kolathur .The Theatre is said to have 24 years of experience in its field. Sri Ganga cinemas on the whole has three screens Ganga, Yamuna and Kaveri.</p>
    </body>
</html>
```
## SCHOOL
```
<html>
    <head>
        <title>School</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">RETTERI</h1>
        <h2 align="center">Padmashree School</h2>
        <hr>
        <center><p>Padmashree School is committed to provide quality education of global standards through value based learning experience that unfolds the unique potential and talent of each child. It is also committed to create lifelong learners, global citizens and inspirational leaders of tomorrow with innovative ideas and a strong sense of values.</p></center>
    </body>
</html>
```
## CAFE
```
<html>
    <head><title>cafe</title></head>
    <body bgcolor="yellow">
        <h1 align="center">RETTERI</h1>
        <h2 align="center">GREEN TREE CAFETERIA</h2>
        <hr>
        <center><p>Kamaraj St, Sri Venkatesa Nagar, Venkateshwara Nagar, Kolathur, Chennai, Tamil Nadu 600099</p></center>


    </body>
    
</html>
```
## CHESS
```
<html>
    <head><title>chess</title></head>
    <body bgcolor="lightblue">
        <h1 align="center">RETTERI</h1>
        <h2 align="center">Sathuranga chess club</h2>
        <p>Venkatesh Elumalai – Creator of Tamil Chess Channel and the Founder of Sathuranga Chanakyan Foundation.

            Welcome to Tamil chess channel! I’m a self -taught chess
            enthusiast who has been sharing my passion for the game for the past 4.5 years.
            With over 64k subscribers and 1100 + videos, I have built a thriving community of
            chess players from around the world.
            
            </p>
    </body>
</html>
```
## OUTPUT
![image](https://github.com/vinodini17/NearMe/assets/149347288/740f3e86-3bbe-46eb-b995-0fe076abbc5e)
![image](https://github.com/vinodini17/NearMe/assets/149347288/204f2385-f575-4d25-8689-058c6c824754)
![image](https://github.com/vinodini17/NearMe/assets/149347288/b2993bdb-e4e0-4049-9915-210a45a6c41d)
![image](https://github.com/vinodini17/NearMe/assets/149347288/2f43321e-3875-40e2-adac-30003a801891)
![image](https://github.com/vinodini17/NearMe/assets/149347288/28a9ab17-3dfe-4791-8b06-0c4806ac0624)
![image](https://github.com/vinodini17/NearMe/assets/149347288/d6bcd390-e0ce-4ae5-b7af-a1851e3fff2b)












## RESULT
The program for implementing image maps using HTML is executed successfully.
