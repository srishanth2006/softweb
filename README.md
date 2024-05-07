# Ex.07 Software Product Company Website
## Date:6-5-24

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
people.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        li{
            display: inline;
            padding: 20px;
            border: 2px rgb(219, 30, 9) solid;
            border-radius: 10px;
            justify-content: center;

           
        }
        li:hover{
            background-color: aqua;
        }
        a{
            text-decoration: none;
        }
        
        .first-div{
            position:absolute;
            top: 0;
            /* bottom: 0; */
            right: 0;
            left: 0;
            border: 10px rgb(75, 94, 101) solid;
            background-color: rgb(236, 115, 16);
        }
        .navbar{
            background-color: rgb(5, 7, 84);
            height: 20%;
            width: 100%;
        }
        ul{
            margin-top: 40px;
            margin-bottom: 80px;
            display: inline-block;
           text-align: left;
           
           
            
        }
        .ja{
            /* display: flex; */
            /* justify-items: center; */
            text-align: center;
            
        }
        
        .heading{
            margin: 10px;
            padding: 10px;
            text-align: center;
                background-color:rgb(6, 12, 80) ;
        }
        .content{
            background-image: url("soft.jpeg");
            background-repeat: no-repeat;
            background-size: cover;
            margin: 10px;
            padding: 10px;
            background-color:rgb(30, 30, 249) ;
        }
        .content h1{
            text-align: center;
        }
        .content h4{
            text-align: center;
        }
       img{
            width: 100px;
            height: 100px;
        }
        #people{
            display: flex;
            /* justify-content: center; */
            align-items: center;
            flex-direction: column;
        }
    </style>
</head>
<body>
    <div class="first-div">
        <nav class="navbar">
            <div class="ja">

            
          <ul style="list-style: none;">
            <li><a href="softewb.html">HOME</a></li>
            <li><a href="product.html">PRODUCT</a></li>
            <li><a href="person.html">PERSON</a></li>
            <li><a href="contact.html">CONTACT</a></li>
    
        </ul>
    </div>
    </nav>
    <div class="heading">
        PEOPLE
    </div>
    <div class="content" style="border: 5px red solid;">
        <h1>BOARD MEMBERS</h1>
        <div id="people">
        <h4 style="color: aliceblue;">Chairman</h4>
        <scan><img src="sri.jpg" alt="chairman"></scan>
        <scan style="color: beige;">SRISHANTH J</scan>
        <h4 style="color: aliceblue;">HEAD EXECUTIVES</h4>
        <scan><img src="rohit.jpeg" alt="cairman"></scan>
        <scan style="color: beige;">ROHIT SHARMA</scan>
        <scan><img src="surya.jpeg" alt="cairman"></scan>
        <scan style="color: beige;">SURYAKUMAR </scan>
    </div>
    </div>
    </div>
</body>
</html>

product.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        li{
            display: inline;
            padding: 20px;
            border: 2px salmon solid;
            border-radius: 10px;
            justify-content: center;

           
        }
        li:hover{
            background-color: aqua;
        }
        a{
            text-decoration: none;
        }
        
        .first-div{
            position:absolute;
            top: 0;
            /* bottom: 0; */
            right: 0;
            left: 0;
            border: 10px rgb(53, 20, 241) solid;
            background-color: yellow;
        }
        .navbar{
            background-color: rgb(6, 15, 89);
            height: 20%;
            width: 100%;
        }
        ul{
            margin-top: 40px;
            margin-bottom: 80px;
            display: inline-block;
           text-align: left;
           
           
            
        }
        .ja{
            /* display: flex; */
            /* justify-items: center; */
            text-align: center;
            
        }
        
        .heading{
            margin: 10px;
            padding: 10px;
            text-align: center;
                background-color:rgb(5, 5, 71) ;
        }
        .content{
            margin: 10px;
            padding: 10px;
            background-color:rgb(36, 36, 119) ;
        }
        .content h1{
            text-align: center;
        }
        .content h2{
            text-align: center;
            color: rgb(209, 212, 30);
        }
        .grid-view{
            display: flex;
            /* justify-content: center; */
            align-items: center;
            flex-direction: column;
        }
        .cl{
            border: 2px saddlebrown solid ;
            margin: 10px;
        }
    </style>
</head>
<body>
    <div class="first-div">
        <nav class="navbar">
            <div class="ja">

            
          <ul style="list-style: none;">
            <li><a href="softewb.html">HOME</a></li>
            <li><a href="product.html">PRODUCT</a></li>
            <li><a href="person.html">PERSON</a></li>
            <li><a href="contact.html">CONTACT</a></li>
    
        </ul>
    </div>
    </nav>
    <div class="heading">
