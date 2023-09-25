<!DOCTYPE html>
<html>
<head>
  <title>3D Lottery Calculator</title>
  <style>
    /* Base CSS */

body {
  font-family: sans-serif;
  background-color: #fff;
  color: #000;
}

h1 {
  font-size: 2rem;
  text-align: center;
}

input,
select,
button {
  width: 100%;
  height: 50px;
  margin-bottom: 10px;
  font-size: 22px;
  border: 1px solid #ccc;
  padding: 10px;
}

button {
  cursor: pointer;
}

.result {
  font-size: 20px;
  font-weight: bold;
  margin-top: 10px;
}

.available-multiplies {
  font-size: 16px;
  margin-bottom: 10px;
}

/* Advanced CSS */

body {
  background-color: #e5f3ff;
}

h1 {
  color: #000;
  text-shadow: none;
  font-size: 3rem;
}

input,
select,
button {
  border-radius: 10px;
  box-shadow: 0 0 10px #ccc;
  width: 390px;
}

button:hover {
  background-color: #007bff;
  border-color: #007bff;
}

.result {
  color: #fff;
  background-color: #000;
  padding: 10px;
  border-radius: 5px;
}

.available-multiplies {
  color: #ccc;
}

/* Onclick animations */

.btn {
  background-color: #fff;
  border-color: #007bff;
  transition: all 0.3s ease-in-out;
}

.btn:hover {
  background-color: #007bff;
  border-color: #007bff;
  color: #fff;
}

.btn:active {
  transform: scale(0.98);
  border-color: #007bff;
}

/* Different shapes */

.btn-rounded {
  border-radius: 50px;
}

.btn-square {
  border-radius: 0;
}

.btn-diamond {
  border-radius: 50% 50% 0 0;
}

  
  </style>
</head>
<body>
  <h1>3D Lottery Calculator</h1>

  <input type="number" placeholder="Number" id="number">
  <select name="round" id="round">
    <option value="O">Original</option>
    <option value="R">Rounded</option>
  </select>
  <input type="number" placeholder="Round Price (Optional)" id="roundPrice">
  <input type="number" placeholder="Lottery Price (Optional)" id="lotteryPrice">

  <div class="available-multiplies">Available multiplies: <span id="available-multiplies"></span></div>

  <button id="calculate">Calculate</button>

  <div class="result" id="result"></div>

  <script>

// Function to calculate the available multiplies.
function calculateAvailableMultiplies(lotteryNumber) {
  const digits = lotteryNumber.split('');
  if (digits[0] === digits[1] && digits[1] === digits[2]) {
    return 0;
  } else if (digits[0] === digits[1] || digits[1] === digits[2] || digits[0] === digits[2]) {
    return 3;
  } else {
    return 6;
  }
}

// Function to calculate the rounded price.
function calculateRoundedPrice(lotteryPrice) {
  return Math.round(lotteryPrice / 100) * 100;
}

// Function to calculate the final answer.
function calculateFinalAnswer(roundedPrice, availableMultiplies, lotteryPrice) {
  if (lotteryPrice === '') {
    return roundedPrice * availableMultiplies;
  } else {
    availableMultiplies -= 1;
    return roundedPrice * availableMultiplies + lotteryPrice;
  }
}

// Calculate button's click event handler.
document.getElementById('calculate').addEventListener('click', function() {
  const lotteryNumber = document.getElementById('number').value;
  const lotteryPrice = document.getElementById('lotteryPrice').value;
  const roundOption = document.getElementById('round').value;
  const roundedPrice = (roundOption === 'R') ? calculateRoundedPrice(lotteryPrice) : lotteryPrice;
  const availableMultiplies = calculateAvailableMultiplies(lotteryNumber);

  // Update the available multiplies box.
  document.getElementById('available-multiplies').innerHTML = availableMultiplies;

  // Calculate the final answer.
  const finalAnswer = calculateFinalAnswer(roundedPrice, availableMultiplies, lotteryPrice);

  // Display the final answer to the user.
  document.getElementById('result').innerHTML = finalAnswer;
});

function calculateFinalAnswer(roundedPrice, availableMultiplies, lotteryPrice) {
  if (lotteryPrice === '') {
    return roundedPrice * availableMultiplies;
  } else {
    availableMultiplies -= 1;
    return availableMultiplies * roundedPrice + lotteryPrice;
  }
}


  </script>
</body>
</html>
