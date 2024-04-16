# Ex.06 Book Front Cover Page Design
## Date:16/04/2024

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
<html>
    <head>
        <title>
            HTML page
        </title>
        <style>
img{
    height: 60%;
    width:25%;
    /* position: absolute;
    left:63%;
    top:64%; */
    float: right;
    /* opacity: 70%; */

}
h1{
    font-size: 400%;
}
p{font-size: 200%;

}       
.container{
    color: rgb(229, 229, 244);
    position: absolute;
    top: 10%;
    left: 30%;
    padding: 25px;
    background-image: url(./background.jpg);
    background-repeat: no-repeat;
    background-size: 100% 100%;
    color: rgb(227, 217, 217);
 
    height: 90%;
    width: 35%;
    background-color: aqua;
}

hr{
    color: orange;
}
.center
{
    height: 35%;
    align-items: flex-end;
    display: flex;
    justify-content: space-between;
    padding: 25px;
}
.details
{
    height: 10%;
    align-items: center;
    display: flex;
    justify-content: space-between;
    padding: 25px;
}
#hr1
{
    width: 20%;
    margin-left: 0.2%;
    color: blue;
}


        </style>
    </head>
<body>
<div class="container">
    <h2> SEC INSIGHT</h2>
    <hr id="hr1">
    <h1>Web Design Playground: HTML & CSS the Interactive Way
    </h1>
    <p> In this project-based book, you'll use a custom online workspace, the book's companion Playground, to design websites, product pages, photo galleries, and more.

    </p>
    <div class ="center">
        <p>
            Second Edition            
        </p>    
        <img src="harshitha.jpg">
    </div>
    <hr>
    <div class="details">
        <p>PRAGAHARSHITHA NC</p>
        <p>SEC</p>
    </div>    
</div>    
</body>
</html>


```

## OUTPUT:
![Screenshot 2024-04-16 113326](https://github.com/pragachellapillai/cover/assets/148254952/d4a90a60-8d4f-4672-9e1f-79bfc17ad085)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
