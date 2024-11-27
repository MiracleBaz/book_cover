# Ex.06 Book Front Cover Page Design
# Date:
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BOOK COVER PAGE</title>
    <link rel="stylesheet" href="bcp.css"
    type="text/css">
</head>
<body>
    <div class="book-cover">
        <div class="book-title">
        <hr>   
        <h1><i>the song of ice and fire</i></h1>
        <hr>
    </div>

    <div class="book-tagline">
        <h2>" the fire and blood will decide the fate of the realm"</h2>
    </div>

    <div class="book-author">
    <img src="bcp2.jpg" width="180" height="180">
    <h2>GEORGE RR MARTIN</h2>
    </div>
   
 </div>
</body>
</html>

{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    display: flex;
    align-items: center;
    height: 100vh;
    background-color: rgb(179, 222, 245);
    font-family: Arial, Helvetica, sans-serif;
    justify-content: center;
    font-style: italic;
}
.book-cover{
    width: 800px;
    height: 1000px;
    background-image: url('bcp.jpg');
    background-repeat: no-repeat;
    background-size: 800px 1000px;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    padding: 50px;
    box-shadow: 0 10px 20px rgba(0, 0, 0, 2);
}
.book-tagline h2{
    font-size: 2rem;
    text-align: top;
    font-style: italic;
    margin-top: 30px;
}
.book-title h1{
   font-size: 3.5rem;
   text-align: center;
   text-transform: uppercase;
   font-style: italic;
   letter-spacing: 2px;
   word-spacing: 2px;
   color: ghostwhite;
   text-shadow: 3em; 
   font-family: Georgia, 'Times New Roman', Times, serif;
}
.book-tagline h2{
   font-size: 2.5rem;
   text-align: center;
   font-style: italic;
   margin-top: 30px;
   color: ghostwhite;
}
.book-author div{
   text-align: end;
   font-weight: 400px;
   align-items: end;
}
.book-author h2{
    font-size: 2em;
    font-style: italic;
    color: gainsboro;
}
hr{
    color: mintcream;
    
}
```
# OUTPUT:
![alt text](<../Screenshot 2024-11-27 145703.png>)
# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
