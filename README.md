# Ex.05 Book Cover Page Design
## Date:15/12/2025

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
cover.html
<html>
    <head>
        <title>Book Cover</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
        <div class="topic">
            <h1>About The Book</h1>
        </div>
        <div>
            <hr class="line">
        </div>
        <div class="para">
           This book <span class="highlight">"Introduction to Data Science"</span> is an easy-to-read, gentle introduction for people with a wide range of backgrounds into the world of data science.It introduces concepts and skills that can help you tackle real-world data analysis challenges. It covers concepts from probability, statistical inference, linear regression, and machine learning. It also helps you develop skills such as R programming, data wrangling, data visualization, predictive algorithm building, file organization with UNIX/Linux shell, and reproducible document preparation.
        </div>
        <div class="quote">
            "You can have data without information, but you cannot have information without data."
        </div>
        <div class="photo">
            <div>
            <img src="My photo.jpeg">
            </div>
           <div class="name"><span class="spanclass">Raaghavi S</span><div>
            Raaghavi S is a writer well-known for their comprehensive educational books with a strong interest in data science, who cover statistics from a conceptual standpoint, focusing on how to use and interpret statistics, rather than the math behind the statistics.
        </div></div>
        </div>
        <div class="details">
            <span class="publisher">SEC Publishers</span>
            <span class="price">Price: &#8377 670</span>
           <span class="print"> Printed in India</span>
         </div>
    </body>
</html>

style.css
body
{
 background: url('bg.jpg') no-repeat top/cover;
 border-radius: 5px;
 background-size:560px 808px;
 border:solid 3px rgb(255, 0, 208);
 width:560px;
 height:805px;
 text-align:justify;
 margin:auto;
}
.topic
{
    color: white;
    padding-top:8px;
    padding-left:20px;
}
.line
{
    background-color:lightgray;
    padding-left:20px;
    height:3px;
    width:500px;
    border:0px;
}
.para
{
    padding-top:10px;
    padding-left:20px;
    padding-right:20px;
    color:rgb(255, 255, 255);
    font-size:18px;
}
.highlight
{
    background-color:rgb(169, 88, 255);
}
.quote
{
    background:linear-gradient( rgb(255, 149, 241),rgb(98, 185, 238));
    font-size:20;
    margin:20px;
    margin-bottom:27px;
    color:rgb(9, 26, 86);
    text-align:center;
    font-weight:bold;
    font-style: italic;
    border-radius: 10px 0px;
    padding:7px;
    border-left: 5px solid rgb(76, 11, 239);
}
.photo img
{
    width:105px;
    height:150px;
    border-radius:3px;
    justify-content:center;
}
.photo
{
    font-family:'Times New Roman', Times, serif;
    background:linear-gradient( rgb(255, 209, 249),rgba(94, 179, 244, 0.679));
    font-size:18;
    padding:10px;
    margin:20px;
    margin-bottom:30px;
    border-radius:10px;
    display:flex;
    gap:3px;
    justify-content:flex-end;
}
.name
{
    padding-left:3px;  
    color:rgb(15, 2, 59);
}
.spanclass
{
    font-weight:bold;
    color: rgb(103, 15, 144);
}
.details
{
    background-color:rgb(198, 165, 238);
    padding:15px;
    margin:20px;
    border-left:solid 5px rgb(76, 11, 239);
    border-radius:10px;
    height:35px;
    color:rgb(15, 49, 137);
    position: relative;
    top:100px;    
}
.publisher
{
    position: relative;
    color:rgb(18, 32, 116);
    font-weight:bold;
    font-size:17px;
}
.price
{
    color:rgb(48, 6, 120);
    position: relative;
    right: -280px;
    bottom: 0px;
    font-weight:bold;
    font-size:17px;
}
.print
{
    position:relative;
    color:rgb(117, 79, 231);
    left: -208px;
    bottom: -20px;
    font-weight:bold; 
    font-size:17px;
}

```

## OUTPUT:
![alt text](<Screenshot (44).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
