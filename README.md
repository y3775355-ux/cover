# Ex.05 Book Front Cover Page Design
## Date:

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
<!DOCTYPE html>
<html>
<head>
    <title>Book Cover</title>

    <style>

        body{
            text-align: center;
            background: linear-gradient(to right, #6a5acd, #87cefa);
            font-family: Arial, sans-serif;
        }

        .cover{
            width: 320px;
            height: 520px;
            background-color: #ffb6c1;
            color: white;
            margin: auto;
            margin-top: 30px;
            border: 4px solid blue;
            border-radius: 15px;
            padding: 40px;
            box-shadow: 0px 0px 15px brown;
        }

        img{
            width: 300px;
            height: 220px;
            border-radius: 10px;
            border: 3px solid white;
        }

        h1{
            color:  green;
            letter-spacing: 2px;
        }

        h2{
            color: maroon;
        }

        p{
            font-size: 18px;
            line-height: 1.5;
        }

        hr{
            border: 1px solid white;
        }

    </style>

</head>

<body>

    <div class="cover">

        <img src="C:\Users\Yazhini\Downloads\book.html.jpeg" alt="Book Image">

        <h1>A WORLD OF DREAMS</h1>

        <hr>

        <h3>Written By</h3>

        <h2>YAZHINI K</h2>

        <p>
            A beautiful book about 
            dreams, happiness, and mysteries 
            that inspire every reader.
        </p>

    </div>

</body>
</html>
## OUTPUT:
<img width="1920" height="1080" alt="Screenshot (50)" src="https://github.com/user-attachments/assets/c78c7cea-de49-49a9-b4bd-d0f51e809603" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
