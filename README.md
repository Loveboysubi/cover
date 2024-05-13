# Ex.06 Book Front Cover Page Design
## Date:28.11.2023

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

<style>
    .bookpage{
        width: 400px;
        height: 600px;
        color:cyan;
        margin-left: auto;
        margin-right: auto;
        padding: 20px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        background-image: url(/static/background.jpeg);
        background-size: cover;
    }
        
    
    .insight{
        color: palegreen;
    
    }
    
    
    .hrstyle{
        width:210px;
    }
    .author{
    
        display: inline;
        position: relative;
        color:bisque;
        top:180px;
        
        font-family:Georgia;
        font-size: medium;
    }
    .booktitle{
        color: palevioletred;
        font-family: 'Courier New', Courier, monospace;
        font-size: larger;
        text-align: center;
        position: relative;
        top: 30px;
    
    }
    .id {
        width:400px;
        position: relative;
        top:190px;
        
    }
    .pub{
        color:red;
        font-size: medium;
        position: relative;
        top:145px;
        left:330px;
    }
    .ed{
        color: yellow;
        font-size: medium;
        font-family: Verdana;
        position:relative;
        top:100px;
    
    }
    .subtitle{
        font-family:Tahoma;
        font-size: large;
        position: relative;
        top:40px;
    }
    .mypic{
        position: relative;
        top: 140px;
        left: 260px;
        width: 100px;
        height: 90px;
        background-size: cover;
    }
    </style>
    <title>Book Cover Page</title>
    </head>
    <body>
    <div class="bookpage">
        <div class="insight">
            HANDS ON  EXPERIENCE WITH
        </div>
        <div class="hrstyle">
            <hr style="color: yellow;">
        </div>
        <div class="booktitle">
            <h1>THE HACKED WORLD ORDER AND CYBER  SECURITY</h1></div>
        <div class="subtitle">
            Hacking is the act of gaining unauthorized access to data in a system or computer. And hands-on experience in identifying and exploiting vulnerabilities in systems and networks.
        </div>
        <div class="mypic">
            <img src="/static/image.jpeg" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: goldenrod;">
        </div>
        <div class="author">
           <p><b>PRIDEESH M</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>Extended Edition</b>
        </div>
    </div>
    </body>

```

## OUTPUT:

![Screenshot 2024-05-13 170054](https://github.com/Loveboysubi/cover/assets/138970879/056f7a2c-4941-4e6d-821b-58c80242f8e0)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
