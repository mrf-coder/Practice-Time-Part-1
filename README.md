# Practice-Time-Part-1
##### Challenge 
Create two variables, firstName and lastName
Concatenate the two variables into a third variable called fullName
Log fullName to the console
```js
let  firstName="Jon"
  let lastName="Doe"
  let fullName=firstName+" "+lastName
  console.log()
```
##### Create a function that logs out "Hi there, Linda!" when called
```js
let name = "Linda"
let greeting = "Hi there"
function meeting(){
    let met=greeting+", "+name+"!"
    console.log(met)
}meeting()
```
Create two functions, add3Points() and remove1Point(), and have them
add/remove points to/from the myPoints variable
Call the functions to that the line below logs out 10
```js
let myPoints = 3
function increment(){
    myPoints+=myPoints
 }
 function decrement(){
    myPoints-=1
 }
 increment()
 increment()
 
 decrement()
 decrement()
console.log(myPoints)
```
##### Try to predict what each of the lines will log out
```js
console.log("2" + 2) // 
console.log(11 + 7) //
console.log(6 + "5") //
console.log("My points: " + 5 + 9) //
console.log(2 + 2) // 
console.log("11" + "14") // 

```
When the user clicks the purchase button, render out
"Something went wrong, please try again" in the paragraph
that has the id="error".
```js
     //<button onclick="purchase()">Purchase - $149</button>

let errorParagraph = document.getElementById("error")
console.log(errorParagraph)

function purchase() {
    console.log("button clicked")
    errorParagraph.textContent = "Something went wrong, please try again"
}
                                          
```
 Create four functions: add(), subtract(), divide(), multiply()
 Call the correct function when the user clicks on one of the buttons
 Perform the given calculation using num1 and num2
 Render the result of the calculation in the paragraph with id="sum-el"
 E.g. if the user clicks on the "Plus" button, you should render
 "Sum: 10" (since 8 + 2 = 10) inside the paragraph with id="sum-el"
 ```js
<html>
    <head>
        <link rel="stylesheet" href="index.css">
    </head>
    <body>
        <span id="num1-el"></span>
        <span id="num2-el"></span>
        <br>
        <button onclick="add()">Add</button>
        <button onclick="subtract()">Subtract</button>
        <button onclick="divide()">Divide</button>
        <button onclick="multiply()">Multiply</button>
        <br>
        <span id="sum-el">Sum: </span>
        <script src="index.js"></script>
    </body>
</html>
```
```js
let num1 = 8
let num2 = 2
document.getElementById("num1-el").textContent = num1
document.getElementById("num2-el").textContent = num2
let sumEl = document.getElementById("sum-el")

function add() {
    let result = num1 + num2
    sumEl.textContent = "Sum: " + result
}

function subtract() {
    let result = num1 - num2
    sumEl.textContent = "Sum: " + result
}

function divide() {
    let result = num1 / num2
    sumEl.textContent = "Sum: " + result
}

function multiply() {
    let result = num1 * num2
    sumEl.textContent = "Sum: " + result
}

```

