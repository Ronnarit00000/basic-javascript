## Javascript Statements

***Example***
```
   let x, y, z; // statement 1
   x = 5;       // statement 2
   y = 6;       // statement 3
   z = x + y    // statement 4
```

#### Javascript Programs

A computer program is a list of "instruction" to be executed by a computer.
These programming instructions are called <b>statements.</b>
Most Javascript programs contain many statements.
The statements are executed one by one in the same order as they are written.

---
   Note
      
      In HTML Javascript programs are executed by the web browser.
---

#### Javascript statements

Javascript statements are composed of:
values, Operators, keywords and comments.
This statement tells the browser to write "Hello Dolly." inside an HTML element with id="demo"

***Example***
``` 
   document.getElementById("demo").innerHTML = "Hello Dolly";
```

---
   Note

      Javascript programs (and Javascript statements) are often called javascript code.
---

#### Semicolons;

Samicolons separate Javascript statemaents.
Add a semicolon at the end of each executable statement:

***Example***
```
   let a, b, c;   // Declare 3 variables
   a = 5;         // Assign the value 5 to a
   b = 6;         // Assign the value 6 to b
   c = a + b      // Assign the sum of a and b to c
```

When separated by semicolons, multiple statements on one line are allowed:

#### Javascript white space

Javascript ignores multiple spaces. You can add white space to your script to make it more readable.
The following lines are equivalent:

***Example***
```   
   let person = "Hege";
   let person="Hege";
```

#### Javascript line length and line breaks

For best readability, programmers often like to avoid code lines longer then 80 characters.
If a Javascript statement does not fit on one line, the best place to break it is after an opreator:

***Example***
```
   document.getElementById("demo).innerHTML = 
   "Hello Dolly";
```

#### Javascript code blocks

Javascript statements can be grouped together in code blocks, inside curly brackets{...}.
The purpose of code blocks is to define statements to be executed together.
One place you will find statement grouped together in blocks, is in Javascrpt functions:

***Example***
```
   function myFunction(){
      document.getElementById("demo").innerHTML = "Hello Dolly";
      document.getElementById("demo").innerHTML = "How are you?";
   }
```

#### Javascript keywords

Javascript statements often start with a keyword to identfy the Javascript action be performed.
Our Reserved Words Reference lista all Javascript keywords.
Here is a list of same of the keywords you will learn about in this tutorial:

| keyword   | Description                                                           |
|---|---|
| var       | Declares a variable                                                   |
| let       | Declares a block variable                                             |
| const     | Declares a block constant                                             |
| if        | Marks a block of statement to be executed on a condition              |
| switch    | Marks a block of statement to be executed in different cases          |
| for       | Marks a block of statement to be executed in a loop                   |
| function  | Declares a function                                                   |
| return    | Exits a function                                                      |
| try       | Implements error handling to a block of statements                    |

---
   Note 
      Javascript keywords are reserved works. Reserved words cannot be uesd as names for variables

---