# Ex04 Places Around Me
## Date:24.05.25

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
p.html

<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Kanchipuram</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Harsheni S (212224040107)</b></font>
</h3>
<center>
<img src="kanchipuram_map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
    <area shape="circle" coords="330,200,20" href="kailasanathar.html" title="Kailasanathar Temple">
    <area shape="circle" coords="450,180,20" href="ekambaranathar.html" title="Ekambaranathar Temple">
    <area shape="circle" coords="820,300,20" href="vaikunta.html" title="Sri Vaikunta Perumal Temple">
    <area shape="circle" coords="190,380,20" href="playarea.html" title="Pranav's Teddy Town play area">
    <area shape="circle" coords="900,500,20" href="prakashsilks.html" title="Prakash Silks and Sarees">
</map>
</center>
</body>
</html>

home.html
<html>
<head>
<title>My Home</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Kanchipuram</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>My Home</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
My home in Kanchipuram is a place filled with warmth, comfort, and love. It's where Ive grown up and created beautiful memories with family. Every corner of it speaks of familiarity and peace, making it my most favorite place in the world.
</font>
</p>
</body>
</html>

kailasanathar temple
<html>
<head><title>Kailasanathar Temple</title></head>
<body bgcolor="beige">
<h1 align="center"><font color="red"><b>Kanchipuram</b></font></h1>
<h3 align="center"><font color="blue"><b>Kailasanathar Temple</b></font></h3>
<hr size="3" color="red">
<p align="justify"><font face="Georgia" size="5">
Kailasanathar Temple is one of the oldest and most remarkable temples in Kanchipuram. Known for its Dravidian architecture and sandstone carvings, it is a must-visit for history and architecture enthusiasts.
</font></p>
</body>
</html>

Ekambranathar temple

<html>
<head><title>Ekambaranathar Temple</title></head>
<body bgcolor="lavender">
<h1 align="center"><font color="red"><b>Kanchipuram</b></font></h1>
<h3 align="center"><font color="blue"><b>Ekambaranathar Temple</b></font></h3>
<hr size="3" color="red">
<p align="justify"><font face="Georgia" size="5">
Ekambaranathar Temple is a massive and significant Shiva temple in Kanchipuram. The temple is known for its tall gopurams, sacred mango tree, and spiritual importance in Tamil Nadu.
</font></p>
</body>
</html>


sri vaikunta perumal temple
<html>
<head><title>Sri Vaikunta Perumal Temple</title></head>
<body bgcolor="aliceblue">
<h1 align="center"><font color="red"><b>Kanchipuram</b></font></h1>
<h3 align="center"><font color="blue"><b>Sri Vaikunta Perumal Temple</b></font></h3>
<hr size="3" color="red">
<p align="justify"><font face="Georgia" size="5">
Sri Vaikunta Perumal Temple is dedicated to Lord Vishnu and features intricate sculptures and a peaceful ambiance. It is a revered religious site and showcases early South Indian temple architecture.
</font></p>
</body>
</html>

pranav's teddy town

<html>
<head><title>Pranav's Teddy Town</title></head>
<body bgcolor="lightyellow">
<h1 align="center"><font color="red"><b>Kanchipuram</b></font></h1>
<h3 align="center"><font color="blue"><b>Pranav's Teddy Town Play Area</b></font></h3>
<hr size="3" color="red">
<p align="justify"><font face="Georgia" size="5">
Pranav's Teddy Town is a fun and safe play area for kids in Kanchipuram. It offers a variety of indoor games and engaging activities, making it a favorite spot for families.
</font></p>
</body>
</html>

prakask silk sarees

<html>
<head><title>Prakash Silks and Sarees</title></head>
<body bgcolor="mintcream">
<h1 align="center"><font color="red"><b>Kanchipuram</b></font></h1>
<h3 align="center"><font color="blue"><b>Prakash Silks and Sarees</b></font></h3>
<hr size="3" color="red">
<p align="justify"><font face="Georgia" size="5">
Prakash Silks and Sarees is a renowned store in Kanchipuram offering a splendid collection of traditional silk sarees. Known for quality and elegance, it is a must-visit for saree lovers.
</font></p>
</body>
</html>
```





## OUTPUT

![Screenshot 2025-05-24 202036](https://github.com/user-attachments/assets/de171b57-cf6c-4c65-8687-c44bd98cfa31)

![Screenshot 2025-05-24 201639](https://github.com/user-attachments/assets/c35a1262-e14a-44c1-9401-42418c643e36)

![image](https://github.com/user-attachments/assets/4f908f12-dd57-4d4c-be31-6067b71e90da)

![image](https://github.com/user-attachments/assets/315bcd69-8b6e-4f22-9188-e4ee640a7cbc)

![image](https://github.com/user-attachments/assets/87295123-7509-4190-80e2-ac4ae9bafa2e)

![image](https://github.com/user-attachments/assets/ef1550f2-fa9b-4da0-baac-629df55c17f1)

![image](https://github.com/user-attachments/assets/72d138a6-313c-4a27-8e32-fffbd115814f)


## RESULT
The program for implementing image maps using HTML is executed successfully.
