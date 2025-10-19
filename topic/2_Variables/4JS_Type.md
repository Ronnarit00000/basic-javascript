## Javascript Datatype

### javascript has 8 Datatypes

A javascript variable can hold 8 types of data:

| Type | Description |
|---|---|
| String    | A text of characters endclosed in quotes      |
| Number    | A number representhing a mathematical value   |
| Bigih     | A number representing a large integer         |
| Boolean   | A data type representing true or false        |
| Object    | A collection of key-value pairs of data       |
| Undefined | A primitive variable with no assigned value   |
| Null      | A primitve value representing object absence  |
| Symbol    | A unique and primitive identifier             |

***Example***
```
// string
let color = "Yellow";
let lastName = "Johnson";

// number
let lenght = 16;
let weight = 7.5;

// BigInt
let x = 123456789012345678901234567890n;
let y = BinInt(123456789012345678901234567890);

// Boolean
let x = true;
let y = false;

// Object
const person = {firstName:"John", lastName:"Doe"};

// Array object
const cars = ["Saab", "Volvo", "BMW"];

// Date object
const date = new Date("2022-03-25");

// Undefined
let x;
let y;

// Null
let x = null;
let y = null;

// Symbol
const x = Symbol();
const y = Symbol();

```

### The typeof Operator

You can use the javascript `typeof` operator to find the type of javascript variable.
The typeof operator return the type of a variable or an expression:

***Example***

```
   typeof ""            // return "string"
   typeof "John"        // return "string"
   typeof "John Doe"    // return "string"
```

***Example***

```
   typeof 0             // return "number"
   typeof 314           // return "number"
   typeof 3.14          // return "number"
   typeof (3)           // return "number"
   typeof (3 + 4)       // return "number"
```

### Javascript strings

A string (a text string) is a series of characters like "John Doe".
String are written with quotes. You use single or double quotes:

***Example***

```
   // Using double quotes:
   let carName1 = "Vovlo XC60";

   // Using single quotes:
   let carName2 = 'Vovlo XC60'
```

You can use quotes inside a string, as long they don't match the quotes surrounding the string:

***Example***

```
   // Single quotes inside double quotes:
   let answer1 = "It's alright";

   // Single quotes inside double quotes:
   let answer2 = "He is called 'Johnny'";

   // Single quotes inside double quotes:
   let answer3 = 'He is called "johnny";
```

### javascript Numbers

All javascript numbers are stored as decimal number (floating point).
Number can be written with, or without decimals:

```
   // With decimals
   let x1 = 34.00;

   // Without decimals:
   let x2 = 34;
```

### Exponential notation

Extra large or extra small number can be written with scientfic (exponential) notation:

***Example***

```
   let y = 123e5;       // 12300000
   let z = 123e - 5     // 0.00123
```

### javascript booleans

Javascript booleans can only have one of two value: `true` or `false`
The booleans value of an expression is the basic for javascript comparisons:

| Descrition      | Expression      | return |
|--- | --- | --- |
| Not equal to    |  (x == 8)       | false  |
| unequal to      |  (x != 8)       | true   |
| Greater then    |  (x  > 8)       | false  |
| Less then       |  (x  < 8)       | true   |

### Datatype undefined

In computer programs, variable are often declared without a value can be something that has to be calculated, or something that will be provided later, like user input.

A variable without a value has the datatype `undefined`
A variable without a value also has value `undefined`

***Example***

```
   let carname;
```

### Empty value

An empty value has nothing to do with `undefined`.
An empty value has both a legal value and a type.

***Example***

```
   let car = "";     // The value is "", the typeof is "string"
```

