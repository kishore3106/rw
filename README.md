# Ex.07 Restaurant Website
## Date: 07.12.2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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
<html>
    <title>Restaurent Title</title>
    <head>
        <style>
body{
    display: flex ;
    justify-content: center;
    align-items: center;
}
.main{
    width: 99%;
    height: 99%;
    background-color: bisque;
    justify-content: center;
    border: 2px solid black;
    border-radius: 20px;
    background-image: url("img1.jpg");
}
.main h1{
    width: 500px;
    position: relative;
    top: 1px;
    left: 480px;
    border: 1px;
    border-radius: 100px;
    padding: 5px;
    background-color: black;
    color:rgb(230, 234, 238);
    
    font-family: 'Times New Roman', Times, serif;
    font-size:  50px;
}
.home{
    background-color: rgb(4, 4, 19);
    color: aliceblue;
    border: 2px solid black;
    border-radius: 50px;
    width: 90%;
    position: absolute;
    top: 120px;
    left: 70px;
    display: flex;
    justify-content: space-evenly;
}
.h1{
    
    margin: 20px;
    padding: 20px;
    font-family: Georgia, 'Times New Roman', Times, serif;
    font-size: x-large;
}
.contents{
    display: flex;
    align-items: center;
    flex-direction:row;
    justify-content: space-around;
    width: 91%;
    height: 400px;
    position: relative;
    top: 100px;
    left: 60px;
    border: 2px solid rgb(244, 230, 110);
    background-color: rgb(244, 230, 110);
    border-radius: 70px;
}
.m1{
    display: flex;
    
    justify-content: center;
    
    width: 20%;
    height: 90%;
    color: rgb(217, 223, 230,217);
    background-image: url("vig1.jpg");
    background-size: cover;
    background-color: darkblue;
    border: 1px solid darkblue;
    border-radius: 50px;
}
h2{
    
    color: aliceblue;
    border: 1px solid rgb(12, 12, 20);
    background-color: rgb(10, 10, 13);
    width: 90%;
    height: 8%;
    border-radius: 80px;  
}
.m2{
    display: flex;
    justify-content: center;
    width: 20%;
    height: 90%;
    color: aliceblue;
    background-image: url("food.jpeg");
    background-size: cover;
    background-color: darkblue;
    border: 1px solid darkblue;
    border-radius: 50px;
}
.m3{
    display: flex;
    justify-content: center;
    width: 20%;
    height: 90%;
    color: aliceblue;
    background-image: url("food2.jpg");
    background-size: cover;
    background-color: rgb(30, 30, 187);
    border: 1px solid rgb(17, 17, 164);
    border-radius: 50px;
}
.foot{
    border: 2px;
    width: 25%;
    border-radius: 60px;
    background-color: black;
    color: aliceblue;
    position: relative;
    bottom: -250px;
    left: 550px;
}
        </style>
    </head>
    <body>
        <div class="main">
            <h1 align="center">THAMIZH CAM</h1>
            <div class="home">
                <div class="h1"><a href="home.html">Home</a></div>
                <div class="h1"><a href="menu.html">Menu</a></div>
                <div class="h1"><a href="admin.html">Administration</a></div>
                <div class="h1"><a href="cu.html">Contact Us</a></div>
            </div>
            <div class="contents">
                 <div class="m1">
                    <h2 align="center">SPECIAL GUEST</h2>
                    
                 </div>
                 <div class="m2">
                    <h2 align="center">NEW ITEM</h2>
                 </div>
                 <div class="m3">
                    <h2 align="center">DISCOUNTS</h2>
                 </div>
            </div>
            <div class="foot">
                <h3 align="center">Designed and Developed By KISHORE B</h3>
            </div>
        </div>
    </body>
</html>
```

## OUTPUT:
![alt text](output.png)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
