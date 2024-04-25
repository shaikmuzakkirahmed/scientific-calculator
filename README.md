# scientific-calculator

#html code

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Scientific Calculator</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="calculator">
    <div class="display">
      <input type="text" id="result" disabled>
    </div>
    <div class="buttons">
      <button class="btn btn-op" onclick="clearDisplay()">AC</button>
      <button class="btn btn-op" onclick="deleteDigit()">DEL</button>
      <button class="btn btn-op" onclick="insertOperator('%')">%</button>
      <button class="btn btn-op" onclick="insertOperator('/')">÷</button>
      <button class="btn btn-num" onclick="insertDigit('7')">7</button>
      <button class="btn btn-num" onclick="insertDigit('8')">8</button>
      <button class="btn btn-num" onclick="insertDigit('9')">9</button>
      <button class="btn btn-op" onclick="insertOperator('*')">×</button>
      <button class="btn btn-num" onclick="insertDigit('4')">4</button>
      <button class="btn btn-num" onclick="insertDigit('5')">5</button>
      <button class="btn btn-num" onclick="insertDigit('6')">6</button>
      <button class="btn btn-op" onclick="insertOperator('-')">-</button>
      <button class="btn btn-num" onclick="insertDigit('1')">1</button>
      <button class="btn btn-num" onclick="insertDigit('2')">2</button>
      <button class="btn btn-num" onclick="insertDigit('3')">3</button>
      <button class="btn btn-op" onclick="insertOperator('+')">+</button>
      <button class="btn btn-num" onclick="insertDigit('0')">0</button>
      <button class="btn btn-num" onclick="insertDigit('.')">.</button>
      <button class="btn btn-op" onclick="calculate('sqrt')">√</button>
      <button class="btn btn-op" onclick="calculate('=')">=</button>
    </div>
  </div>

  <script src="calculator.js"></script>
</body>
</html>
