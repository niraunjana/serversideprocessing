# Design a Website for Server Side Processing

## AIM:
To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:

### Step 1:


Create a new Django project using "django-admin startproject",get into the project terminal and use
"python3 manage.py startapp" command.

### Step 2:


Define urls.py and views.py for the website .Allow host access and add the app name under installed
apps in settings.py




### Step 3:
Create a templates folder under the app folder followed by a folder under templates with the app
name followed by html file named perimeter.html



### Step 4:
Write HTML and CSS code in the file save it and run the app using python manage.py
makemigrations and python manage.py migrate commands .Run the Server using "python3
manage.py runserver 0:80" command.




### Step 5:

The Website is published. Provide user inputs. The server processes the inputs in the terminal and
provides output in the client side. The server side processing can be views in the terminal.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```
<html>
<head>
<meta charset='utf-8'>
<meta http-equiv='X-UA-Compatible' content='IE=edge'>
<title>Perimeter of Rectangle</title>
<meta name='viewport' content='width=device-width, initial-scale=1'>
<style type="text/css">
body 
{
background-color:purple;
}
.edge {
width: 1060px;
margin-left: auto;
margin-right: auto;
padding-top: 300px;
padding-left: 200px;
}
.box {
display:block;
border: Thick dashed lime;
width: 300px;
min-height: 200px;
font-size: 30px;
background-color: purple;
}
.formelt{
color: yellow;
text-align: center;
margin-top: 10px;
margin-bottom: 5px;
}
h1
{
color: yellow;
text-align: center;
padding-top: 30px;
}
</style>
</head>
<body>
<div class="edge">
<div class="box">
<h1>Perimeter of a Rectangle</h1>
<form method="POST">
{% csrf_token %}
<div class="formelt">
Length : <input type="text" name="length" value="{{l}}"></input>(in m)<br/>
</div>
<div class="formelt">
Breadth : <input type="text" name="breadth" value="{{b}}"></input>(in m)<br/>
</div>
<div class="formelt">
<input type="submit" value="Calculate"></input><br/>
</div>
<div class="formelt">
Perimeter : <input type="text" name="area" value="{{Perimeter}}"></input>m<sup>2</sup><br/>
</div>
</form>
</div>
</div>
</body>
</html>
```



## OUTPUT:
![WhatsApp Image 2023-01-25 at 12 00 17](https://user-images.githubusercontent.com/119395610/214502552-38c6c86d-5975-428f-ba01-95986e063d4b.jpg)



### Home Page:
![WhatsApp Image 2023-01-25 at 12 00 33](https://user-images.githubusercontent.com/119395610/214502506-78d895dc-a66e-47fb-985b-5b9f102fe9b5.jpg)



## Result:
Server side processing is created successfully.

