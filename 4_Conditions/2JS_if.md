## Javascript if

---

   #### The Javascript if statement
   
   Use The Javascript if statement to execute a block of code **when a codition is true**

---

## syntax 

```
   if(condition){
      // block of code to be executed if the condition is true
   }
```

Note that `if` is in lowercase letters. Uppercase letter(If or IF) will generate a javascript error.

***Example***

```
   let hour, greeting

   if(hour < 18 ){
      greeting = "Good day"
   }

   // the result of greeting will be:
   // Good day
```

***Example***

```
   let age = 18;
   let text = "You can Not drive"

   if(age >= 18){
      text = "You can drive";
   }
```
Nested if

You can use an `if` statement inside another `if` statement:

***Example***

```
   let age = 16;
   let country = "USA";
   let text = "You can Not drive!";

   if(contry == "USA"){
      if(age >= 16){
         text = "You can drive"
      }
   }
```

Nested if statement can make your code more complex.
A better solution is to the use the logical AND operator:

***Example***

```
   let age = 16;
   let country = "USA"
   let text = You can Not drive";

   if (country = "USA" && age >= 16){
      text = "You can drive";
   }
```