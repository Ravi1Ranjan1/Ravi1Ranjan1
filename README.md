<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>macOS Scientific Calculator</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="calculator">
        <div class="display">
            <p id="output">0</p>
        </div>
        <div class="buttons">
            <button class="function" onclick="appendFunction('(')">(</button>
            <button class="function" onclick="appendFunction(')')">)</button>
            <button class="function" onclick="mc()">mc</button>
            <button class="function" onclick="mPlus()">m+</button>
            <button class="function" onclick="mMinus()">m-</button>
            <button class="function" onclick="mr()">mr</button>
            <button class="function" onclick="appendOperator('C')">C</button>
            <button class="function" onclick="appendFunction('+/-')">+/-</button>
            <button class="function" onclick="appendOperator('%')">%</button>
            <button class="operator" onclick="appendOperator('&#247;')">&#247;</button>
            <button class="function" onclick="appendOperator('2nd')">2nd</button>
            <button class="function" onclick="appendOperator('x^2')">x²</button>
            <button class="function" onclick="appendOperator('x^3')">x³</button>
            <button class="function" onclick="appendOperator('x^y')">x^y</button>
            <button class="function" onclick="appendOperator('e^x')">e^x</button>
            <button class="function" onclick="appendOperator('10^x')">10^x</button>
            <button class="number" onclick="appendNumber('7')">7</button>
            <button class="number" onclick="appendNumber('8')">8</button>
            <button class="number" onclick="appendNumber('9')">9</button>
            <button class="operator" onclick="appendOperator('*')">x</button>
            <button class="function" onclick="appendOperator('1/x')">1/x</button>
            <button class="function" onclick="appendOperator('√x')">√x</button>
            <button class="function" onclick="appendOperator('∛x')">∛x</button>
            <button class="function" onclick="appendOperator('√y')">√y</button>
            <button class="function" onclick="appendOperator('ln')">ln</button>
            <button class="function" onclick="appendOperator('log10')">log10</button>
            <button class="number" onclick="appendNumber('4')">4</button>
            <button class="number" onclick="appendNumber('5')">5</button>
            <button class="number" onclick="appendNumber('6')">6</button>
            <button class="operator" onclick="appendOperator('-')">-</button>
            <button class="function" onclick="appendOperator('x!')">x!</button>
            <button class="function" onclick="appendOperator('sin')">sin</button>
            <button class="function" onclick="appendOperator('cos')">cos</button>
            <button class="function" onclick="appendOperator('tan')">tan</button>
            <button class="function" onclick="appendOperator('e')">e</button>
            <button class="function" onclick="appendOperator('EE')">EE</button>
            <button class="number" onclick="appendNumber('1')">1</button>
            <button class="number" onclick="appendNumber('2')">2</button>
            <button class="number" onclick="appendNumber('3')">3</button>
            <button class="operator" onclick="appendOperator('+')">+</button>
            <button class="function" onclick="appendOperator('Rad')">Rad</button>
            <button class="function" onclick="appendOperator('sinh')">sinh</button>
            <button class="function" onclick="appendOperator('cosh')">cosh</button>
            <button class="function" onclick="appendOperator('tanh')">tanh</button>
            <button class="function" onclick="appendOperator('π')">π</button>
            <button class="function" onclick="appendOperator('Rand')">Rand</button>
            <button class="number" onclick="appendNumber('0')">0</button>
            <button class="number" onclick="appendNumber('.')">.</button>
            <button class="operator" onclick="calculate()">=</button>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
--->
