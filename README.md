# Ex.06 Book Front Cover Page Design
## Date:05.12.2024

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> GALAXY OF HOPE: Book Cover</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="book-cover">
        <div class="expert-insight">
            <p>EXPERT INSIGHT</p>
        </div>
        <div class="main-title">
            <h1>LOST IN THE GALAXY OF HOPE</h1>
        </div>
        <div class="subtitle">
            <p>The stars are the streetlights of eternity</p>
        </div>
        <div class="edition-container">
	<div class="edition">
            <p>Second Edition</p>
        </div>
	<img src="my photo.jpg " alt="Edition Icon" class="edition-image">
	</div>
        <div class="author-publisher-container">
        <div class="author">
            <p>Pooja Sri P</p>
        </div>
        <div class="publisher">
            <p>Macmillan</p>
        </div>
    </div>
</body>
</html>


body, html {
    margin: 0;
    padding: 0;
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}


.book-cover {
    width: 400px;
    height: 600px;
    background-image: linear-gradient(rgba(255, 255, 255, 0.5), rgba(255, 255, 255, 0.2)), url('background.png');
    background-size:cover;
    background-position:center;
    color: white;
    padding: 20px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    border-radius: 5px;
    box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.5);
    position: relative;
}


.expert-insight p {
    font-size: 12px;
    font-weight: bold;
    text-transform: uppercase;
    margin: 0;
    color: #ffa500;
    border-bottom: 2px solid #ffa500;
    width: fit-content;
    padding-bottom: 5px;
}


.main-title h1 {
    font-size: 30px;
    font-weight: bold;
    line-height: 1.3;
    margin-top: -100px;
    color: #000;
}


.subtitle p {
    font-size: 18px;
    color: #ffa500;
    margin-top: -130px;
}

.edition-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: absolute;
    bottom: 20px;
    left: 20px;
    right: 20px;
}

.edition p {
    position: absolute;
    bottom: 40px;
    left: 15px;
    color: #ffa500;
    font-size: 18px;
    font-weight: bold;
    margin: 0;
}

.edition-image {
    width: 60px;
    height: auto;
    margin-bottom: 40px;
}


.author-publisher-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 10px;
    border-top: 2px solid #ffa500;
}


.author p {
    font-size: 18px;
    font-weight: bold;
    margin: 0;
    text-align: left;
}


.publisher p {
    font-size: 24px;
    font-weight: bold;
    margin: 0;
    text-align: right;
    color: #fff;
}


````

## OUTPUT:
![alt text](<Screenshot (206).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
