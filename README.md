# Ex.05 Design a Website for Server Side Processing
## Date:
14/04/2024

## AIM:
To design a website to find surface area of a Right Cylinder in server side.

## FORMULA:
Surface Area = 2Πrh + 2Πr<sup>2</sup>
<br>r --> Radius of Right Cylinder
<br>h --> Height of Right Cylinder

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        input{
            border-radius: 30px;
            text-align: center;
        }
        body {
            background-color :pink;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            color: navy;

        }
        
    </style>
</head>
<body>
    <script>
        function check(){
            radius=document.getElementById('radius').value;
            height=document.getElementById('height').value;
            result=document.getElementById('result');
            area =  2*(3.14)*radius*height + 2*(3.14)*radius*radius;
            result.value = area;
        }
    </script>
    <center>

        <h1>Surface Area of Cylinder</h1>

        <h2>Radius : <input size="30px" type="text"  name="radius" id="radius" placeholder="Enter the Radius of the cylinder">m <br> <br>
        Height : <input type="text" size="30px" name="height" id="height" placeholder="Enter the Height of the cylinder">m <br><br>
        <button type="button" onclick="check()">AREA</button> <br> <br>
        Output : <input type="text" size="30px" name="result" id="result" placeholder="Output"> m<sup>2</sup></span></h2>
    </center>
</body>
</html>

```



## OUTPUT:
![out1](https://github.com/KGSatheeshKumar/MathServer/assets/128453421/4782c02a-29e6-4510-be1f-28969d3d675f)

![out2](https://github.com/KGSatheeshKumar/MathServer/assets/128453421/4ef70c7c-86e2-4250-975f-b92d9e0f52ed)


## RESULT:
The program for performing server side processing is completed successfully.
