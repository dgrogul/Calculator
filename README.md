<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic Calculator</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
    
</head>
<body>
    <div id="calculator">
        <input type="text" id="display" readonly>
        <br>
        <input type="button" value="1" onclick="appendToDisplay('1')">
        <input type="button" value="2" onclick="appendToDisplay('2')">
        <input type="button" value="3" onclick="appendToDisplay('3')">
        <input type="button" value="+" onclick="appendToDisplay('+')">
        <br>
        <input type="button" value="4" onclick="appendToDisplay('4')">
        <input type="button" value="5" onclick="appendToDisplay('5')">
        <input type="button" value="6" onclick="appendToDisplay('6')">
        <input type="button" value="-" onclick="appendToDisplay('-')">
        <br>
        <input type="button" value="7" onclick="appendToDisplay('7')">
        <input type="button" value="8" onclick="appendToDisplay('8')">
        <input type="button" value="9" onclick="appendToDisplay('9')">
        <input type="button" value="*" onclick="appendToDisplay('*')">
        <br>
        <input type="button" value="DEL" onclick="deleteLastChar()">
        <input type="button" value="0" onclick="appendToDisplay('0')">
        <input type="button" value="." onclick="appendToDisplay('.')">  
        <input type="button" value="÷" onclick="appendToDisplay('÷')">
        <input type="button" value="CLEAR" onclick="clearDisplay()">
        <input type="button" value="=" onclick="calculate()">

      
    </div>
    <script src="calc.js"></script>
</body>
</html>
