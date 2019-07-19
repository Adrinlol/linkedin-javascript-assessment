## LinkedIn JavaScript Assessment
LinkedIn Assessments - JavaScript 2019


## Overview
 #### Answer 15-20 timed, multiple-choice questions

- ~15 minutes duration
- 70th percentile required to pass and get a badge
- Retry in 3 months if you don’t pass

----------------------------------------------------------

### You've written the  event listener shown below for a form button, but  each time you click the button, the page reloads. Which statement would stop this from happening?
```javascript
button.addEventListener('click', function(e) {
  button.className = 'clicked';
}, false);
```

- e.preventDefault();

----------------------------------------------------------


### Which statement references the DOM node created by the code shown?

```
 <p class="pull">Lorem Ipsum </p>
```

- document.querySelector(".pull");

----------------------------------------------------------

### Which statement is the correct way to create a variable called rate and assign it the value 100?

- let rate = 100;

----------------------------------------------------------


### When would the final statement in the code shown be logged to the console?
```javascript
let modal = document.querySelector('#results');
setTimeout(function() {
  modal.classList.remove('hidden');
}, 10000);
console.log('Results shown');
```

- Immediately

----------------------------------------------------------

### Which statement creates a new object using the Person constructor?

-  var student = new Person();

----------------------------------------------------------


### When would you use a conditional statement?


- When you want your code to choose between multiple options.

----------------------------------------------------------

### How is forEach statement different from a for statement?

- A for statement is generic but a forEach statement can be used only with an array.

----------------------------------------------------------

### Review the code below. Which statement calls the addTax function and passes 50 as the argument?

- addTax(50);

----------------------------------------------------------

### What is the result in the console of running the code shown?
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

### How does a function create a closure?

- It returns a reference to a variable in its parent scope.

----------------------------------------------------------

### What is the result in the console of running this code?
```javascript
"use strict";
function logThis() {
  this.desc="logger";
  console.log(this);
}
new logThis();
```

- Function

----------------------------------------------------------

### What is the result of running this statement?
```javascript
console.log(typeof(42));
```

- 'Number'

----------------------------------------------------------











