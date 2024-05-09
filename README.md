# Ex04 Places Around Me
## Date: 09/05/2024

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
```C
ex4.html
<HTML>
    <HEAD>
        <TITLE>My City</TITLE>
    </HEAD>
    <BODY>
        <h1 align="center">
            <font color="ligthred"><b>pondicherry</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Dhinesh.p(212222043001)</b></font>
        </h3>
        <CENTER>
            <img src="C:\Users\dhine\OneDrive\Pictures\Screenshots\ex4.png" usemap="#mymap" height="500" width="1000">
            <map name="mymap">
                <area title="Paradise Beach Puducherry" href="beach.html" coords="652,320,880,398" shape="rect">
                <area title="Sri Aurobindo Ashram Puducherry" href="Sri Aurobindo.html " coords="452,600,208" shape="circle">
                <area title="Arikamedu Puducherry" href="Arikamedu.html" coords="819,400,981,881" shape="rect">
                <area title="boat House" href="boat House.html" coords="705,315,935,337,710,414,637,317" shape="poly">
            </map>

        </CENTER>
    </BODY>
</HTML>
beach.html

<HTML>
    <HEAD>
        <TITLE> Paradise Beach Puducherry</TITLE>
    </HEAD>
    <body bgcolor="yellow">
        <h1 align="center">
            <font color="red">Pondicherry</font>
        </h1>
        
        <h3 align="center">
            <font color="brown">Paradise Beach Puducherry</font>
        </h3>
        <hr color="sky blue" align="center">
        <br>
        <p><h4>
            Located in Chunnambar, Paradise Beach is an isolated beach ranked as one of the best tourist destinations in Pondicherry. Locally referred to as ‘Plage Paradiso’, this breathtakingly beautiful golden sand beach has a tranquil atmosphere. The crystal-clear water and tropical vibe allow you to enjoy a relaxing day with your family and friends.

You must take an exciting ferry ride from the city to reach the beach. The route is flanked by thick mangrove forests which make your trip to the beach a refreshing journey. A haven for nature lovers, Paradise Beach is a treat for bird watchers as it is home to a wide variety of rare and beautiful species of birds.

The best time to visit this popular weekend getaway from Pondicherry is November to March. Adventure lovers can also enjoy water sports such as Canoeing, Kayaking, Swimming, and Jet Skiing at the beach. There are a few surfing schools in the area where you can rent the required equipment.
        </h4></p>
    </body>
</HTML>
Sri Aurobindo.html

<HTML>
    <HEAD>
        <TITLE>  Sri Aurobindo Ashram Puducherry</TITLE>
    </HEAD>
    <body bgcolor="lightgreen">
        <h1 align="center">
            <font color="red">Pondicherry</font>
        </h1>
        
        <h3 align="center">
            <font color="brown"> Sri Aurobindo Ashram Puducherry</font>
        </h3>
        <hr color="sky blue" align="center">
        <br>
        <p><h4>
            Located towards the eastern part of the city, Sri Aurobindo Ashram is among the famous tourist places of Pondicherry. Founded by Sri Aurobindo Ghose in 1926, the ashram is dedicated to his vision of leading a simple and healthy life. The spiritual atmosphere of the Ashram and soul-soothing silence make it a perfect place to meditate.

You can visit this ashram with your family to relax your body and mind from the stress of routine life. The simplicity of the building and its beautiful interiors are refreshing for the eyes. Sri Aurobindo Ashram is a treat for people curious about life and diverse cultures.

Dance, singing, drama, and other events are regularly organized by the community members at the Ashram. You can learn about the Ashram, Sri Aurobindo, his vision, and the Mother at the theatre where their history and vision are telecasted regularly. The Ashram’s courtyard houses the Samadhi of Sri Aurobindo and the Mother, which is adorned with fresh flowers each day.
        </h4></p>
    </body>
</HTML>
 Arikamedu.html
<HTML>
    <HEAD>
        <TITLE>Arikamedu Puducherry</TITLE>
    </HEAD>
    <body bgcolor="lightgreen">
        <h1 align="center">
            <font color="red">Pondicherry</font>
        </h1>
        
        <h3 align="center">
            <font color="brown"> Arikamedu Puducherry</font>
        </h3>
        <hr color="sky blue" align="center">
        <br>
        <p><h4>
            Located on the banks of the Ariyankuppam River, Arikamedu is a famous Indo-Roman archaeological site. It is among the well-known tourist places near Pondicherry. Inhabited by Romans, French, and Cholas centuries ago, the town was once a popular trade center of the region.

Excavation of the site was started in 1940 and since then interesting details have been unearthed. The site has been acquired by the Archaeological Survey of India for its cultural importance as the only surviving place with remnants of Roman existence in India during 300 BC - 1800 AD.

Valuable artifacts and relics excavated from the site are preserved in the Pondicherry Museum. They give visitors an insight into the history and culture of Arikamedu. The staggering ruins lure history buffs and photographers. A walk along the trails takes you back to the opulent era of trade and exchange in the 1st century BC.
        </h4></p>
    </body>
</HTML>
Boat house.html
```


## OUTPUT
![Screenshot (6)](https://github.com/dhinesh00406/NearMe/assets/147149471/03d406aa-6861-4f3f-b592-fd7ad0d25347)
![Screenshot (7)](https://github.com/dhinesh00406/NearMe/assets/147149471/55eec8f5-29cb-4e4d-b528-9de07f32d231)
![Screenshot (8)](https://github.com/dhinesh00406/NearMe/assets/147149471/e3ed428a-e203-44e0-86e4-ecd53347ba79)
![Screenshot (9)](https://github.com/dhinesh00406/NearMe/assets/147149471/de9b8f25-99e0-4e5f-a66e-853978fe078d)
![Screenshot (10)](https://github.com/dhinesh00406/NearMe/assets/147149471/ba7c6e7d-161a-40fc-b761-3e4752e0c977)












## RESULT
The program for implementing image maps using HTML is executed successfully.
