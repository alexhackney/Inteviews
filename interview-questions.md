# Skill Tests:

## Php

- How do you get information from a form that is submitted using the "get" method?
Using Super Globals

- What is the correct way to create a function in PHP?
With a Function Declaration

- Name a method to output an array?
print_r()

- Which operator is used to check if two values are equal and of same data type?
===

- Which superglobal variable holds information about headers, paths, and script locations?
$_SERVER

- Explain the static keyword in php classes.
The Static keyword makes a function or variables accessible without instantating a class

- What is the commonly used library for database connections?
PDO

- What is the commonly used library for making requests?
CURL is what I think you're looking for. I think Guzzle is becoming the default these days.

- What is php function strlen?
Returns the number of bytes in a string.


## SQL

- With SQL, how do you select a column named "FirstName" from a table named "Persons"?
SELECT FirstName FROM Persons;

- With SQL, how do you select all the columns from a table named "Persons"?
SELECT * FROM Persons;

- With SQL, how do you select all the records from a table named "Persons" where the value of the column "FirstName" is "Peter"?
SELECT * FROM Persons WHERE FirstName = 'Peter';

- With SQL, how do you select all the records from a table named "Persons" where the value of the column "FirstName" starts with an "a"?
SELECT * FROM Persons WHERE FirstName LIKE 'a%';

- With SQL, how do you select all the records from a table named "Persons" where the "FirstName" is "Peter" and the "LastName" is "Jackson"?
SELECT * FROM Persons WHERE FirstName = 'Peter' AND LastName = 'Jackson';

- With SQL, how do you select all the records from a table named "Persons" where the "LastName" is alphabetically between (and including) "Hansen" and "Pettersen"?
SELECT * FROM Persons WHERE LastName BETWEEN 'Hansen' AND 'Pettersen';

- With SQL, how can you return all the records from a table named "Persons" sorted descending by "FirstName"?
SELECT * FROM Persons ORDER BY 'FirstName' DESC;

- With SQL, how can you insert "Olsen" as the "LastName" in the "Persons" table?
INSERT INTO Persons (LastName) VALUES ('Olsen');

- How can you change "Hansen" into "Nilsen" in the "LastName" column in the Persons table?
UPDATE Persons SET LastName = 'Nilsen' WHERE LastName = 'Hansen';

- With SQL, how can you delete the records where the "FirstName" is "Peter" in the Persons Table?
DELETE FROM Persons WHERE FirstName = 'Peter';

- With SQL, how can you return the number of records in the "Persons" table?
SELECT COUNT(*) FROM Persons;

- With SQL, how can you join two related tables together?
With a JOIN Statement or a Pivot Table

## Vanilla Javascript

- How do you create a function in JavaScript?
With a function keyword.

- How do you call a function named "myFunction"?
By invoking it with parenthesis.

- How to write an IF statement in JavaScript?
if (condition) { Code to be executed if true }

- How to write an IF statement for executing some code if "i" is NOT equal to 5?
if (i !== 5) { Code to be executed if true }

- How does a WHILE loop start?
while (condition) { Code to be executed while condition is true }

- How does a FOR loop start?
for (i = 0; i < someNumber; i++) { Code to be executed while i < someNumber }

- How do you round the number 7.25, to the nearest integer?
Math.round(7.25); // 7

- What will the following code return: Boolean(10 > 9)
true

## jQuery

- Can jQuery animate() method can be used to animate ANY CSS property?
No

- Which jQuery method is used to hide selected elements?
hide()

- Which jQuery method is used to perform an asynchronous HTTP request?
ajax()

- Which jQuery method is used to switch between adding/removing one or more classes (for CSS) from selected elements?
toggleClass()

- Look at the following selector: $("div p"). What does it select?
Any p tags that are decendents of a div.

- Look at the following selector: $(":disabled"). What does it select?
Elements that are disabled.


## React

- What is JSX?
Creates an element.

- What triggers a render cycle?
forceUpdate()

- What is a React Hook?
A function that let you hook into functions and components.

- Which method in a React Component should you override to stop the component from updating?
shouldComponentUpdate()

- Which method in a React Component is called after the component is rendered for the first time?
componentDidMount()

- What happens when you call setState() inside render() method?
An infinite loop.