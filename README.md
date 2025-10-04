# Ex.06 Book Front Cover Page Design
## Date:02-10-2025

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
book.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover</title>
  <link rel="stylesheet" href="book.css">
</head>
<body>

  <div class="book-cover">

    <div class="title">
      FUNDAMENTALS OF <br> WEB APPLICATION <br> DEVELOPMENT
    </div>

    <div class="subtitle">
      <h1>DEEP DIVE IN HTML, CSS &amp; JAVASCRIPT BASICS</h1>
      <h2>SPECIAL EDITION FOR LEARNERS</h2>
    </div>

    <div class="author">
      <img src="imagephoto.png" width="100" height="100">
      <h2>SIVAPRASATH B</h2>
      <h2>REF NO: 25016007</h2>
    </div>

  </div>

</body>
</html>

book.css

body {
  font-family: Arial, sans-serif;
  background-color: white;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
}

.book-cover {
  position: relative;
  width: 400px;
  height: 600px;
  border: 2px solid #ccc;
  border-radius: 10px;
  overflow: hidden;
  background-image: url('imagebackground.png');
  background-size: cover;
  background-position: center;
}

.title {
  position: absolute;
  top: 20px;
  left: 20px;
  color: rgb(49, 48, 49);
  font-size: 35px;
  font-weight: bold;
  line-height: 1.2;
}

.subtitle {
  position: absolute;
  top: 150px;
  left: 20px;
  right: 10px;
  color: rgb(239, 186, 210);
}

.subtitle h1 {
  font-size: 18px;
  margin: 0;
}

.subtitle h2 {
  font-size: 14px;
  margin: 5px 0;
}

.author {
  position: absolute;
  bottom: 10px;
  right: 10px;
  color: rgb(5, 237, 12);
  font-size: 13px;
  font-weight: bold;
}

```
## OUTPUT:
![Alt text](<Screenshot 2025-10-04 183631.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
