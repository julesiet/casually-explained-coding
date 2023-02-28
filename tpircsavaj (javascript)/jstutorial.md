``` javascript
// TURNING PSUEDOCODE INTO JAVASCRIPT (Andrade, Jules-Elvin, Per. 6, 2/26/2023)
// ASSIGNMENT, DISPLAY AND INPUT

// variable assignment (evaluates expression and then assigns a copy of the result to the variable a)
// PSUEDOCODE: a <- expression 

var a = 6; // storing an integer (6 is the expression)
var b = 'six'; // storing a string ('six' is the expression)
var c = true; // storing a boolean value ('true' is the expression)
var d = [6, 'six', true]; // storing a list ('[6, 'six', true]' is the expression)

// displaying values (displays the value of expression, followed by a space)
// PSUEDOCODE: DISPLAY(expression)

console.log(a); // expected output: 6 (a is the expression)
console.log(b); // expected output: 'six' (b is the expression) 

// user input (accepts a value from the user and returns the input value)
// PSUEDOCODE: INPUT()

// prompt the user for an input and store a string
var userInput = prompt('Enter a value!: ');
// IF user inputs 'apple', userInput will store 'apple'
// HOWEVER if user inputs 6, userInput will store '6' (as a string!!)

// prompt the user for an input and store a number
var numberInput = promptNum('Enter a number!: ');
// IF user inputs 6, userInput will store 6 (as an integer!!)
// HOWEVER if user inputs 'six', userInput will return as an error :(

// ARITHMETIC OPERATORS AND NUMERIC PROCEDURES (used to perform arithmetic on a and b)

// 'the order of operations used in mathematics applies when evaluating expressions'
a = 8;
b = 2;
var addition = a + b; // expected input: 10
var subtraction = a - b; // expected input: 6
var multiplication = a * b; // expected input: 16
var division = a / b; // expected input: 4

// modulus operator (returns the remainder after dividing a and b, the mod operator has the same precedence as the * and / operators)
// PSUEDOCODE: a MOD b
var modulus = a % b; // expected input: 0 (no remainder)

// random number generator (returns a random integer between a and b)
// PSUEDOCODE: RANDOM(a, b)
var randomNum = randomNumber(a, b); // any number between 2 and 8

/* RELATIONAL AND BOOLEAN OPERATORS (used to test the relationship between two variables, expressions, or values and can evaluate to a BOOLEAN value)

- 'a = b' checks if a is EQUAL to b
	--> 'a == b' checks if a is equal to b IN A CONDITIONAL STATEMENT
- 'a != b' checks if a is NOT EQUAL to b
- 'a > b' checks if a is GREATER THAN b
- 'a < b' checks if a is LESS THAN b
- 'a >= b' checks if a is GREATER THAN OR EQUAL TO b
- 'a <= b' checks if a is LESS THAN OR EQUAL TO b

*/ 

// NOT operator (evaluates to true if condition is false, otherwise false)
// PSUEDOCODE: NOT condition

if (!(a == b)) { // using the ! operator to reverse the outcome
	console.log('a is not equal to b!');
}

// AND operator (evaluates to true if condition1 and condition2 is true, otherwise false)
// PSUEDOCODE: condition1 AND condition2

if (a == 8 && b == 2) { // uses the && operator to see if both values are true
	console.log('these two values are assigned correctly!');
}

// OR operator (evaluates to true if condition1 OR condition2 is true, if any are true return true, if not false)
// PSUEDOCODE: condition1 OR condition2

if (a == 100 || b == 2) { // uses the || operator to see if one or the other value is true
	console.log('one of these values are true!');
}

// SELECTION
// if statements (the code inside of the brackets execute if the condition in first pair of parantheses is true)
// if... else statements (same as an if statement, but excutes the second pair of parantheses after checking all other conditions)

/* PSUEDOCODE:
IF(condition) {
	<first block of statements>
} ELSE {
	<second block of statements>
}
*/

if (a == b) { // if the conditon a is equal to b is true, console.log will print 'a is equal to b'
	console.log('a is equal to b');
} else { // runs if the first conditional returns as false
	console.log('a is not equal to b :(');
}

// ITERATION
// repeat loop for n number of times (code in parantheses is executed n amount of times)
/* PSUEDOCODE:
REPEAT n TIMES {
	<block of statements>
}
*/

for(var i = 0; i < 5; i++) {
	console.log('hello!');
}
// OR
var j = 0;
while (j < 5) {
	console.log('world!');
	j++;
}

// repeat loop until condition is true (code in parantheses is executed until condition is true) 
/* PSUEDOCODE:
REPEAT UNTIL(condition) {
	<block of statements>
}
*/

var peopleAtMyTable = ['Jules', 'Lindsey', 'Lucas', 'Nadira', 'Omar', 'Makaylee', 'Kyra', 'John'];

for(var i = 0; i < peopleAtMyTable.length; i++) {
	console.log(peopleAtMyTable[i]);
}

// OR
var k = 0;
while (k < peopleAtMyTable.length) {
	console.log(peopleAtMyTable[i]);
	k++;
}

// LIST OPERATIONS

// creating a list (creates a new list that stores value1, value2, value3... (with the first item of the list starting at 1) in aList)
// PSUEDOCODE: aList <- [value1, value2, value3]

var aList = ['one hundred fourty-two', 142, true];
// with index 1 (index 0 in js) being 'one hundred fourty-two', index 2 (index 1 in js) being 142, index 3 (index 2 in js) being true

// PSUEDOCODE: aList <- []
var bList = []; // bList is assigned to be an empty list

// assigning a copy of a list to another variable
// PSUEDOCODE: cList <- aLit
var cList = aList; // cList will have the same contents as aList 

// reference an element with their designated index (in this case, index 'i')
// PSUEDOCODE: aList[i], with first element starting at 1

console.log(aList[i]); // same notation, but first element starts at 0

// assign an index from a list to a variable
// PSUEDOCODE: x <- aList[i]

var x = aList[i] // assigns index 'i' from aList to x 

// assign a variable to an index of a list 
// PSUEDOCODE: aList[i] <- x

x = 'this is actually not one hundred fourty-two';
aList[0] = x;

// assign an index to another index in the same list
// PSUEDOCODE: aList[i] <- aList[j]

aList[0] = aList[1];

// 'insert' keyword in lists (any values in aList at indices greater than or equal to 1 are shifted one position to the right, length of list is increased by 1, and value is placed at index i in aList)
// PSUEDOCODE: INSERT(aList, i, value)

insertItem(aList, 0, 'what if this was one hundred fourty-two :)');
// expected input: ["what if this was one hundred fourty-two :)", 142, 142, true]


// 'append' keyword in lists (length of aList is increased by 1, and value is placed at end of aList)
// PSUEDOCODE: APPEND(aList, value)

appendItem(aList, 'these strings are too long :(');
// expected input: ["what if this was one hundred fourty-two :)", 142, 142, true, 'these strings are too long :(']

// 'remove' keyword in lists (removes the item at index i in aList and shifts all values to the left greater than i, length of aList is decreased by 1)
// PSUEDOCODE: REMOVE(aList, i)

removeItem(aList, 4);

// 'length' keyword in lists (returns the total number of elements in aList, not to be confused by index)
// PSUEDOCODE: LENGTH(aList)

console.log(aList.length);

// 'for each' statement OR traversals (using either will traverse a list sequentially/in order until the end of the list) 
/* PSUEDOCODE:
FOR EACH item IN aList {
  <block of statements>
}
*/
// SIDENOTE: there is .forEach keyword in javascript, but i don't know what that means or how to do it, so i'll just use a traversal example :)
for(var i = 0; i < aList.length; i++) {
  console.log(aList[i]);
}
// OR EVEN
var l = 0;
while (l < aList.length) {
  console.log(aList[l]);
  l++;
}

// PROCEDURES AND PROCEDURE CALLS

// procedures/functions declarations (defines procName as a procedure that takes zero or more arguments and runs code inside of first set of brackets when function is called)
/* PSUEDOCODE:
PROCEDURE procName(parameter1, parameter2, ...) {
  <block of statements>
}
*/

function myFunction() {
  console.log('this is a function without any parameters!');
}
// can be called with 'myFunction();'

// procedures/functions declarations with return values (similar to declaring a declaration/function, but IMMEDIATELY returns the value of expression whenever the 'return' keyword is called)
/* PSUEDOCODE:
PROCEDURE procName(parameter1, parameter2, ...) {
  <block of statements>
  RETURN(expression)
}
*/

function myReturnFunction(a, b, c, d) {
  return a + b + c + d;
}
// can be called with 'myReturnFunction(a, b, c, d)' which will return the concatenation of a, b, c, and d

// ROBOT (NOTE: if robot tries to move to square beyond the edge of grid or is not open, it will stay in the same place and terminate the program)
// moving forward (moves one square forward)
// PSUEDOCODE: MOVE_FORWARD()

moveForward(25); // default is 25 pixels

// rotating left and right (turns 90 degress counterclockwise or clockwise, respectively, in place)
// PSUEDOCODE: ROTATE_LEFT() / ROTATE_RIGHT()

turnLeft(90);
turnRight(90);

// 'can move' keyword (evaluates to true if there is at least one open square in the direction the robot if facing)
// PSUEDOCODE: CAN_MOVE(direction), where direction can be left, right, forward or backward)

// there is no specific keyword for 'can move' in app lab, however there may be in other versions or applications within code.org
```
