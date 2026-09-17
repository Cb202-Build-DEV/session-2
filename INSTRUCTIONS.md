# Lab: First JavaScript File

## Instructions

### Setup

- Create an index.html file with a basic HTML skeleton.
- Create an app.js file in the same folder.
- In index.html, link app.js using a <script> tag placed right before the closing </body> tag.

### Build

- In app.js, create a variable for your name using const.
- Create a variable for your age using let.
- Create a boolean variable called isLearningJS and set it to true.
- Use console.log() to print each of your three variables.
- Use console.log() with the typeof operator to print the data type of each variable.

### Test

- Open index.html in the browser and open the Console tab.
- Confirm all three values print with no errors.
- Confirm typeof reports "string", "number", and "boolean" respectively.

### Refine

- Add a one-line comment above each variable explaining why you chose const or let for it.
- Try reassigning your const variable and confirm the console shows a TypeError — then
remove that line.


# Lab: Operators & Expressions

## Instructions

### Setup

- Open your app.js file (or start a new one) and clear out unrelated code.

### Build

- Arithmetic: create variables total and items, calculate their average, and log the result.
- Comparison: create password and confirmPassword variables, use strict equality (===) to
check if they match, and log the boolean result.
- Logical: create boolean variables hasTicket and isGuest, create canEnter that is true if
either is true, and log canEnter.
- Validation: create an age variable and write an expression checking if age is greater than or
equal to 18, then log the result.

### Test
- Run the file and confirm all four console.log() outputs appear with the correct type (number
or boolean).
- Change password so it does not match confirmPassword and confirm the comparison result
flips to false.
- Set both hasTicket and isGuest to false and confirm canEnter becomes false.

### Refine
- Add a comment above each of the four sections naming which operator category it
demonstrates.
- Double-check you used === (strict equality) rather than == throughout.
