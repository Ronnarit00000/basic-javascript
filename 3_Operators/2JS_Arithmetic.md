## Javascript arithmetic

### Javascript arithmetic operators

Arithmetic operators perform arithmetic on number (lierals or variables).

| Operator     | Description     |
|---|---|
| +            | Addition                 |
| -            | Subtraction              |
| *            | Multiplication           |
| **           | Exponentaion(ES2016)     |
| /            | Divison                  |
| %            | Modulus                  |
| ++           | Increment                |
| --           | Decrement                |

### Arithmetic Operations

A typical arithmetic operation operator on two numbers.
The two numbers can be literals:

***Example***

```
   let x = 100 + 50;
```

or variables:

```
   let x = a + b;
```

or expressions:
```
   let x = (100 + 50) * a;
```

### Operators and Operands

The number (in an arithmetic) are called operands.
The operation (to be performed between the operands) is defined by an **operator**

| Operand | Operator | Operand |
|---|---|---|
| 100     | +        | 50      |

### Adding

The addition operator `(+)` adds numbers:

***Example***

```
   let x = 5;
   let y = 2;
   let z = x + y; // 7
```

### subtracting

The subtraction operator `(-)` subtracts numbers.

***Example***

```
   let x = 5;
   let y = 2;
   let z = x - y; // 3
```

### Multiplying

the multiplication operator `(*)` multiplies numbers.

***Example***

```
   let x = 5;
   let y = 2;
   let z = x * y; // 10
```

### Remainder

The modulus operator `(%)` returns the division remainder.

***Example***

```
   let x = 5;
   let y = 2;
   let z = x % y; // 1
```
### Incramenting

The increment operator `(++)` increments numbers.

***Example***

```
   let x = 5;
   x++;
   let z = x; // 6
```

### Decrementing 

The decrement operator `(--)` decrements numbers.

***Example***

```
   let x = 5;
   x--;
   let z = x; // 4
```

### Exponentiation

The exponentiation operator `(**)` reises the first operand to the power of the second operad.

***Example***

```
   let x = 5;
   let z = x ** 2;
```

x ** y produces the same reult as Math.pow(x,y):

***Example***

```
   let x = 5;
   let z = Math.pow(x, 2);
```

### Operator precedence

Operatioe precednce describes the order in which operations are preformed in an arithmetic pression.

***Example***

```
   let x = 100 + 50 * 3; // 250
```

Is the result of example above the same as 150 * 3, or is it the same as 100 + 150?
Is the addition or the multiplication done first?
As in traditional school mathematics the multiplication is done first.
Multiplication `(*)` and division `(/)` have higher precedence than addition `(+)` and subtraction `(-)`.
And (as in school mathematics) the precedence can be changed by using parenthese.
When using parentheses, the operations inside the parentheses are computed first:

***Example***

```
   let x = (100 + 50) * 3;
```

When many operations have the same precdence (like assition and subtraction or multiplication and divison) they are computed from left to right:

***Example***

```
   let x = 100 + 50 - 3; // 147
```

```
   let x = 100 / 50 * 3 // 6
```