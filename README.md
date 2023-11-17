# Ex04 Places Around Me
## Date: 

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
## akm.html
```


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Map</title>
</head>
<body>
    <img src="nearmap.png" usemap="#image-map">

    <map name="image-map">
        <area target="_blank" alt="Arakkonam Railway Station" title="Arakkonam Railway Station" href="station.html" coords="962,331,1127,450" 
shape="rect">
        <area target="_blank" alt="INS Rajali" title="INS Rajali" href="rajali.html" coords="1762,307,1876,413" shape="rect">
        <area target="_blank" alt="Sindhu Cinema" title="Sindhu Cinema" href="cinema.html" coords="87,666,263,723" shape="rect">
        <area target="_blank" alt="Krishna Polytechnic College" title="Krishna Polytechnic College" href="college.html" coords="1031,487,1192,567" shape="rect">
        <area target="_blank" alt="Arakkonam Bus Stand" title="Arakkonam Bus Stand" href="bus.html" coords="1444,495,1647,597" shape="rect">
    </map>
</body>
</html>

## station.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arakkonam Railway Station</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>Arakkonam Junction</h1>
    <br>
    <hr color="Brown">
    <p>Arakkonam Railway Station, officially Arakkonam Junction, and formerly known as Arakkonam Railway (station code: AJJ). Arakkonam Railway Station is a major railway junction located in the town of Arakkonam in the Indian state of Tamil Nadu. It serves as a crucial transportation hub, connecting various cities and towns in the region. The station is well-equipped with essential facilities, including multiple platforms, waiting areas, and ticketing services. Arakkonam Railway Station plays a vital role in facilitating both passenger and freight train services, contributing to the efficient functioning of the Southern Railway network.</p>

</body>
</html>

## rajali.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>INS Rajali</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>INS Rajali Navy Base</h1>
    <br>
    <hr color="Brown">
    <p>INS Rajali is a naval air station located in Arakkonam, Tamil Nadu, India. It serves as a key base for the Indian Navy, primarily focusing on maritime reconnaissance and surveillance. The station is equipped with modern facilities to support various naval aircraft, including patrol planes and reconnaissance aircraft. INS Rajali plays a strategic role in enhancing the maritime security of India, serving as a crucial asset for naval operations in the region.</p>

</body>
</html>

## college.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Krishna Polytechnic College</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>Sri Krishna Polytechnic College</h1>
    <br>
    <hr color="Brown">
    <p>Sri Krishna Polytechnic College was established on 1995. It is an affiliated college of Directorate of Technical Education, Chennai. It is approved by AICTE. It has maximum student cout of 923 and faculty count of 69. It has various facilities like Laboratories, Library, Hospital, Transport Facility, I.T Infrastructure, Cafeteria, Auditorium, Sports. Sri Krishna polytechnic college typically offers technical education and practical skills training in various disciplines. It would provide diploma-level education in fields such as engineering, technology, or applied sciences.</p>

</body>
</html>

## cinema.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sindhu Cinema</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>Sindhu Cinema</h1>
    <br>
    <hr color="Brown">
    <p>Sindhu Cinemas is a well known theatre in Arakkonam. Cinema is equipped with comfortable push backed enabled Seating and fully air conditioned. The theatre has ample car and two-wheeler Parking and the canteen caters fresh and quality food items. A cinema hall which provides redefining movie going experience. Be spoilt for choice ! We, offers a wide selection of short eats and beverages that are not only scrumptious but also stored and served under safe and hygienic conditions. The menu selection offers a range of irresistible combos too. The menu undergoes regular revisions to surprise your taste buds. We have also revamped our canteen facilities to deliver quick service and our courteous staff will ensure that you enjoy the services all all times.</p>

</body>
</html>

## bus.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arakkonam Bus Stand</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>Arakkonam Main Bus Stand</h1>
    <br>
    <hr color="Brown">
    <p>Arakkonam's bus stand likely plays a crucial role in the local and regional transportation network, connecting the town with nearby cities and towns. It may have facilities such as ticket counters, waiting areas, and information boards to assist passengers. For the most accurate and up-to-date information, including bus schedules and services, it's recommended to check with local transportation authorities or visit the bus stand in person.</p>

</body>
</html>
```

## OUTPUT







## RESULT
The program for implementing image maps using HTML is executed successfully.
