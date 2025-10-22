## Javascript Operator

Operator are for Mathemation and Logical computaions

The **Assignments Operator**  `=` assigns values
The **Addition operator**     `+` add values
The **Mutiplication**         `*` multipes values
The **Comparison Operator**   `>` compares values

### Javascript Assignment

The **Asssignment operator `(=)` assigns a value to a variable:

***Example***

```
   let x = 10;
```

```
   // Assign the value 5 to x
   let x = 5;

   // Assign the value 2 to y
   let y = 2;

   // Assign the value x + y to z
   let z = x + y;
```

### Javascript addition

The addition operator `(+)` adds numbers:

***Example***

```
   let x = 5;
   let y = 2;
   let z = x + y;
```

### Javascript Multiplication

The mutiplication operator `(*)` multiplies number:

***Example***

```
   let x = 5;
   let y = 2;
   let z = x * y;
```

### Types of javascript operators

There are differfnt types of javascript operators:
   - Arithmetic operators
   - Assignment operators
   - Comparison operators
   - Logical operators
   - and more ...

### Javascript arithmetic operators

**Arithmetic operators are used to perform arithmetic on numbers:

***Example***

```
   let a = 3;
   let x = (100 + 50) * a;
```

| Operator | Description |
|---|---|
|    +     |   Addition                      |
|    -     |   Subtraction                   |
|    *     |   Mutiplication                 |
|    **    |   Exponention                   |
|    /     |   Division                      |
|    %     |   Modulus (Divison remainder)   |
|    ++    |   Increment                     |
|    --    |   Decrement                     |

### Javascript String addiion

The `+`  can also be used to add (concatenate) string:

***Example***

```
   let text1 = "John";
   let text2 = "Doe";
   let text3 = text1 + " " + text2; // John Doe
```

The `+=` assignment operator can also be used to add (concatenate) strings:

***Example***

let text1 = "What a very "
text1 += "nice day";

// What a very nice day

### Adding string and numbers

Adding two numbers, will return the sum as a number like 5 + 5 = 10.
Adding a number and a string, will return the sum as a concatenated string like 5 + "5" = "55"

***Example***

```
   let x = 5 + 5;          // 5
   let y = "5" + 5;        // 55
   let z = "hello" + 5;    // Hello5
```

### Javascript assignment operators

Assignment operators assign values to javascript variables.
The **Addition assignment operator** `(+=)` adds a value to a variable.

***Example***

```
   let x = 10;
   x += 5;
```

|  Operator |  Example  |  Same As  |
|---|---|---|
| =         | x = y     | x = y     |
| +=        | x += y    | x = x + y |
| -=        | X -= y    | x = x - y |
| *=        | x *= y    | x = x * y |
| /=        | x /= y    | x = x / y |
| %=        | x %= y    | x = x % y |
| **=       | x **= y   | x = x ** y|

### Javascript comparison operators

Comparison operators are used to compare two values.
Comparison operators always return `turn` or `false`.

***Example***

```
   let x = 5;
   let result = x > 8; // true
```

| Operator  |  Description                      | Example   |
|---|---|---|
| ==        | equal to                          | x == 5    |
| ===       | equal value and equal type        | x === 5   |
| !=        | not equal                         | x != 5    |
| !==       | not equal value or not equal type | x !== 5   |
| >         | greater than                      | x > 5     |
| <         | less than                         | x < 5     |
| >=        | greater than or equal to          | x >= 5    |
| <=        | less than or equal to             | x <= 5    |

All the comparison operators above can also be used on strings:

***Example*** 

```
   let text1 = "A";
   let text2 = "B";
   let result = text1 + text2;
```
### Javascript logical operators

| Operator  | Description |
|---|---|
| `&&`       | logical and  |
| `//`       | logical Or   |
| `!`        | logical not  |

