# Ex.06 Book Front Cover Page Design
## Date:6/10/2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
in cover.html
<html>
    <head>
        <title>sample</title>
        <link rel="stylesheet" href="cover.css">
    </head>
    <body>
         <div class="imgbg"></div>
         <div class="rectangle"></div>
         <div class="lefttext"><h3><u>SEC insights</u></h3></div>
         <div class="ctext"><h1>MASTER COMPUTER NETWORKS</h1>
         <pre><h1><I>    THINGS U NEED TO KNOW ABOUT CN</I></h1></pre>
       <p><h2>(Top selling book since 2020)</h2></p>
        </div>
          <div class="mypic"></div>
          <div class="hline"></div>
          <div class="edition"><h2>Based on latest Edition</h2></div>
          <div class="created"><h1>Created by</h1>
        <p><h2>Ghufran P (25009482)</h2></p>
        </div>
        <div class="SEC"><h2>SEC</h2></div>
    </body>
</html>

in cover.css

.imgbg{
    background-image: url(bgimage.png);
    background-size: 620px 1000px;
    background-repeat: no-repeat;
    border-style: solid;
    border-color: rgb(16, 192, 192);
    width: 620px;
    height: 870px;
    position: relative;
}
.rectangle {
      width: 540px; 
      height: 780px;
      border: 2px solid white;
      position: absolute;
      top: 55px;
      left: 50px;
    }
.lefttext{
     position: absolute;
     top: 50px;
     left: 55px;
     color: white;
}
.ctext{
    position: absolute;
    top: 30%; 
    left: 3%;
    color: gainsboro;
}
.mypic{
    background-image: url(mypic0.png);
    background-repeat: no-repeat;
    position:absolute;
      top: 580px;
      left: 440px;
      width: 200px;
      height: 200px;
      background-size: 100px;
}
.hline{
    position: absolute;
    width: 540px;
    border: 1px solid darkgray;
    top: 89%;
    left: 50px;
}
.edition{
    position: absolute;
    top: 82%;
    left: 50px;
    color: azure;
}
.created
{
    position:absolute;
    top: 86%;
    left: 50px;
    color: bisque;
}
.SEC{
   position:absolute;
    top: 96%;
    left: 530px;
    color: bisque; 
}
```

## OUTPUT:
![alt text](<Screenshot 2025-10-06 081155.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
