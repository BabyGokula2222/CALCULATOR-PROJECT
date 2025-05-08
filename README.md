# CALCULATOR-PROJECT:
Project 2: Calculator (web application)
* Technologies Used: HTML5, CSS3
* Description:
* Designed and developed a functional web-based calculator using HTML and CSS.
* Created a clean, user interface focusing on basic UX/UI principles such as simplicity, responsiveness, and visual
clarity.
* Implemented structured layout for easy user interaction with buttons for basic arithmetic
operations(Addition,Subtraction,Multiplication,Division).
* Ensured the design was fully responsive and compatible across different screen sizes and browsers.
# HTML CODE:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>CALCULATOR</title>
</head>
<body>
    <div class="container">
        <div class="calculator">
            
            <div class="display-screen">
            <div id="dispaly"></div>
        </div>
        <div class=""></div>
        <div class="buttons">
            <table>
                <tr>
                    <td><button class="btn-operator"id="clear">C</button></td>
                    <td><button class="btn-operator"id="/">&divide;</button></td>
                    <td><button class="btn-operator"id="*>">&times;</button></td>
                    <td><button class="btn-operator"id="backspace"><</button></td>
                </tr>
                <tr>
                    <td><button class="btn-operator"id="7">7</button></td>
                    <td><button class="btn-operator"id="8">8</button></td>
                    <td><button class="btn-operator"id="9">9</button></td>
                    <td><button class="btn-operator"id="-">-</button></td>
                </tr>
                <tr>
                    <td><button class="btn-operator"id="4">4</button></td>
                    <td><button class="btn-operator"id="5">5</button></td>
                    <td><button class="btn-operator"id="6">6</button></td>
                    <td><button class="btn-operator"id="+">+</button></td>
                </tr>
                <tr>
                    <td><button class="btn-operator"id="1">1</button></td>
                    <td><button class="btn-operator"id="2">2</button></td>
                    <td><button class="btn-operator"id="3">3</button></td>
                    <td rowspan="2"><button class="btn-operator" id="equal">=</button></td>
                </tr>
                <tr>
                    <td><button class="btn-operator"id="(">(</button></td>
                    <td><button class="btn-operator"id="0">0</button></td>
                    <td><button class="btn-operator"id=")">)</button></td>
               </tr>
            </table>
        </div>
        </div>
        </div>
  </body>
</html>

# CSS CODE:


*{
    padding: 0;
    margin: 100;
    box-sizing: border-box;
}
body{
    background-color:aqua;
}

.container{
    height: 100vh;
    width: 100vh;

    display: grid;
    place-items: center;
}

    

.calculator{
     height: auto;
     width: auto;
     padding: 20px;
     background-color: white;
     border-radius: 10px;
     box-shadow: 0 0 30px black;
}
#display{
    height: 150px;
    width: auto;
}

button{
    height: 60px;
    width: 60px;
    border: 0;
    margin: 5px;
    font-size:20px;
    cursor:pointer;

}
button#equal{
    height: 130px;
    background-color: darkgray;
    color: black;
}


.calculator button#clear{
    background-color: crimson;
    color: white;
}

.calculator button.btn-operator{
    background-color: black;
    color: white;
}
.calculator button.btn-number{
    background-color: black;
}
