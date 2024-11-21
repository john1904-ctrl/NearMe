# Ex04 Places Around Me
## Date: 21.11.24

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
<title>My City</title>
</head> 
<body>
    <h1 aligen="center"
<font align="center" color="red"><b>Pudukkottai</b></font>
</h1>
<h3 align="center">
    <font color="blue"><b>John Pall M (24900131)</b></font>
</h3>
<center>

<img src="Screenshot (32).png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="arimalam" title="arimalam" href="arimalam.html" coords="989,778,1111,852" shape="rect">
    <area target="" alt="alangudi" title="alangudi" href="alangudi.html" coords="1198,655,69" shape="circle">
    <area target="" alt="pudukkottai" title="pudukkottai" href="pudukkottail.html" coords="877,591,913,539,1052,545,1089,589,1049,658,902,650" shape="poly">
    <area target="" alt="tirumayam" title="tirumayam" href="tirumayam.html" coords="825,837,74" shape="circle">
    <area target="" alt="keeranur" title="keeranur" href="keeranur.html" coords="954,352,808,264" shape="rect">
</map>
</center>
 </body>
  </html>



alangudi.html

<html>
    <body bgcolor="lightred">
        <font><h1 align="center">Alangudi</h1></font>
        <font align="center" size="5"><p>
            <br>
           
            Alangudi is a municipality in the Pudukkottai district of the Indian state of Tamil Nadu, that serves as the headquarters for Alangudi taluk, one of the 11 taluks in Pudukkottai district. The town has been ruled, at different times, by the Cholas, Mutharaiyars, Early Pandyas, Thondaimans, and the British. It is situated about 395 kilometres (245 mi) southwest of Chennai and about 75 kilometres (47 mi) southeast of Tiruchirappalli. Tamil Nadu's first women Asiad Santhi Soundarajan is from Alangudi municipality.
        </p></font>
    </body>
</html>



arimalam.html

<html>
    <body bgcolor="lightgray">
        <font><h1 align="center">arimalam</h1></font>
        <font align="center" size="5"><p>
            <br>
            
            As of the 2011 Indian census, The Arimalam city is divided into 15 wards for which elections are held every 5 years. The Arimalam Town Panchayat has population of 19,948 of which 10,552 are males while 9,448 are females as per report released by Census India 2015.

Population of Children with age of 0-6 is 890 which is 9.95% of total population of Arimalam (TP). In Arimalam Town Panchayat, Female Sex Ratio is of 1004 against state average of 996. Moreover, Child Sex Ratio in Arimalam is around 1,055 compared to Tamil Nadu state average of 943.

Literacy rate of Arimalam city is 78.98% lower than state average of 80.09%. In Arimalam, Male literacy is around 87.25% while female literacy rate is 70.69%.
        </p></font>
    </body>
</html>



keeranur.html

<html>
    <body bgcolor="lightpink">
        <font><h1 align="center">keeranur</h1></font>
        <font align="center" size="5"><p>
            <br>
           
            Keeranur is a panchayat town in Pudukkottai District in the Indian state of Tamil Nadu. It is located 225 km South-East of Coimbatore. The Uthama Nathaswami Sivan Temple is of a Mutharaya edifice and contains epigraphs of Cholas and Vijayanagar Empires
        </p></font>
    </body>
</html>



pudukkottai.html

<html>
    <body bgcolor="lightblue">
        <font><h1 align="center">pudukkottai</h1></font>
        <font align="center" size="5"><p>
            <br>
            
            - Pudukottai became a separate district only during recent times. The area is clearly founded upon ancient traditions.
            The district of Pudukottai has a very eminent history. It seems to have seen the ruling of various dynasties over the course of time.
            Our Tamil literature has seen various poets who have hailed from this particular area. It proves to be a very sacred land to the
            Pandyas. It was a great centre of trade and business. History tells that many of the wars between the Pallavas and the Pandiyas
            have been fought in this area. Tamil literature of the Sangam period has mentioned many places of this district. The district
            became a sort of marchar land between the Pandyas and the Pallavas. The Cauveri river plays an important role in the geography
            of the area. The area is a reserve for various archaeological explorations. It has many monuments and scriptures that identify the
            diversity of rulers the land has seen. It is a abode of cultural inferences. The ground has always been a point for power struggle
            between the Cholas, Pandiyas and the Pallavas. The area was at its beneficial peak only during the reign of Raja Raja I. In the
            17th and 18th centuries the area also saw the rule of the Thondaiman Dynasty. The famous Carnatic Wars were mostly fought
            around Tiruchirapalli. The history of Pudukottai is of vital importance in order to understand the transformations that have taken
            place in Tamil Nadu over the course of time.
            
        </p></font>
    </body>
</html>



tirumayam.html

<html>
    <body bgcolor="lightgreen">
        <font><h1 align="center">Thirumayam</h1></font>
        <font align="center" size="5"><p>
            <br>
        
            Thirumayam is a town located in Pudukkottai district of the Indian state of Tamil Nadu. It is a place of historical importance located about 22 km from the Capital City of Pudukkottai & 22 km from the city of Karaikudi. The noted Indian independence activist Sathyamurthy was born in Thirumayam in 1887
        </p></font>
    </body>
</html>

```

## OUTPUT

![alt text](<Screenshot (34).png>) 

![alt text](<Screenshot (35).png>) 

![alt text](<Screenshot (36).png>) 

![alt text](<Screenshot (37).png>) 

![alt text](<Screenshot (38).png>) 

![alt text](<Screenshot (39).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
