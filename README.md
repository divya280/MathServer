# Ex.05 Design a Website for Server Side Processing
## Date: 13.11.2024

## AIM:
 To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side. 


## FORMULA:
P = I<sup>2</sup>R
<br> P --> Power (in watts)
<br> I --> Intensity
<br> R --> Resistance

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

### SERVER.HTML:
```
<html>
    <head>
        <title>Server side processing</title>
        <style>
          body{
             background-color:thistle;
          }
          .box{
              font-style: italic;
              display: inline-block;
              width: 500px;
              min-height: 300px;

          }
          .edge {
            
                width: 100%;
                padding-top: 250px;
                text-align: center;
          }

        </style>
    </head>
    <body>
        <div class="edge">
        <div class="box">
            <h1><b><center>POWER OF A LAMP FILAMENT </center></b></h1>
            <div class="calc">
                  <center>
                    <form method="post">
                      <h2>Intensity : <input type="text" name="Intensity">A</h2>
                    </form>
                    <form method="post">
                      <h2>Resistance : <input type="text" name="Resistance">ohm</h2>
                    </form>          
                    <form>
                        <input type="submit" name="Calculate">
                    </form> 
                  </center>
                </div>
                <div class="ans">
                  <center>
                    <form>
                      <h2>Power :  <input type="text" name="Power">watts</h2>
                    </form>
                  </center>
                </div>   </div>
             
   
    </body>
</html>

```
## HOMEPAGE:
![image](https://github.com/user-attachments/assets/35d29ffd-ff83-4d09-9e75-6a71fe6b0371)


## RESULT:
The program for performing server side processing is completed successfully.
