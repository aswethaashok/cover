# Ex.06 Book Front Cover Page Design
## Date: 3-04-24

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
<html>

<head>
  <title>CN Book Page</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color:rgb(14, 6, 38);
    }

    .book-cover {
      width: 500px;
      height: 700px;
      background-color:black;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
      margin: 50px auto;
      position: relative;
    }
    
    .book-cover .insight {
      position: absolute;
      top: 20px;
      left: 20px;
      font-size: 24px;
      font-weight: bold;
      color: rgb(7, 4, 30);
    }
    .book-cover .line1
    {
      position: absolute;
      top: 40px;
      left: 10px;
      width: 80px;
    }
    .book-cover .title1 {
      position: absolute;
      top: 80px;
      left: 50px;
      font-size: 40px;
      font-weight: bold;
      color:  rgb(19, 5, 61);
    }
    .book-cover .title2 {
      position: absolute;
      top: 130px;
      left: 30px;
      font-size: 40px;
      font-weight: bold;
      color:  rgb(23, 9, 86);
    }

    .book-cover .subtitle1 {
      position: absolute;
      top: 470px;
      left: 20px;
      font-size: 16px;
      font-weight: bold;
      color:  rgb(17, 5, 74);
    }
    .book-cover .subtitle2 {
      position: absolute;
      top: 500px;
      left: 20px;
      font-size: 16px;
      font-weight: bold;
      color: rgb(31, 7, 81);
    }
    .book-cover .subtitle3 {
      position: absolute;
      top: 530px;
      left: 20px;
      font-size: 16px;
      font-weight: bold;
      color: rgb(11, 8, 92);
    }
    .book-cover .line2
    {
      position: absolute;
      top: 480px;
      left: 20px;
      width: 160px;
    }
    .book-cover .line3
    {
      position: absolute;
      bottom:38px;
      left: 20px;
      width: 115px;
    }


    .book-cover .author {
      position: absolute;
      bottom: 25px;
      left: 20px;
      font-size: 18px;
      color: rgb(13, 6, 64);
    }

    .book-cover .number {
      position: absolute;
      bottom: 5px;
      left: 20px;
      font-size: 18px;
      color: rgb(14, 24, 111);
    }

    .book-cover .end {
      position: absolute;
      bottom: 5px;
      right: 50px;
      font-size: 18px;
      color: rgb(96, 80, 155);
    }
    .book-cover .mypic
    {
      position: relative;
      top:550px;
      left: 370px;
      width : 8px;
      height: 8px;
      background-size:fit;
    }


    .book-cover .image {
      width: 100%;
      height: 100%;
      object-fit: cover;
      position: absolute;
      top:  0;
      left: 10;
    }
  </style>
</head>

<body>
  <div class="book-cover">
    <img src="book.png" alt="Book Cover Image" class="image">
    <div class="insight">COMPUTER NETWORKS</div>
    <div class="line1"><hr style="color:blanchedalmond"></div>
    <div class="title1">OSI MODEL </div>
    <div class="title2">  TOPOLOGY AND TCP </div>
    <div class="subtitle1">7'TH EDITION OF OPERATING SYSTEM </div>
    <div class="line2"><hr style="color:blanchedalmond"></div>
    <div class="subtitle2">Unraveling the</div>
    <div class="subtitle3">Secrets of KERNEL Technology</div>
    <div class="line3"><hr style="color:blanchedalmond"></div>
    <div class="mypic"><img src="blswe.jpg" width="120" height="120" ></div>
    <div class="end">SEC</div>
    <div class="number">212223220114</div>

    <div class="author"> SWETHA A</div>

  </div>
</body>
</html>
```

## OUTPUT:

![alt text](<Screenshot 2024-04-07 131720.png>)

![alt text](<swetha/blapp/static/cn book.jpeg>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
