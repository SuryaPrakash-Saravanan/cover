# Ex.06 Book Front Cover Page Design
## Date:06/10/2025

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
cover.html
<!DOCTYPE html>
<html>
<head>
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-image: url('https://images.unsplash.com/photo-1549887534-4b1f2e6c2f85?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80');
      background-size: cover;
      background-position: center;
      color: black;
      background-color: brown;
    }
    .cover {
      width: 600px;
      height: 850px;
      margin: 40px auto;
      padding: 40px;
      position: relative;
      background: rgba(255, 250, 240, 0.9);
      border: 5px solid black;
      border-radius: 6%;
    }
    .top {
      font-size: 22px;
      font-weight: bold;
      color: gray;
      text-align: left;
      letter-spacing: 2px;
    }
    .title {
      font-size: 38px;
      font-weight: bold;
      text-align: center;
      margin-top: 120px;
      color: brown;
      font-family: 'Times New Roman', serif;
    }
    .subtitle {
      font-size: 20px;
      text-align: center;
      margin-top: 30px;
      font-style: italic;
      color: brown;
    }
    .special {
      font-size: 22px;
      font-weight: bold;
      margin-top: 450px;
      color: brown;
      text-align: left;
    }
    .author {
      font-size: 20px;
      font-weight: bold;
      color: black;
      margin-top: 20px;
      text-align: left;
    }
    .sec {
      position: absolute;
      bottom: 30px;
      right: 20px;
      font-size: 18px;
      color: black;
    }
    .photo {
      width: 100px;
      height: 120px;
      position: absolute;
      bottom: 60px;
      right: 100px;
      border-radius: 8px;
      border: 2px solid brown;
      box-shadow: 0 0 10px black
    }
  </style>
</head>
<body>
  <div class="cover">
    <div class="top">SEC Insights</div>
    
    <div class="title">
      THE FUTURE OF TECHNOLOGY<br>
      INNOVATIONS & BEYOND
    </div>
    
    <div class="subtitle">
      Exploring AI, Web & Emerging Tech<br>
      A guide for 2025 and beyond
    </div>
    
    <div class="special">SPECIAL EDITION</div>
    
    <img src="me.jpg" class="photo" alt="Author Photo">
    
    <div class="author">SURYA PRAKASH S</div>
    <div class="sec">SEC</div>
  </div>
</body>
</html>

```

## OUTPUT:
<img width="1920" height="1080" alt="Screenshot (62)" src="https://github.com/user-attachments/assets/cf490981-e51e-4fd1-b79e-c62ff4a12262" />



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
