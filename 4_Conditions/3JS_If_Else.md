## Javascript else

### The else statement

Use the `else` statement to specify a **block of code** be execute if a condition is `false`

```
   if (condition) {
      // block of code to be executed if the condition is true
   }else {
      // block of code to be executed if the condition is false
   }
```

***Example***

```
   if the hour is than 18 create a "Good day" greeting, otherwose "good revening":

   if (hour < 18){
      greeting = "Good day"
   }else {
      greeting = "Good evening"
   }
```

### The else if statement

Use the `else if` statement to specify a new confition if the first is `false`

***syntax***

```
   if(condition1){
      // block of code to be executed if condition1 is true
   }else if(condition2){
      // block of code to be executes if the condition1 is false and condition2 is true
   }else {
      // block of code to be executed if the condition1 is false and condition2 is false
   }
```

***Example***

```
   if(time < 10){
      greeting = "Good morning";
   }else if(time < 20){
      greeting = "Good day"
   }else{
      greeting = "Good evening"
   }
```

***Example***

This example will write a link either W3Schools to the world Wildlife Foundation (WWF). By using a random number, the there is a 50% chance for each of the link

```
   let text;
   if (Math.random() < 0.5) {
      text = "<a href='https://w3schools.com'>Visit W3Schools</a>";
   } else {
      text = "<a href='https://wwf.org'>Visit WWF</a>";
   }
   document.getElementById("demo").innerHTML = text;
```
