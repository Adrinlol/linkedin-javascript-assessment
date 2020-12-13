## LinkedIn JavaScript Assessment
LinkedIn Assessments - JavaScript 2019-2020


## Overview
 #### Answer 15-20 timed, multiple-choice questions

- ~15 minutes duration
- 70th percentile required to pass and get a badge
- Retry in 3 months if you don’t pass

----------------------------------------------------------

#### Q1. You've written the  event listener shown below for a form button, but  each time you click the button, the page reloads. Which statement would stop this from happening?
```javascript
button.addEventListener('click', function(e) {
  button.className = 'clicked';
}, false);
```

- e.preventDefault();

----------------------------------------------------------

#### Q2. Which statement references the DOM node created by the code shown?

```
 <p class="pull">Lorem Ipsum </p>
```

- document.querySelector(".pull");

----------------------------------------------------------

#### Q3. Which statement is the correct way to create a variable called rate and assign it the value 100?

```javascript
let rate = 100;
```

----------------------------------------------------------

#### Q4. When would the final statement in the code shown be logged to the console?
```javascript
let modal = document.querySelector('#results');
setTimeout(function() {
  modal.classList.remove('hidden');
}, 10000);
console.log('Results shown');
```

- Immediately

----------------------------------------------------------

#### Q5. Which statement creates a new object using the Person constructor?

-  var student = new Person();

----------------------------------------------------------

#### Q6. When would you use a conditional statement?

- When you want your code to choose between multiple options.

----------------------------------------------------------

#### Q7. How is forEach statement different from a for statement?

- A for statement is generic but a forEach statement can be used only with an array.

----------------------------------------------------------

#### Q8. Review the code below. Which statement calls the addTax function and passes 50 as the argument?

```javascript
addTax(50);
```

----------------------------------------------------------

#### Q9. What is the result in the console of running the code shown?
```javascript
var Storm = function () {};
Storm.prototype.precip = 'rain';
var WinterStorm = function () {};
WinterStorm.prototype = new Storm();
WinterStorm.prototype.precip = 'snow';
var bob = new WinterStorm();

console.log(bob.precip);

```

- 'snow'

----------------------------------------------------------

#### Q10. How does a function create a closure?

- It returns a reference to a variable in its parent scope.

----------------------------------------------------------

#### Q11. What is the result in the console of running this code?
```javascript
"use strict";
function logThis() {
  this.desc="logger";
  console.log(this);
}

new logThis();
```

- logThis { desc: 'logger' }

----------------------------------------------------------

#### Q12. What is the result of running this statement?
```javascript
console.log(typeof(42));
```

- 'Number'

----------------------------------------------------------

#### Q13. Which operator returns true if the two compared values are not equal?
 
- !== 

----------------------------------------------------------

#### Q14. How is a forEach statement different from a for statement?

- A for statement is generic, but a forEach statement can be used only with an array

----------------------------------------------------------

#### Q15. Which statement is the correct way to create a variable called rate and assign it the value 100?

```javascript
let rate = 100;
```

----------------------------------------------------------

#### Q16. Which statement creates a new object using the Person constructor?

```javascript
var student = new Person();
```

----------------------------------------------------------

#### Q17. How would you reference the text 'avenue' in the code shown?

```javascript
roadTypes[2]
```

----------------------------------------------------------

#### Q18. Which property references the DOM object that dispatched an event?

- target

----------------------------------------------------------

#### Q19. Which method converts JSON data to a JavaScript object?

```javascript
JSON.parse()
```

----------------------------------------------------------

#### Q20. When would you use a conditional statement?

- When you want your code to choose between multiple options

----------------------------------------------------------

#### Q21. What would be the result in the console of running this code?

```javascript
for(var i=0; i<5; i++){ 
  console.log(i); 
}

```

- 01234 

----------------------------------------------------------

#### Q22. What is the name of a function whose execution can be suspended and resumed at a later point?

- Generator

----------------------------------------------------------

#### Q23. You've written the code shown to log a set of consecutive values, but it instead results in the value 5, 5, 5, and 5 being logged to the console. Which revised version of the code would result in the value 1, 2, 3 and 4 being logged?

```javascript
for (var i=1; i<=4; i++){
   setTimeout(function(){
       console.log(i);
   }, i*10000);
  }

```

- ```for (var i = 1; i <= 4; i++) {{function(j) {setTimeout(function() {console.log(j);}, j * 1000);})(i)};```

----------------------------------------------------------

#### Q24. Which statement creates a new function called discountPrice?

- ```let discountPrice = function(price) { return price * 0.85; };```

----------------------------------------------------------

#### Q25. You need to match a time value such as 12:00:32. Which of the following regular expressions would work for your code?

- /\d\d:\d\d:\d\d/

----------------------------------------------------------

#### Q26. How many prototype objects are in the chain for the following array?

```javascript
let arr = [];

```
- 0

----------------------------------------------------------

#### Q27. Which of the following is not a unary operator?

- instanceof 

----------------------------------------------------------

#### Q28. What type of scope does the end variable have in the code shown?

```javascript
var start = 1;
if (start === 1) {
  let end = 2;
}

```
- block 

----------------------------------------------------------

#### Q29. What will the value of y be in this code:

```javascript
const x = 6 % 2;
const y = x ? 'One': 'Two';

```
- Two 

----------------------------------------------------------

#### Q30. Which keyword is used to create an error?

- throw

----------------------------------------------------------

#### Q31. What's one difference between the async and defer attributes of the HTML script tag?

- The defer attribute will asynchronously load the scripts in order

----------------------------------------------------------

#### Q32. The following program has a problem. What is it?

```javascript
var a;
var b = (a = 3) ? true: false

```
- The condition in the ternary is using the assignment operator. 

----------------------------------------------------------

#### Q33. Which statement references the DOM node created by the code shown?

```javascript
<p class="pull">lorem ipsum</p>

```
- ```document.querySelector('.pull');```

----------------------------------------------------------

#### Q34. What value does the code return?

```javascript
let answer = true;
if (answer === false) {
  return 0;
} else {
  return 10;
}

```
- 10

----------------------------------------------------------

#### Q35. What is the result in the console of running the code shown?

```javascript
var start = 1;
function setEnd() {
  var end = 10;
}
setEnd();
console.log(end);

```
- ReferenceError 

----------------------------------------------------------

#### Q36. What will this code log in the console?

```javascript
function sayHello() {
  console.log("hello");
}

console.log(sayHello.prototype);

```
- undefined  

----------------------------------------------------------

#### Q37. Which collection object allows unique value to be inserted only once?

- Set

----------------------------------------------------------

#### Q38. The following program has a problem. What is it?

```javascript
var a;
var b = (a = 3) ? true: false

```

- The condition in the ternary is using the assignment operator.

----------------------------------------------------------
#### Q39. For the following class, how do you geet value of 42 from `x`?

```javascript

class X{
    get Y(){return 42;}
}
var x = new X();

```

- x.Y

----------------------------------------------------------
#### Q40. What is the result?

```javascript

sum(10,20);
diff(10,20);

function sum(x,y){
  return x+y;
}

let diff = function(x,y){
  return x-y;
}

```

- ReferenceError

----------------------------------------------------------

#### Q41. Which variable is an implicit parameter for every function in JavaScript?

- Arguments
