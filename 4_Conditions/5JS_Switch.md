## Javascript switch statement

---

   Switch control flow

   based on a condition, `switch` select one or more **code block to be executed**
   `switch` executes the code block that **matches an expression**.
   `switch` is often used as a more readable alternative to many if...else statements, especially when dealing with multiple possible values.

---

***syntax***

```
   switch(expression){
      case x:
         // code block
         break;
      case y:
         // code block
         break;
      default:
         // code block
   }
```

This is how it works:

- The switch expression is evaluated once.
- The value of the expression is compared with the values of each case.
- If there is a match, the associated block of code is executed.
- If there is no match, no code is executed.


***Example***

The getDay() method returns the weekday as a number between 0 and 6.
(Sundday=0, Monday=1, Tuseday=2..)
This example uses the weekday number to calculate the weekday name:

```
   switch(new Date().getDay()){
      case 0:
         day = "Sunday";
         break;
      case 1:
         day = "Monday";
         break;
      case 2:
         day = "Tuseday";
         dreak;
      case 3:
         day = "Wednesday"
         break;
      case 4:
         day = "Thursday"
         break;
      case 5:
         day = "Friday"
         break;
      case 6:
         day = "saturday";
   }
```