PRODUCT
    </div>
    <div class="content">
        
        <h2> programming languages</h2>
        <div class="grid-view">
           
                <scan class="cl"><img src="c.jpeg" ></scan>
                <scan>C</scan>
         
           
                <scan class="cl"><img src="java.jpeg" alt="chairman"></scan>
                <scan>JAVA</scan>
            
                <scan class="cl"><img src="python.jpeg".png" alt="chairman"></scan>
                <scan>PYTHON</scan>
            
                <scan class="cl"><img src="html.jpeg" alt="chairman"></scan>
                <scan>HTML</scan>
            
        </div>
        
    </div>
    </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        li{
            display: inline;
            padding: 20px;
            border: 2px salmon solid;
            border-radius: 10px;
            justify-content: center;

           
        }
        li:hover{
            background-color: aqua;
        }
        a{
            text-decoration: none;
        }
        
        .first-div{
            position:absolute;
            top: 0;
            bottom: 0;
            right: 0;
            left: 0;
            border: 10px rgb(32, 10, 129) solid;
            background-color: rgb(73, 55, 112);
        }
        .navbar{
            background-color: rgb(6, 16, 97);
            height: 20%;
            width: 100%;
        }
        ul{
            margin-top: 40px;
            display: inline-block;
           text-align: left;
           
           
            
        }
        .ja{
            /* display: flex; */
            /* justify-items: center; */
            text-align: center;
            
        }
        
        .heading{
            margin: 10px;
            padding: 10px;
            text-align: center;
                background-color:rgb(7, 5, 84) ;
        }
        .content{
            margin: 10px;
            padding: 10px;
            background-color:rgb(71, 72, 67) ;
            border: 5px rgb(13, 9, 90) solid;

        }
        .content h1{
            text-align: center;
        }
        .content h4{
            text-align: center;
        }
        .contact-info{
            padding: 20px;
        }
        .contact-info div{
            padding: 10px;
        }
        .contact-info div b{
            padding: 10px;
        }
        
    </style>
</head>
<body>
    <div class="first-div">
        <nav class="navbar">
            <div class="ja">
  
          <ul style="list-style: none;">
            <li><a href="softewb.html">HOME</a></li>
            <li><a href="product.html">PRODUCT</a></li>
            <li><a href="person.html">PERSON</a></li>
            <li><a href="contact.html">CONTACT</a></li>
    
        </ul>
    </div>
    </nav>
    <div class="heading">
    CONTACT US
    </div>
    <div class="content">
        <h1>DETAILS ABOUT US</h1>
        <h4>CONTACT US</h4>
        <div ><b> CONTACT INFORMATION:</b></div>
        <div class="contact-info">
        <div ><b>Address:</b>330/kaiakal street,Thiruvarur</div>
        <div ><b>Landline:</b>140 8904 1353</div>
        <div><b>Phone:</b>9360246488</div>
        <div><b>Email:</b>srishanthcollege@gmail.com</div>
        
        

        

    </div>
    </div>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        li{
            display: inline;
            padding: 20px;
            border: 2px rgb(122, 103, 101) solid;
            border-radius: 10px;
            justify-content: center;

           
        }
        li:hover{
            background-color: #e132d6;
        }
        a{
            text-decoration: none;
        }
        
        .first-div{
            position:absolute;
            top: 0;
            bottom: 0;
            right: 0;
            left: 0;
            border: 10px rgb(20, 166, 224) solid;
            background-color: yellow;
        }
        .navbar{
            background-color: rgb(14, 177, 202);
            height: 20%;
            width: 100%;
        }
        ul{
            margin-top: 40px;
            display: inline-block;
           text-align: left;
           
           
            
        }
        .ja{
            /* display: flex; */
            /* justify-items: center; */
            text-align: center;
            
        }
        
        .heading{
            margin: 10px;
            padding: 10px;
            text-align: center;
                background-color:rgb(129, 209, 31) ;
        }
        .content{
            margin: 10px;
            padding: 10px;
            background-color:rgb(12, 12, 104) ;
        }
        .content h1{
            text-align: center;
        }
        .content h4{
            text-align: center;
        }
        img{
            width: 400px;
            height: 200px;
        }
        .center{
            display: block;
            margin-left: auto;
            margin-right: auto;
            border: 5px rgb(119, 66, 243) solid;

        }
    </style>
</head>
<body>
    <div class="first-div">
        <nav class="navbar">
            <div class="ja">

            
          <ul style="list-style: none;">
            <li><a href="softewb.html">HOME</a></li>
            <li><a href="product.html">PRODUCT</a></li>
            <li><a href="person.html">PERSON</a></li>
            <li><a href="contact.html">CONTACT</a></li>
    
        </ul>
    </div>
    </nav>
    <div class="heading">
        SRISHANTH SOFTWARE DEVELOPING CENTER
    </div>
    <div class="content">
        <h1>MAKING YOUR FUTURE BRIGHT BY SKILLS</h1>
        <h4>OFFICIAL WEBSITE</h4>
        <div>srishanth Software Developing Center is a dynamic hub for software innovation, fostering collaboration and continuous learning. </div>
        <div>With a diverse team of talented individuals, the center excels in crafting elegant solutions to complex challenges. From intuitive user interfaces to scalable systems, srishanth Software Developing Center is dedicated to pushing boundaries and shaping the future of technology with creativity and innovation.</div>
        <div ><img src="software.jpeg" class="center"></div>
    </div>
    </div>
</body>
</html>
```

## OUTPUT:
c:\Users\admin\OneDrive\Pictures\Screenshots\Screenshot 2024-05-06 141044.png
![alt text](<Screenshot 2024-05-06 143810-1.png>)
![alt text](<Screenshot 2024-05-06 143918-1.png>)
 ![alt text](<Screenshot 2024-05-06 143852-1.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
