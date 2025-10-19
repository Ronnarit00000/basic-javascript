## Javascript Let

---

   The `let` keyword was introduced ES6 (2015)
   Variables declared with `let` have Block scope
   Variables declared with `let` must be Declared before use
   Variables declared with `let` cannot be Redeclared in the same scope

---

### Block scope

Before ES6 (2015), javascript did not have Block scope.
Javascript global scope and function scope.
ES6 introduced the two new javascript keywords: `let` and `const`.
These two keywords provided block scope in javascript:

***Example***

```
   {
      let x = 2;
   }

   // x can NOT be used here
```

### Global scope

Variables declared with the `var` always have Global scope.
Variables declared with the `var` keyword can NOT have block scope:

***Example***
variables declared with `var` inside a {} block can be accessed from outside the block: 

```
   {
      var x = 2;
   }

   // x can be used here
```

### cannot be redecalred

Variables defined with `let` can not redeclared.
You can not accidentally redelared a variable declared with `let`

with `let` you can not do this:

```
   let x = "John Doe";
   let x = 0;
```

varibles define with var can be redeclared.


with `var` you can do this;

```
   var x = "John Doe";
   var x = 0;
```

### Redeclaring varibles

Redeclaring a variable using the `var` keyword can impose problems.
Redeclaring a variable inside a block will also redeclare the variable outside the block:

***Example***

```
   var x = 10;
   // Here x is 10

   {
      var x = 2;
      // Here x is 2
   }

   // Here x is 2
```

Difference Between var, let and const

|        | scope     | Redeclare | Reassign  | Hoisted   | Binds this   |
|---|---|---|---|---|---|
| var    | NO        | Yes       | Yes       | Yes       | Yes          |
| let    | Yes       | No        | Yes       | No        | No           |
| const  | Yes       | No        | NO        | No        | No           |




