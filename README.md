# Ex04 Places Around Me
# Date:29.04.2025
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
map.html
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>My Home Town</title>
   <style>
       img{
           padding-top: 1%;
       }
       h1{
           text-align: center;
           font-size: 48px;
           color: white;
       }
       body{
           background-color: rgb(106, 17, 250);
       }
   </style>
</head>
<body>
   <h1>My Home Town</h1>
   <center><img src="map.png" usemap="#image-map" width="1400px" height="800px">
   <map name="image-map">
    <area target="" alt="Ekambaranathar Temple" title="Ekambaranathar Temple" href="t1.html" coords="529,181,808,253"" shape="rect">
    <area target="" alt="Kailasanathar Temple" title="Kailasanathar Temple" href="t2.html" coords="77,175,356,247" shape="rect">
    <area target="" alt="Sri Vaikunta Perumal Temple" title="Sri Vaikunta Perumal Temple" href="t3.html" coords="660,263,939,335" shape="rect">
    <area target="" alt="Sri Varadharaja Perumal Temple" title="Sri Varadharaja Perumal Temple" href="t4.html" coords="916,621,1195,693" shape="rect">
    <area target="" alt="Arignar Anna Memorial Park" title="Arignar Anna Memorial Park" href="p.html" coords="247,438,526,510" shape="rect">

</map>
</body>
</html>

t1.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ekambaranathar Temple</title>
    <style>
        h1 {
            color: red;
            text-align: center;
            font-size: 48px;
        }

        p {
            padding-top: 2%;
            font-size: 28px;
            padding-right: 5%;
            padding-left: 2%;
            color: blue;
        }

        body {
            background-color: yellow;
        }
    </style>
</head>

<body>
    <h1>Ekambaranathar Temple</h1>
    <hr color="black">
    <p><b>
            The Ekambaranathar Temple in Kanchipuram, Tamil Nadu, is one of the most significant temples dedicated to
            Lord Shiva. It is part of the Pancha Bhoota Stalas, representing the element Earth. The temple's history
            dates back to the Pallava dynasty and has been expanded over time by various dynasties, including the Cholas
            and Vijayanagara Empire. The temple complex features a towering five-tiered Rajagopuram, vast courtyards,
            intricately carved halls, and a sacred mango tree believed to be over 3,000 years old, with three varieties
            of mangoes symbolizing the three gunas (Sattva, Rajas, and Tamas).
            <br><br>
            Legend has it that Goddess Parvati once worshipped Lord Shiva under a mango tree here, and Lord Shiva
            appeared as the tree itself to bless her. The temple is known for its grand rituals and festivals, such as
            Shivarathri and Vaikasi Visakam, which draw large crowds. It is a center of spiritual significance and
            architectural beauty, offering a place for both devotion and historical exploration.
        </b></p>
    <br><br>
    <hr color="black">
</body>

</html>
t2.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kailasanathar Temple</title>
    <style>
        h1 {
            color: brown;
            text-align: center;
            font-size: 48px;
        }

        p {
            padding-top: 2%;
            font-size: 28px;
            padding-right: 5%;
            padding-left: 2%;
            color: rgb(227, 83, 83);
        }


        body {
            background-color: rgb(171, 147, 215);
        }
    </style>
</head>

<body>
    <h1>Kailasanathar Temple</h1>
    <hr color="black">
    <p><b>The Kailasanathar Temple is a renowned Hindu temple located in Kanchipuram, Tamil Nadu, dedicated to
            Lord Shiva. Built during the Pallava dynasty in the 8th century CE by Raja Simha, it is
            considered one of the oldest and most important temples in the region. The temple is renowned for its
            architecture, which is a fine example of early Dravidian style, and is often considered a precursor
            to the grander Dravidian temples built later.
            <br><br>
            The Kailasanathar Temple is especially famous for its intricate carvings and sculptures, which
            include beautiful depictions of deities, mythological stories, and scenes from the Shiva Purana. The
            temple complex has a small sanctum housing the main deity, Lord Kailasanathar, in the form of
            Shiva, with a separate shrine dedicated to Parvati. The temple's pillared hall (mandapam) and
            vast courtyards are surrounded by a series of smaller shrines and monolithic structures,
            creating a peaceful and meditative atmosphere. The Kailasanathar Temple is one of the architectural gems of
            Kanchipuram, reflecting the artistic mastery of the Pallava period.</b></p>
    <br><br>
    <hr color="black">
