## Javascript Logical Operators

---

   #### Logical Operators

   Logical operators are used to combine boolean expression.
   Logical operators can be used to modify the result of comparisons.
   Typically, you will use a comparsion operator to check a condition, and a logical operator to combine conditions into more complex logic.

---
   
### Javascript Logical operators

Logical operatora are used to determine the between variables or values.
Goven that **x = 6 and y = 3**, the table below explans the logical operators:

| Oper         | Name         | Example                           |
|---|---|---|
| &&           | AND          | (x < 10 && y > 1) is true         |
| `\\`         | OR           | (x === 5 || y === 5) is false     |
| `!`          | NOT          | !(x === y) is true                |

#### Javascript Logical AND

The **&& operator** return `true` if both expressions are `true`, otherwise `false`

***Example***

```

   let x = 6;
   let y = 3;
   let z = (x < 10 && y > 1)

```

#### Javascript Logical OR

The **`||` operator** return `true` if one or both expressions are `true`, otherwise `false`

***Example***

```
   
   let x = 6;
   let y = -3;
   let z = (x > 0 || y > 0);

```

#### Javascript Logical NOT

The NOT operator(!) return `true` for expressions and `false` for **true expression.**

***Example***

```

   let x = (5 == 8); // false
   let y = !(5 == 8); // true

```

#### The Nullish Coalescing Operator(??)

The `??` operator reutrn th right operand when left operand is **nullsh** (`null` or `undefined`), otherwise it returns the left operand.

***Example***

```

   let name = null;
   let text = "missing";
   let result = name ?? text; 

```