![Screenshot 2024-12-05 080136](https://github.com/user-attachments/assets/7c4b7d6c-8577-4fb0-ac5e-9f104a5c74e5)# Ex.06 Book Front Cover Page Design
## Date:05/12/24

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
    <title>Web Development Book Cover</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            display: flex;
            justify-content: center;
            align-items:center ;
            height: 100vh;
            background: linear-gradient(135deg, #e2e2e2, #ffffff);
            font-family: 'Arial', sans-serif;
        }

        .book-cover {
            width: 350px;
            height: 500px;
            background: #34495e;
            color: white;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.3);
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .book-title {
            font-size: 26px;
            margin-bottom: 15px;
            font-weight: bold;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5);
        }

        .book-author {
            font-size: 20px;
            margin-bottom: 25px;
            color: #ecf0f1;
        }

        .book-image {
            width: 100%;
            height: 180px;
            background-image: url('book cover page.png');
            background-size: cover;
            background-position: center;
            border-radius: 10px;
            margin-bottom: 20px;
            border: 2px solid #2980b9;
        }

        .book-description {
            font-size: 16px;
            color: #bdc3c7;
            line-height: 1.5;
            margin-bottom: 15px;
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            font-size: 16px;
            color: white;
            background-color: #2980b9;
            border: none;
            border-radius: 5px;
            text-decoration: none;
            transition: background-color 0.3s ease;
        }

        .button:hover {
            background-color: #3498db;
        }

        .footer {
            position: absolute;
            bottom: 10px;
            width: 100%;
            font-size: 12px;
            color: #ecf0f1;
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <div class="book-title">Web Development Essentials</div>
        <div class="book-author">by Jane Smith</div>
        <div class="book-image"></div>
        <div class="book-description">
            Dive into the world of web development with this comprehensive guide, covering HTML, CSS, JavaScript, and more!
        </div>
        <a href="https://www.w3schools.com/whatis/whatis_htmldom.asp" class="button">Get Started</a>
        <center><div class="footer">Published: 2024</div></center>
    </div>
</body>
</html>
```


## OUTPUT:

![Screenshot 2024-12-05 080136](https://github.com/user-attachments/assets/1c50cb93-9feb-45bb-a668-682d56c4ed93)

![Screenshot 2024-12-05 080156](https://github.com/user-attachments/assets/ebe88872-d828-48d5-b2b8-bd0f8b3b86bb)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
