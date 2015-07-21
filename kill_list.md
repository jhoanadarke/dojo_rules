Kill List
=========
* <i>snap</i>
* <span></span><font></font>nice!
* <p>this is a code block</p><p>this is a code block</p><p>this is a code block</p> 
* var 1person  = william
* Functions with side effects
<!--  this is unused code  -->
var makeNoise = function() {
  console.log("Pling!");
};

makeNoise();
// → Pling!

var power = function(base, exponent) {
  var result = 1;
  for (var count = 0; count < exponent; count++)
    result *= base;
  return result;
};

console.log(power(2, 10));
// → 1024
