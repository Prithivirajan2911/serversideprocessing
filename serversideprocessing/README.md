# Design a Website for Server Side Processing

## AIM:
To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:

### Step 1:
Complete the math html according to triarea.


### Step 2:
Insert the code for urls.py in myproj


### Step 3:
Insert the code for views.py in myapp.


### Step 4:
Complete the changes in settings.py in myproj.


### Step 5:
Now run the server


### Step 6:

Publish the website in the given URL.

## PROGRAM :
```
html
<html>
<head>
<meta charset='utf-8'>
<meta http-equiv='X-UA-Compatible' content='IE=edge'>
<title>Area of triangle</title>
<meta name='viewport' content='width=device-width, initial-scale=1'>
<style type="text/css">
body 
{
background-color:cyan;
}
.edge {
width: 1080px;
margin-left: auto;
margin-right: auto;
padding-top: 200px;
padding-left: 300px;
}
.box {
display:block;
border: Thick dashed lime;
width: 500px;
min-height: 300px;
font-size: 20px;
background-color: purple;
}
.formelt{
color: Red;
text-align: center;
margin-top: 5px;
margin-bottom: 5px;
}
h1
{
color: yellow;
text-align: center;
padding-top: 20px;
}
</style>
</head>
<body>
<div class="edge">
<div class="box">
<h1>Area of a triangle</h1>
<form method="POST">
{% csrf_token %}
<div class="formelt">
Height : <input type="text" name="height" value="{{h}}"></input>(in m)<br/>
</div>
<div class="formelt">
Breadth : <input type="text" name="breadth" value="{{b}}"></input>(in m)<br/>
</div>
<div class="formelt">
<input type="submit" value="Calculate"></input><br/>
</div>
<div class="formelt">
Area : <input type="text" name="area" value="{{area}}"></input>m<sup>2</sup><br/>
</div>
</form>
</div>
</div>
</body>
</html>
```

## OUTPUT:
![Alt text](<Screenshot from 2023-12-13 18-39-02.png>)
![Alt text](<Screenshot from 2023-12-13 18-39-21.png>)


### Home Page:


## Result:
THE PROGRAM WAS EXECUTED SUCCESSFULLY.


