## Javascript Comparison

---
   
   #### Comparison operators

   Comparsion operator are used to compare two values.
   Comparison operators always reurn `true` or `false`.

---

Given that `x = 5`, the table below explains the comparison operators:

| Operator        | Description                          | Comparing       | Return          |
|---|---|---|---|
| ==              | equal to                             | x == 8;         | false           |
|                 |                                      | x == 5;         | true            |
|                 |                                      | x == "5"        | true            |
| ===             | equal value and equal type           | x === 5         | true            |
|                 |                                      | x === "5"       | false           |
| !=              | not equal                            | x != 8          | true            |
| !==             | not equal value or not equal type    | x !== 5         | false           |
|                 |                                      | x !== "5"       | true            |
|                 |                                      | x !== 8         | true            |
| >               | greater than                         | x > 8           | false           |
| <               | less than                            | x < 8           | true            |
| >=              | greater than or equal to             | x >= 8          | false           |
| <=              | less than or equal to                | x <= 8          | true            |

Comparison operators can be used in conditional statements to compare values and take action depending on the result:

```
   if (age < 18) text = "Too young to buy alcohol";
```

### Javascript string comparison

All the comparison operator above can also be used on strings:

***Example***

```
   let text1 = "A";
   let text2 = "B";
   let result = text1 < text2; // true
```
Note that strings are compared alphabetically:

***Example***

```
   let text1 = "20";
   let text2 = "5";
   let result = text1 < text2; // true
```

### Comparing different types

Comparing data of different types may give unexpected result.

When comparing a string with a number, javascript will convert the string to number when doing comparison. An empty string converts to 0. A non-numeric string convertd to `NaN` which is always `false`

| Case         | Value        |
| 2 < 12       | true         | 
| 2 < "12"     | true         | 
| 2 < "john"   | false        | 
| 2 > "john"   | false        | 
| 2 == "john"  | false        | 
| "2" < "12"   | false        | 
| "2" > "12"   | true         | 
| "2" == 12    | false        |

When comparing two string, "2" will be greater then "12".
Alphabetically 1 is less than 21.
To secure a proper result, variable should be to the proper type before comparion:

***Example***

```
   age = Number(age);
   if(isNaN(age)){
      voteable = "Input is not a number";
   }else{
      voteable = (age < 18) ? "Too young" : "Old enough";
   }
```