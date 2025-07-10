<!DOCTYPE html>
<head>
    <style>
        .red-button{
        
        background: red;
        border:none;
        color:white;
        
        }
        .blue-button{
        background-color: blue;
        border:none;
        color:white;
        }
        .green-button{
        background-color: green;
        border:none;
        color:white;
        
        }
        .click-button{
        
            background-color: orange;
            color:white;
            border:none;
        }
        
        </style>
</head>
<body>
    <button class = "red-button" onclick="alert('good job')">RED Button</button>
    <button class = "blue-button">BLUE Button</button>
    <button class="green-button">Green Button</button>
    
    <button title="tooltip" class="click-button">Click on Button</button>
    <p>Paragraph of text</p></body>
<script>
alert('hello');

</script>
</html>



<!DOCTYPE html>
<html>
<head>
<title>Variables</title>

</head>
<body>

    <script>
let variable1 = 3;
console.log(variable1);


let calculation = variable1 + 2;
console.log(calculation);

let result = calculation + variable1;
console.log(result);

let message = 'hello';
console.log(message);
    </script>
</body>

</html>


