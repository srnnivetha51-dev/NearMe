# Ex03 Places Around Me
## Date: 
29-11-2025
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
map.html
<html>
    <body>
        <h1 align="center"><font color="red">Chennai-Velachery</font></h1>
        <h2  align="center"> <font color="blue">Nivedhitha (25000724)</font></h2>
        <img src="Screenshot 2025-11-26 113301.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="shop" title="shop" href="Instore.html" coords="891,397,1028,436" shape="rect">
    <area target="" alt="hotel" title="hotel" href="nestle.html" coords="1048,547,96" shape="circle">
    <area target="" alt="westein" title="westein" href="westein.html" coords="1037,239,949,276,947,329,1135,337,1141,265" shape="poly">
    <area target="" alt="grocery" title="grocery" href="dmart.html" coords="1123,728,1030,750,1030,837,1108,852,1245,811,1229,749" shape="poly">
    <area target="" alt="Fashion" title="Fashion" href="maybell.html" coords="1390,82,1422,39,1556,41,1600,80,1569,115,1417,115" shape="poly">
</map>
    </body>
</html>

Instore.html
<html>
    <body bgcolor="purple">
        <h1 align="center">Chennai-Velachery</h1>
        <br>
        <h2 align="center">S.R.NIVEDHITHA (25000724)</h2>
        <hr>
        <h2 align="center">INSTORE</h2>
        <h3>Instore, Anna nagarInstore is a women's fashion brand founded in 2005 that offers affordable, designer, and sustainable clothing, including kurtis, ethnic wear, and children's fashion.</h3>
    </body>
</html>

nestle.html
<html>
     <body bgcolor="lightblue">
        <h1 align="center">Chennai-Velachery</h1>
        <br>
        <h2 align="center">S.R.NIVEDHITHA (25000724)</h2>
        <hr>
        <h2 align="center">Nestle</h2>
        <h3>Nestlé is the world's largest food and beverage company, headquartered in Vevey, Switzerland, with a purpose of "unlocking the power of food to enhance quality of life for everyone, today and for generations to come"</h3>
    </body>
</html>

westein.html
<html>
     <body bgcolor="lightblue">
        <h1 align="center">Chennai-Velachery</h1>
        <br>
        <h2 align="center">S.R.NIVEDHITHA (25000724)</h2>
        <hr>
        <h2 align="center">Nestle</h2>
        <h3>Nestlé is the world's largest food and beverage company, headquartered in Vevey, Switzerland, with a purpose of "unlocking the power of food to enhance quality of life for everyone, today and for generations to come"</h3>
    </body>
</html>

dmart.html
<html>
     <body bgcolor="cyan">
        <h1 align="center">Chennai-Velachery</h1>
        <br>
        <h2 align="center">S.R.NIVEDHITHA (25000724)</h2>
        <hr>
        <h2 align="center">Dmart</h2>
        <h3>DMart Velachery is a large, multi-floor supermarket offering a wide range of products like groceries, clothing, and home essentials at competitive prices, with ample parking available</h3>

    </body>
</html>

maybell.html
<html>
     <body bgcolor="light green">
        <h1 align="center">Chennai-Velachery</h1>
        <br>
        <h2 align="center">S.R.NIVEDHITHA (25000724)</h2>
        <hr>
        <h2 align="center">MAYBELL</h2>
        
        <h3>Maybell is a women's fashion store in Velachery, Chennai, that offers contemporary and ethnic women's wear like kurtas and skirt sets at affordable prices</h3>

    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2025-11-29 113927.png>)
![alt text](<Screenshot 2025-11-30 110712.png>)
![alt text](<Screenshot 2025-11-30 111059.png>)
![alt text](<Screenshot 2025-11-30 111157.png>)
![alt text](<Screenshot 2025-11-30 110804.png>)
![alt text](<Screenshot 2025-11-30 110952.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
