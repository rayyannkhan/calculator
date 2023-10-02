# calculator

## This is my first calculator

```javascript
var a, b;
a = prompt("Enter number");
b = prompt("Enter 2nd number");
c = a * b;
d = Number(a) + Number(b);
e = a - b;
f = a / b; 
g = a % b;

function mul() {
  alert("The product of the numbers u entered is " + c);
}

function add() {
  alert("The sum of the numbers u entered is " + d );
}

function sub() {
  alert("The subtraction of the numbers u entered is " + e);
}

function div() {
  alert("The dividion of the numbers u entered is " + f);
}

function perc() {
  alert("The % of the numbers u entered is " + g);
}
```