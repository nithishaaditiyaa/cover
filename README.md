# Ex.05 Book Cover Page Design
## Date:

## AIM:
To design a book back cover page using HTML and CSS.

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
nithish_cover.html

<html>
    <head>
        <title>Boosdvsvsbv</title>
        <link rel="stylesheet" type="text/css" href="cover.css">
    </head>
    <body>
        <div class="contain">
            <h1 align="center">About the book</h1>
        </div>
            <hr color="lime" size="5px">
        <br>
        <div class="para">
            <p>
            This book Data structures and algorithms (DSA) are fundamental concepts in computer science used for efficient data management and problem-solving.
            <br>
            <br>
            Python, known for its clear and readable syntax, is an excellent language for implementing and learning DSA, offering both built-in structures and the ability to implement user-defined ones.
            <br>
            <br>
            </p>
        </div>
        <div class="box">
            <p>
                "Any fool can write code that a computer can understand. Good programmers write code that humans can understand."
            </p>
        </div>
        <div class="about">
            <img src="photo.jpeg" align="left" width="100" height="120">
            <p align="right" >
                Mr. Nithish Aaditiyaa is a distinguished technical mentor and author with several years of experience guiding students and engineers in the field of data structures and algorithms.
            </p>
        </div>
        <div class="footer-bar">
        <div class="footer-left">
            <span class="pub-name">R. Nithish Aaditiyaa [25011876]</span><br>
            <span class="printed-text">Printed in India</span>
        </div>
        <div class="footer-right">
            Price: <span class="price-val">₹500</span>
        </div>
    </body>
</html>

cover.css

body
{
    width:400px;
    height: 600px;
    margin-left: auto;
    margin-right:auto;
    padding:20px;
    background-image: url("web.jpg");
    background-repeat: no-repeat;
    background-size: contain;
    background-position: center;

}
.contain
{
    color: crimson;
    padding: 10px;
}
.para
{
    color: aqua
}
.box
{
    border-left: 3px solid yellow;
    border-right: 3px solid yellow;
    border-top: 1px solid yellow;
    border-bottom: 1px solid yellow;
    padding: 15px;
    margin-bottom:10px;
    color: red;
}
.about
{
    margin-top: 20px;
    padding-top: auto;
    border-left: 3px solid blue;
    border-right: 3px solid blue;
    border-top: 1px solid blue;
    border-bottom: 1px solid blue;
    padding: 15px;
    color: red;
}
.footer-bar {
    background-color: #003366; /* Dark blue */
    padding: 15px 25px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-top-left-radius: 15px; /* Matches your screenshot */
    border-top-right-radius: 15px;
    color: white;
}

.pub-name { color: #ffcc00; font-weight: bold; font-size: 18px; }
.printed-text { font-size: 14px; opacity: 0.9; }
.price-val { color: #ffcc00; font-weight: bold; font-size: 18px; }

```
## OUTPUT:
![alt text](<Screenshot (160).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
