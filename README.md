# Ex04 Places Around Me
# Date:26.10.24
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

<html>
    <head>
        <center>
        <title>Image Mapping</title>
    </center>

   </head>
    <body>
        <img src="gmap.webp" title="sara" alt="Diary" usemap="#mapping">

        <map name="mapping">
            <area shape="circle" coords="164,695,82" title="Circle" href= "sara/mapapp/static/basket.html">
            <area shape="circle" coords="502,963,110" title="Circle" href="sara/mapapp/static/bouquet.html">
            <area shape="poly" coords="908,1039,998,1030,908,1094,988,1095" title="poly" href="sara/mapapp/static/garland.html">




        </map>
    </body>
</html>

basket.html  

<html>
    <body>
        <tr>
       <center>
       <td><img src="flobasket.jpg" style="width:350px;"></td>
       </center>
        <p style="font-size: larger;"> flower basket can be a great gift for a wedding or a birthday – flowers are already in the water and they do not need a vase! Every flower basket tells a unique story, tailored to suit any occasion.
            Therefore, flowers are an essential part of our lives. They are responsible for bringing happiness in our lives and making our surrounding environment a prettier place to live in. Thus, we must all plant flowers at homes and in our neighbourhood to beautify the place and bring happiness and joy for everyone passing by
            They can also be used to hold dried flowers or potpourri, adding a lovely fragrance to any room. In addition to being used for flowers, brass flower baskets can also be used for other decorative purposes. They can be filled with decorative stones or marbles, or used to hold small trinkets or keepsakes.    </p>
    </body>
</html>

bouquet.html

<html>
<body>
    <tr>
<center>
   <td><img src="flobouquet.jpg" style="width:350px;"></td>
</center>
</tr>
<p style= "font-size:larger";> flower bouquet is a collection of flowers in a creative arrangement. Flower bouquets can be arranged
     for the decor of homes or public buildings or may be handheld. Several popular shapes and styles classify handheld bouquets, including nosegay,
    crescent, and cascading bouquets. Flower bouquets are often given for special occasions such as birthdays, anniversaries or funerals. They are also used
    extensively in weddings and at the Olympic Medal Ceremonies. Bouquets arranged in vases or planters for home decor can be placed in traditional or modern styles.
     According to the culture, symbolism may be attached to the types of flowers used.
</p>
</body>
 </html>

garland.html

<html>
    <body>
        <tr>
    <center>
       <td><img src="garimg.webp" style="width:350px;"></td>
    </center>
    </tr>
    <p>Garlands were historically purely secular at first, sought for their fragrance and beauty and used for decorating houses, roads, and streets.[5] It is eventually applied to Hindu deities as an important and traditional role in every festival where these garlands are made using different fragrant flowers (often jasmine) and leaves.[6] Both fragrant and non-fragrant flowers and religiously-significant leaves are used to make garlands to worship Hindu deities.
    </p>
    </body>
 </html>


```
# OUTPut


![Screenshot 2024-12-05 210902](https://github.com/user-attachments/assets/ee5e8df9-594b-4301-9475-c8176fa6ee2e)

![Screenshot 2024-12-05 210930](https://github.com/user-attachments/assets/9914a30e-4c12-4487-aa76-606dd606b624)

![Screenshot 2024-12-05 210942](https://github.com/user-attachments/assets/6dc79fac-7403-4928-85d8-7f89b725d025)

![Screenshot 2024-12-05 210956](https://github.com/user-attachments/assets/491b3c31-3b65-4621-af9f-87104a9d5021)




# RESULT
The program for implementing image maps using HTML is executed successfully.
