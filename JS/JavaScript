var myBtn = document.getElementById('my-button');
var tipElem = document.getElementById("tip");
var totalElem = document.getElementById("total");

myBtn.addEventListener('click', calc);

function calc(e) {
  e.preventDefault();
  var input = document.getElementById('bill');
  var bill = parseFloat(input.value);
  var tip = bill * 0.15;
  var total = bill + tip;
  
  tipElem.textContent = "$"+(tip).toFixed(2);
  totalElem.textContent = "$"+(total).toFixed(2);  
}