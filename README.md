# Ex04 Places Around Me
## Date: 26/9/25

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
mapcode
 <head>
    <title>
        erode 

    </title>
    <body>
        <img src="c:\Users\acer\Pictures\Screenshots\Screenshot (24).png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="turmeric!!!" title="turmeric!!!" href="turmeric.html" coords="764,732,41" shape="circle">
    <area target="" alt="cinema!!!" title="cinema!!!" href="cinema.html" coords="956,802,45" shape="circle">
    <area target="" alt="park!!!" title="park!!!" href="park.html" coords="1344,838,58" shape="circle">
    <area target="" alt="dmat!!!" title="dmat!!!" href="dmart.html" coords="679,339,849,420" shape="rect">
    <area target="" alt="hotel!!!" title="hotel!!!" href="hotel.html" coords="1008,702,1078,642,1134,642,1223,656,1207,722,1073,749" shape="poly">
</map>

    </body>
 </head>
 

hotel.html
<html>

<head>
    <title>

    </title>
    <style>
        h1{
            text-align: center;
        }
        body{
            color:darkorchid;
            background-color: cyan;
        }
    </style>
</head>

<body>
    <h1>
        Hotel 
    </h1>
    <p>
        Hotels in Erode, such as Lemon Tree Hotel Erode and Hotel Gokul Grande, offer various amenities like<br>
        multi-cuisine restaurants, bars, modern rooms, and helpful staff, catering to both business and leisure<br>
        travelers in locations like Thirunagar Colony and near the bus stand.
    </p>
    <img src="hotel.jpg.jpg" style="width: 300; height: auto; alt: error;">

</body>

</html>
park.html

<html>

<head>
    <style>

    </style>
</head>

<body>
    <p>
        Periyar Park" in Erode likely refers to the Thanthai Periyar Wildlife Sanctuary, a newly notified protected area<br>
        in Tamil Nadu's Erode district. This 80,000+ hectare sanctuary serves as a vital ecological corridor for<br>
        wildlife moving between the Western and Eastern Ghats, supporting diverse flora and fauna, including significant<br>
        populations of tigers and elephants. It is situated in the Bargur Hills and connects to other reserves,<br> 
        facilitating wildlife movement between states.
        Key
    </p>
    <img src="park.jpg (2).jpg">
</body>

</html>
dmart.html
<html>

<head>
    <style>
        body {
            background-color: blueviolet;
        }

        h1 {
            text-align: center;
            color: cornsilk;
        }
    </style>
</head>

<body>
    <h1>Erode Dmart</h1>
    <p>DMart is an Indian supermarket chain owned by Avenue Supermarts Ltd. that provides a variety of home and
        personal<br>
        Damani, its core objective is to offer good products at great value through its "Everyday Low Prices" (EDLP)<br>
        strategy. The Erode DMart stores, such as the one in Karungalpalayam,<br> are part of the company's
        widespread<br>
        presence across India, focusing on being a low-cost retailer in its operating regions. </p>
    <img src="dmart.2" style="width: 300pt; height: auto; alt: error;">

</body>

</html>
cinema.html
<html>

    <head>
        <style>
            body {
                background-color: blueviolet;
            }

            h1 {
                text-align: center;
                color: cornsilk;
            }
        </style>
    </head>

<body>
    <h1>Maharaja Multiplex</h1>
    <p>Maharaja Multiplex is a cinema hall located on Chennimalai Road in Erode, Tamil Nadu, featuring multiple
        screens<br>
        and offering a movie-watching experience. While the search results do not provide a narrative "story" of the<br>
        multiplex itself, they describe its physical presence and seating capacity, with one source mentioning its<br>
        location along the Coimbatore-Erode route and another detailing the seating arrangement of its screens.<br>
    </p>
<img src="maharajamultiplex.jpg.webp" style="width: 300pt; height: auto; alt: error;">

</body>  
</html>

turmeric.html
<html>

<head>
    <style>
        body {
            background-color: darkgray;
        }
    </style>
</head>

<body>
    <p>Erode turmeric, also known as "Erodu Manjal," is a type of turmeric cultivated in <br>the Erode region of Tamil
        Nadu, India, recognized by the government as a Geographical Indication (GI) for its distinct quality. <br>It is
        prized for its high curcumin content, deep yellow color, and aromatic qualities, making it a significant
        agricultural commodity and identity for the city, which is often called the "Yellow City" or "Turmeric City".

    </p>
    <img src="turmeric.jpg.jpg" style="width: 300pt; height: auto; alt: error;">

</body>

</html>
```


## OUTPUT
![alt text](<Screenshot (28).png>)
![alt text](<Screenshot (29).png>)
![alt text](<Screenshot (30).png>)
![alt text](<Screenshot (31).png>) 
![alt text](<Screenshot (27).png>)
![alt text](<Screenshot (24).png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
