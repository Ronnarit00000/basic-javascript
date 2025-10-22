## Javascript Assignment

### Javasscript Assignment Operators

Assignment operators value to javascript variables.
Given that `x = 10` and `y = 5`, the table below explains the assignment operators:

| Operator  | Example   | Same As      | Result       |
|---|---|---|---|
| =         | x = y     | x = y        | x = 5        |
| +=        | x += y    | x = x + y    | x = 15       |
| -=        | x -= y    | x = x - y    | x = 5        |
| *=        | x *= y    | x = x * y    | x = 50       |
| **=       | x **= y   | x = x ** y   | x = 10000    |
| /=        | x /= y    | x = x / y    | x = 2        |
| %=        | x %= y    | x = x % y    | x = 10       |
| :         | x:45      | size.x = 45  | x = 45       |

### Logical Assignment Operators

| Operator  | Example      | Result       |
|---|---|---|
| &&=       | true &&=10   | x = 10       |
| `\\=`     | false `\\=`  | x = 10       |
| ??=       | null ??= 10  | x = 10       |

#### The `=` Operator

The simple assignment operator assigns a simple value to a variable.

***Example***

```
   let x = 10;
```
```
   let x = 10 + y;
```

#### The `+=` Operator

The Addition Assigment operator add a value to a variable.

***Example***

```
   let x = 10;
   x += 5; // 15
```

#### The `-=` Operator
The subtraction assignment operator subtrats value from a variable.

***Example***

```
   let x -= 10;
   x -= 5; // 5
```

#### The `*=` Operator
The Multiplication assignment operator multiplies a variable.

***Example***

```
   let x = 10;
   x *= 5; // 50
```

#### The `**=` Operator

The Exponentiation assignment operator raises a variable to the power of the operand

***Example***

```
   let x = 10;
   x **= 5; // 100000
```

#### The `/=` Operator

The Divison assignment operator divides a variable.

***Example***

```
   let x = 10;
   x /= 5; // 2
```

#### The `%=` Operator

The remainder assignment operator assigns a remainder to a variable.

***Example***

```
   let x = 10;
   x %= 5;
```

#### String assignment

Two assignment operators can assign values to strings:
The **Simple assignment operator** assigns a simple value to string.
The **Addition assignment operator** adds a value to string.

#### The `=` Operator
The **Simple assignment operator** assigns a value to a variable.

***Example***

```
   let text = "Hello";
```

#### The `+=` Operator

The Addition assignment operator can also be used to add strings.

***Example***

```
   let text = "Hello";
   text += " World";
```

#### The `&&=` Operator

The Logical AND assignment operator is used between two values.
If the first value is true, the second value is assigned.

***Example***

```
   let x = true;
   let y = x && = 10;
```
```
   let x = false;
   let y = x &&= 10;
```
```
   let x = 1;
   let y = x && = 10;
```
```
   let x = 0;
   let y = x && = 10;
```
```
   let x = undefined;
   let y = x && = 10;
```
```
   let x = null;
   let y = x && = 10;
```
---

   Note
   The &&= operator is an ES2020 feature

---

#### The `||=` Operator

The **Logical OR assignment operator** is used between two values.
If the first value is false, the second value is assigned.

***Example***

```
   let x = false;
   let y = x || = 10;
```
```
   let x = true;
   let y = x || = 10;
```
```
   let x = null;
   let y = x || = 10;
```
```
   let x = null;
   let y = x || 10;
```
```
   let x = undefinedl
   let y = x || = 10;
```
---

   Note
   The `||=` operator is an ES2020 feature

---

#### The ??= operator

The nullish coalescing assinment opertor is used between two values.
If the first value is undefined or null, the second value is assigned.

***Example***

```
   let x;
   x ??= 10; //10
```
```
   let x = 0;
   x ??= 10; //0
```
```
   let x = null;
   x ??= 10; //10
```
```
   let x = undefined;
   x ??=10; // 10
```
```
   let x = 10;
   let y = 5;
   x ??= y; //10
```
---

   Note
   The `??=` operator is an ES2020 feature

---

#### The Spread `(...)` Operator

The `...` operator split iterables into indivdual elements.

***Example***

```
   let text = "1234"
   let min = Math.min(...text); //1
   let max = Math.max(...text); //4
```