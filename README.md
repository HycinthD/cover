# Ex.06 Book Front Cover Page Design
## Date:29.11.2023

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
        <title>
            Front cover page
        </title>
        <style>
            .bookpage{
                height:700px;
                width:500px;
                margin-left:35%;
                background-image:url(img.jpeg);
                padding:10px;
                background-size: cover;
            }
            .hr1{
                width:200px

            }
            .booktitle{
                margin-top: 30px;
                color:blue;
                padding:5px;
                font-size: xx-large;
            }
            .subtitle{
                color:blueviolet;
                font-size: large;
            }
            .mypic{
                position: relative;
                top:90px;
                left:390px;
                height: 80px;
                width: 90px;
            }
            .hr2{
                padding-top: 130px;
            
            }
            *{
                color:whitesmoke;
            }
            .ed{
                position:relative;
                top: 110px;
            }
            .author{
                font-family: 'Trebuchet MS';
                font-size: large;
            }
            .pb{
                position: relative;
                left:420px;
                top:-40px;
                font-size: x-large;
            }
        </style>
        <body>
            <div class="bookpage">
            <div style="color:blueviolet">INSIGHT </div>
            <div class="hr1"><hr ></div>
            <div class="booktitle"><h1>INDUSTRIES IN MACHINE LEARNING</h1></div>
            <div class="subtitle">API to launch a transcription job<br>using latest HTML5 and CSS</div>
            <div class="mypic"><img src="Hycinth D.png" height="140px" ></div>
            <div class="ed">SPECIAL EDITION</div>
            <div class="hr2"><hr ></div>
            <div class="author"> HYCINTH</div>
            <div class="pb"> <h2>SEC</h2></div>
        </div>
        </body>
    </head>
</html>
```

## OUTPUT:
![Alt text](<Screenshot (56).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
