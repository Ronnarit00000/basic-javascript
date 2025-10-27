## Javascript booleans

---

   #### The Boolean Data Type
   
   In javascript a boolean is a primitive data type that can only have one of two values:

   **true** or **false**
   The Boolean value of an exoression is the basis for javascript comparions and conditions.

---

### Key Boolean Characteristics

- true and false are **boolean data types**
- **true and false** are the only possible boolean value
- true and false must be writen in **lowercase**
- true and false must be writen **without quotes**

### Boolean Use Cases

Very often, in programming, you will need a data type that can represent one of two value, value:

- yes or no
- on or off
- true or false

Boolean values are faundamental for logical opreations and control flow in javascript programming.

### Comparisons

All Javascript comparison opreator(like ==, !=, <, >) return true or false from the comparison.
Given that `x = 5` the table below explains comparison:

| Description        | Example         | Return       |
|---|---|---|
| Not equal to       | (x == 8)        | false        |
| Unequal to         | (x != 8)        | true         |
| Greater than       | (x > 5)         | false        |
| Less than          | (x < 8)         | true         |

***Example***

```

   let x = 5;

   (x == 8); // equal false
   (x != 8); // equal true

```

### Conditions 

Booleans are extensively used in if statenments to determine the code block to extecute based on the logic.

| Example               | Result          | 
|---|---|
| if(day == "Monday")   | true or false   |
| if(salay > 9000)      | true or false   |
| if(age < 18>)         | true or false   |

***Example***

```

   if (hour < 18){
      greenting = "Good day";
   }else{
      greenting = "Good day"
   }

```

### Loops

Booleans are extensively used in loops to determine codition for looping.

| Description        | Example               |
|---|---|
| For loop           | for(i = 0;i < 5;i++)  |
| While              | while(i < 10)         |
| For in loop        | for (x in person)     |
| For of loop        | for (x of car)        |


***Example***

```
   
   while(i < 10){
      text += i;
      i++;
   }

```

### The Boolean() function

You can use the Boolean() function to fine out if an expression (or varible) is true:

***Example***

```

   Boolean(10 > 9)

```

Or even easier:

```
   
   (10 > 9)

```

