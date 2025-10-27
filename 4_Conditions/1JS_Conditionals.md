## Javascript Conditionals

---

   #### Conditional statements

   When you write code, you often want to perform **different actions** for **different conditions.**
   Conditional statements **run diffrerent code** depending on a **true** or **false** condition.
   **Conditional statements** include:

   - if
   - if...else
   - if...else if...else
   - switch
   - twrnary(`?:`)

---

### When to use conditionals

   - Use `if` to specify a **code block** to be executed, if a specifed condition is `true`
   - Use `else` to specify a **code block** to be executed, if the same condition is `false`
   - Use `else if` to specify a **new condition** to test, if the first condition is `false`
   - Use `switch` to specify many **alternative code block** to be executed
   - Use (`?:`) (ternary) as a shorthand for `if...else`

#### The `if` statement

Use `if` to specify a **code block** to be executed, if a specified condition is `true`

***Example***

```
   if(condition){
      // code to execute if the condition is true
   }
```

#### `else` statement

Use `else` to specify a **code block** to be executed, if the same condition is `false`

***Example***

```
   if(condition){
      // code to execute if the conditon is true
   }else{
      // code to execute id the conditon is false
   }
```

#### The `else if` statement

Use `else if` to specify a **new conditon** to text if the first condition is `false`

***Example***

```
   if (condition1) {
      // code to execute if condition1 is true
   } else if(condition2){
      // code to execte if the condition1 is false and confition2 is true
   }else{
      code to excute if the condition is false ans condition2 is false
   }
```

#### The switch statement

Use `switch` to specify many **alternative code block** to be executed.

***Example***

```
   switch(exoression){
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

#### Ternary Operator (`?:`)

Use (`?:`) (ternary) as a shorthand for `if...else`.

***Example***

```
   condition ? expression1 : expression2
```