# Ex04 Places Around Me
# Date:24/11/24
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
~~~
<!DOCTYPE html>
<html>
    <head>
        <title>Image Map</title>
        <link rel="stylesheet" href="map.css">
    </head>
    <body>
        <div id="container">
            <div id="image_container">
                <img src="mapnew1.png" usemap="#image-map">

<map name="image-map">
    <area alt="Anna Nagar" target="_blank" title="Anna Nagar" href="annanagar.html" coords="287,321,560,435"shape="rect">
    <area alt="Villivakam" target="_blank" title="Villivakam" href="villivakam.html" coords="242,37,498,118" shape="rect">
    <area alt="Koyambedu" target="_blank" title="Koyambedu" href="koyambedu.html" coords="117,540,336,632" shape="rect">
    <area alt="Egmore" target="_blank" title="Egmore" href="egmore.html" coords="978,495,1147,580" shape="rect">
    <area alt="Padi" target="_blank" title="Padi" href="padi.html" coords="33,200,164,266" shape="rect">
    <area alt="Korattur" target="_blank" title="Korattur" href="korattur.html" coords="1,37,176,120" shape="rect">                                                                                 ,74" shape="rect">
    <area alt="Chennai" target="_blank" title="Chennai" href="chennai.html" coords="1015,331,1333,456" shape="rect">
</map>
            </div>
        </div>
    </body>
</html>
~~~
## anna nagar:
~~~
<!DOCTYPE html>
<html>
    <body>
        <center>
    <img style="width:720px ;" src="anna nagar.jpg">
    <h1>Anna Nagar</h1>
    </center>
        <h2>The area was originally called Mullam Village, and was a peaceful place with paddy fields and the Coovum river. Anna Nagar was developed by the Tamil Nadu Housing Board in the early 1970s following the World Trade Fair in the area in 1968. The board developed residential plots, apartments, commercial complexes, wide roads, school zones, bus termini, and large parks.</h2>
    </body>
</html>
~~~
## chennai:
~~~
<!DOCTYPE html>
<html>
    <body>
        <center>
        <img style="width:720px ;" src="chennai.jpg">
        <h1>Chennai</h1>
        </center>
        <h2>Chennai, formerly known as Madras, is the capital of the state of Tamil Nadu and is India's fifth largest city.[1] It is located on the Coromandel Coast of the Bay of Bengal. With an estimated population of 12.05 million (2024), the 383-year-old city is the 31st largest metropolitan area in the worldChennai boasts a long history from the English East India Company, through the British rule to its evolution in the late 20th century as a services and manufacturing hub for India. Additionally, the pre-city area of Chennai has a long history within the records of South Indian Empires</h2>
    </body>
</html>
~~~
## egmore:
~~~
<!DOCTYPE html>
<html>
    <body>
        <center>
        <img style="width:720px ;" src="Egmore.jpg">
        <h1>Egmore</h1>
        </center>
        <h2>Egmore, a locality in Chennai, India, has a rich history that includes the Chola Empire, the East India Company, and the British rule:
            Chola Empire
            Egmore was the headquarters of Elumbur Nadu, an administrative division under the Chola Empire.
            East India Company
            The East India Company acquired Egmore in 1720. In the early 18th century, the company converted a choultry into a fortified redoubt.
            British rule
            Egmore experienced significant growth during the "Golden age of British rule" from 1858 to 1947. The Egmore Museum was one of the first notable monuments built in the area after the Sepoy Mutiny of 1857.</h2>
    </body>
</html>
 ~~~
## korattur:
~~~
<!DOCTYPE html>
<html>
    <body>
        <center>
        <img style="width:720px ;" src="korattur.jpeg">
        <h1>Korattur</h1>
        </center>
        <h2>Korattur, a suburb of Chennai, India, has a history that includes its development from a village to an industrial hub and residential area:
            Early history: Korattur was a village in the 20th century.
            Industrial development: Korattur is now an industrial hub with manufacturing, textile, and engineering industries. It's located next to the Ambattur Industrial Estate.
            Residential development: Korattur has become a popular residential area with a variety of housing options. It's known for being affordable and having essential amenities like schools, hospitals, and markets.
            Infrastructure development: Korattur has seen a lot of large-scale infrastructure development.
            Korattur Aeri: Korattur Aeri, also known as Korattur Lake, is one of the largest lakes in the western part of Chennai. The lake was used to supply water to Chennai residents during a shortage in the late 1970s. However, the lake has been contaminated with sewage and industrial effluents.
            Korattur railway station: The first lines at the Korattur railway station were electrified in 1979, and additional lines were electrified in 1986</h2>
    </body>
</html>
~~~
## padi:
~~~
<!DOCTYPE html>
<html>
    <body>
        <center>
        <img style="width:720px ;height: 500px;" src="Padi.JPG">
        <h1>Padi</h1>
        </center>
        <h2>Name
            Padi is a shortened version of the name Thiruvaaipadi. The name Padi comes from the Tamil word for a resting place near a war field.
            History
            Padi is an industrial area that's popular with the working class. It's located 13 kilometers from the city's Kilometer Zero and is crossed by MTH Road, which is now known as CTH Road.
            Temples
            Padi is home to several temples, including the Arulmigu Thiruvalithayam Temple, which is a famous Guru Bhagawan temple. The Padavattamman Temple is another nearby temple.
            Festivals
            Padi hosts a big festival every year called Thai Kirthigai.</h2>
    </body>
</html>
~~~
## villivakkam:
~~~
<!DOCTYPE html>
<html>
    <body>
        <center>
        <img style="width:720px ;" src="villivakam.jpeg">
        <h1>Villivakam</h1>
        </center>
        <h2>Villivakkam, a part of Chennai in Tamil Nadu, India, has a rich history, including the name's origin, a Shiva temple, and a lake:
            Name
            The original name of Villivakkam was Vilvaaranyam, which means "jungle of bael trees". The name comes from the many bael trees in the area and an old Shiva temple built by Sage Agasthiyar.</h2>
    </body>
</html>
~~~
# OUTPUT
![Screenshot (34)](https://github.com/user-attachments/assets/bbbe4609-6a07-4734-a392-5658831885f1)
![Screenshot (40)](https://github.com/user-attachments/assets/9b46a4ac-a940-459d-9bf5-2ffe1efc07c6)
![Screenshot (37)](https://github.com/user-attachments/assets/79a57f06-8249-43ef-b505-d7f2294817c3)
![Screenshot (35)](https://github.com/user-attachments/assets/97e4e8fe-f4bc-432b-b0c3-c17e3c227b96)
![Screenshot (36)](https://github.com/user-attachments/assets/4c7ce2ed-1569-459b-bf18-96fa6ecb90f9)
![Screenshot (38)](https://github.com/user-attachments/assets/2285debc-d74e-480a-8d52-71b5b41732c8)
![Screenshot (39)](https://github.com/user-attachments/assets/e367c060-972e-42ed-890d-b3c926b80ba2)

# RESULT
The program for implementing image maps using HTML is executed successfully.