</body>

</html>
t3.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sri Vaikunta Perumal Temple</title>
    <style>
        h1 {
            color: rgb(210, 56, 221);
            text-align: center;
            font-size: 48px;
        }

        p {
            padding-top: 2%;
            font-size: 28px;
            padding-right: 5%;
            padding-left: 2%;
            color: rgb(41, 41, 238);
        }

        body {
            background-color: rgb(80, 235, 109);
        }
    </style>
</head>

<body>
    <h1>Sri Vaikunta Perumal Temple</h1>
    <hr color="black">
    <p><b>The Sri Vaikunta Perumal Temple is a prominent Vaishnavite temple located in Kanchipuram, Tamil
            Nadu. Dedicated to Lord Vishnu, it is one of the 108 Divya Desams, which are the holy abodes of
            Vishnu mentioned in the works of the Alvars (Tamil saints). The temple is famous for its unique
            architecture and rich religious significance, dating back to the Pallava dynasty in the 8th century
            CE.
            <br><br>
            The temple is built in the Dravidian style and features an impressive five-tiered Rajagopuram (gateway
            tower), and a spacious inner sanctum housing the main deity, Vaikunta Perumal, a form of Vishnu. It is
            particularly known for its massive corridors and intricate sculptures, which include depictions of
            various mythological stories and scenes from the life of Lord Vishnu. The temple also houses a beautiful
            central shrine dedicated to Vishnu's consort, Goddess Lakshmi. The Vaikunta Ekadasi festival,
            celebrated here with great fervor, attracts numerous devotees every year, who come to offer prayers and seek
            blessings for prosperity and spiritual growth.</b></p>
    <br><br>
    <hr color="black">
</body>

</html>
t4.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sri Varadharaja Perumal Temple</title>
    <style>
        h1 {
            color: rgb(48, 234, 221);
            text-align: center;
            font-size: 48px;
        }

        p {
            padding-top: 2%;
            font-size: 28px;
            padding-right: 5%;
            padding-left: 2%;
            color: rgb(59, 52, 104);
        }

        body {
            background-color: rgb(249, 42, 242);
        }
    </style>
</head>

<body>
    <h1>Sri Varadharaja Perumal Temple</h1>
    <hr color="black">

    <p><b>The Sri Varadharaja Perumal Temple is one of the most famous Vaishnavite temples in Kanchipuram,
            Tamil Nadu, dedicated to Lord Varadharaja Perumal, a form of Lord Vishnu. It is one of the 108
            Divya Desams, sacred shrines of Lord Vishnu, and holds great religious significance for followers of the
            Sri Vaishnavism tradition. The temple's history dates back to the Chola dynasty and was further
            expanded during the Vijayanagara dynasty, with notable contributions from rulers like
            Krishnadevaraya.
            <br><br>
            The temple is known for its stunning architecture, featuring a grand five-tiered Rajagopuram and an
            expansive prakaras (outer courtyards). The main deity, Lord Varadharaja Perumal, is enshrined in a
            seated posture, and the temple also houses a shrine for Goddess Lakshmi. The temple complex is renowned
            for its beautiful carvings, including those depicting scenes from the Ramayana and Mahabharata,
            as well as other mythological stories. One of the temple's most notable features is the Varadaraja Perumal
            idol, which is traditionally taken out of the temple once every 40 years for a special ritual known as the
             Kanchipuram Varadaraja Darshan". The temple is also an important center for Vaishnavite rituals and
            festivals, with the Brahmotsavam and Vaikunta Ekadasi being celebrated with great
            enthusiasm.</b></p>

    <br><br>
    <hr color="black">
</body>

</html>

```
# OUTPUT
![alt text](<Screenshot 2025-04-29 063821.png>)
![alt text](<Screenshot 2025-04-29 063842-1.png>)
 ![alt text](<Screenshot 2025-04-29 063931.png>) 
 ![alt text](<Screenshot 2025-04-29 063953.png>) 
 ![alt text](<Screenshot 2025-04-29 064007.png>)
# RESULT
The program for implementing image maps using HTML is executed successfully.
