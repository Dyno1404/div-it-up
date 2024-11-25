Assignment 1:

The Null type is inhabited by exactly one value: null. It can be in the shopping cart as a customer can buy o value or many values
The Boolean type represents a logical entity and is inhabited by two values: true and false. It can be in the shopping cart as to determine whether a customer buyed something from shop or not.
Strings are made up of a list of characters, essentially an array of characters. There is no separate type of characters. A single character is also a string.It can be in the shopping cart as to hold the value of customer nameand product name 
Numbers are always stored in double-precision 64-bit binary format. It can be double , int , float. It can be in the shopping cart as a price tag for each product


Assignment 2:

<h1>JavaScript Functions</h1>
<p>Call a function which performs a calculation and returns the result:</p>
<p id="demo"></p>
<script>
let x = myFunction(4, 3);
document.getElementById("demo").innerHTML = x;
function myFunction(a, b) {
  return a * b;
}
</script>
gives output as 12


In JavaScript, functions are standalone blocks of code that can be called independently, while methods are functions that are associated with and called on objects.


<p>Call a function which performs a calculation and returns the result:</p>
<p id="demo"></p>
<script>
let x = myFunction(4, 3);
document.getElementById("demo").innerHTML = x;
function myFunction(a, b) {
    let c=a*b;
	document.write(c);
}
</script>

gives output as undefined and 12 



Assignment3:

let allStudents = ['A', 'B-', 1, 4, 5, 2];
let studentsWhoPass = [];

for (let grade of allStudents) {
  if (typeof grade === 'number') {
    // First grading system: pass if grade is 3 or higher
    if (grade >= 3) {
      studentsWhoPass.push(grade);
    }
  } else if (typeof grade === 'string') {
    // Second grading system: pass if grade is A, A-, B, B-, or C
    if (['A', 'A-', 'B', 'B-', 'C'].includes(grade)) {
      studentsWhoPass.push(grade);
    }
  }
}

console.log(studentsWhoPass);

function checkAgeWithLogicalOperators(age) {
  let message;
  
  if (age >= 18 && age <= 65) {
    message = "You are an adult.";
  } else if (age > 65) {
    message = "You are a senior citizen.";
  } else {
    message = "You are a minor.";
  }
  
  return message;
}

console.log(checkAgeWithLogicalOperators(20)); // "You are an adult."
console.log(checkAgeWithLogicalOperators(70)); // "You are a senior citizen."
console.log(checkAgeWithLogicalOperators(10)); // "You are a minor."


function checkAgeWithTernary(age) {
  return age >= 18 && age <= 65 
    ? "You are an adult." 
    : age > 65 
    ? "You are a senior citizen." 
    : "You are a minor.";
}

console.log(checkAgeWithTernary(20)); // "You are an adult."
console.log(checkAgeWithTernary(70)); // "You are a senior citizen."
console.log(checkAgeWithTernary(10)); // "You are a minor."



Assignment4:

<body>
  <h1>Every 3rd Number Between 1 and 20</h1>
  <script>
    for (let i = 1; i <= 20; i += 3) {
      console.log(i);
    }
  </script>
</body>


Using for loop
const numbers = [1, 2, 3, 4, 5];
let squared = [];

for (let i = 0; i < numbers.length; i++) {
  squared.push(numbers[i] ** 2);
}

console.log(squared); // [1, 4, 9, 16, 25]


Using for each
const numbers = [1, 2, 3, 4, 5];
let squared = [];

numbers.forEach(num => {
  squared.push(num ** 2);
});

console.log(squared); // [1, 4, 9, 16, 25]

Using for-of loop
const numbers = [1, 2, 3, 4, 5];
let squared = [];

for (const num of numbers) {
  squared.push(num ** 2);
}

console.log(squared); // [1, 4, 9, 16, 25]


Using map

const numbers = [1, 2, 3, 4, 5];
const squared = numbers.map(num => num ** 2);

console.log(squared); // [1, 4, 9, 16, 25]

