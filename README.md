# Ex.06 Book Front Cover Page Design
## Date:06.05.2025

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

<html>
    <style>
        .box{
            height: 700px;
            width: 500px;
            margin:auto;
            position: relative;
            
        }
        .title{
            font-size: x-large;
            font-weight: 400;
            font-style: italic;
            top:0%;
            left:10%;
            color:rgb(87, 60, 6);
            position: absolute;
            
        }
        .id {
    width:400px;
    position: relative;
                top:180px;
        }


        .caption{
            font-size: x-large;
            font-weight: 900;
            font-style: oblique;
            color:rgb(92, 63, 4);

            top:25%;
            right:22px;
            position:absolute;
        }
        .author{
            
            
           
            right: 0%;
            bottom: 0px;
            position: absolute;
            
           
        }
        .name{
            font-size: large;
            font-weight: 500;
            font-style: initial;
            position: absolute;
            right: 2%;
            bottom :10%;
            color: rgb(172, 120, 16);

        }

        
   
        .bottom-bar {
            position: absolute;
            bottom: 10px;
            left: 20px;
            font-size: medium;
        }
        .publisher, .date {
            display: inline-block;
            margin-right: 10px;
            font-weight: 600;
            color: seashell;

        }
        


    </style>
    <body>
        <div class="box">
            
            <center>
                <img src="death note cover.png" width="100%" height="100%">
            </center>
           
            <div class="title" >
                <h1>DEATH NOTE</h1>
                

            </div>
            

            
            <div class="caption">
                <p>judgment in the dark

                </p>
            </div>
            <hr>
            <div class="name">
                <p>-RAFSHAAN AHMED.A</p>
            </div>
            
            <div class="author">
                <img src="Screenshot 2025-05-07 221741.png" width="85" height="85">
            </div>
    
            <div class="bottom-bar">
                <div class="publisher">Publisher: dream books</div>
                <div class="date">2024</div>
              
            </div>
            
            
            <div class="strip"></div>
        </div>
    
    
    </body>
</html>

```


## OUTPUT:
![alt text](<Screenshot 2025-05-08 151940.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
