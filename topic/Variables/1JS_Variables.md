## Javascript variables

---

Variables = Data Containers
<b>Javascript variables</b> are containers for data.
Javascript variables can be declared in 4 ways:

| Modren javascript  | Older javascript                  |
|---|---|
| Using `let`        | Using `var` (Not Recommended)     |                          
| Using `const`      | Automatically (Not Recommended)   |

---

***Example using let***
```
   let x = 5;
   let y = 6;
   let z = x + y;
```

***Example using const***
```
   const x = 5;
   const y = 6;
   const z = x + y;
```

From the examples you can guess:

- x contains (or stores) the value 5
- y contains (or stores) the value 6
- z contains (or stores) the value 11

---

Variables are <b>labels</b> for data values.
Variables are <b>containers</b> for storing data.

---


### Javascript identifiers

variable are identified with <b>unique names</b> called <b>identifiers</b>
Names can be short like x, y, z.
Names can be desscriptive age, sum carName.
The rules for constructing name (identifiers) are:

- Names can <b>contain</b> letters, digis, underscores and dollar signs.
- Names must <b>begin</b> with a letter, a $ sign or an underscore(_).
- Names are <b>case sensitive</b> (X is different from x).
- <b>Reserved words</b> (Javascript keywords) cannot be used as names.

---

Note
   Nummber are not allowed as the first character in names.
   This way javascript can easily distinguish identifiers from numbers.

---


### Javascript Underscore(_)

Javascript trats underscore as letter.
Identifiers containing _ are vaild variable names:

***Example***
```
   let _lastName = "Johnson";
   let _x = 2;
   let _100 = 5;
```

A convention among professional programmers is to start a name with underscore for "private" variables.


### Javascript Dollar sign $

Javascript aslo treats a dollar sign as a letter.
Identifiers containing $ are valid variable names:

***Example***
```
   let $ = "Hello world";
   let $$$ = 2;
   let $myMoney = 5;
```

Uning the $ is not very common in javascript, but professional programmers often use it as an alias for the main function in javascript libraries.


### Declaring javascript variables

<b>Create a varible</b> in javascript is called <b>declaring</b> a variable.
You declare a javascript variable with the `let` keywork or the `const` keyword.


### Declareing a varible Using <b>let</b>

```
   let carName;
```

After the declaration, the varible has no value (technically it is undefined).
To `assign` a value to the variable, use the equal sign:

```
   carName = "Volvo";
```

Most often you will assign a value to the variable when you declare it:

***Example***

Create a variable called carName and assign the value "volvo" to it:

```
   let carName = "volvo";
```


### Declareing a variable using <b>const</b>

Always use `const` if the value should not be changed

```
   const carName = "Volvo";
```

***A Mixed Example***

```
   const price1 = 5;
   const price2 = 6;
   let total = price1 + price2;
```

The two variable <b>price1</b> and <b>price2</b> are declared with the `const` keyword.
The values of price1 and price2 cannot be changed.
The variable `total` is declared with the `let` keyword.
The value of total can be changed.

### Declareing a variable automatically

Undeclared variable are <b>automatically declaredlet</b> when first used:

***Exaple (Not Recommended)***

```
   x = 5;
   y = 6;
   z = x + y;

   // it's a good programming practice to decalre all variables at the deginning of script.
```

### Declaring a variable using <b>var</b>

The `var` keyword was used in javascript code defore 2015.
The `let` and `const` keywords were new to javascript in 2015.

***Using var (Not Recommended)***

```
   var x = 5;
   var y = 6;
   var z = x + y;
```

---

##### when to use var, let or const?

   1. Always declare varibles
   2. Always use `const` if the value should not be changed.
   3. Always Use `const` if type should not be changed (Arrays and Objects).
   4. Only use `let` if you cannot use `const`
   5. Never use `var` if you can use let or const

---

### Javascript Data types

Javascript variables can hold 8 <b>datatypes,</b> but for now just think of numbers and strings.
<b>String</b> are text written <b>inside quotes.</b>
<b>Number</b> are written <b>without quotes.</b>
If you put a number in quotes, ite will be treated as a text string.

***Example***

```
   const pi = 3.14;
   let person = "John Doe";
   let answer = 'Yes I am';
```

One statement, Many variables

You can declare many variable in one statement.
Start the statement with `let` to `const and separate the varibles by comma:

Example
```
   let person = "John Doe", carName = "Volvo", price = 200;
```

### The assignment opreator

In javascript, the equal sign (=) is an <b>assignment</b> operator, not an <b>equal to operator.</b>
This is different from algebra. The following does not make sense in algebra:

```
   x = x + 5
```

In javascript, howerver, it makers perfect sense: it assigns the value of x + 5 to x.
(lt calculates the value of x + 5 and put the result into x. The value of x is incremented by 5.)

---

   Note
      The equal to operator is written like == in javascript.

---

