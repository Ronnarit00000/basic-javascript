### javascript const

---

   The const keyword was introued in ES6(2015)
   Variable define with `const` cannot be Redeclared
   Variable define with `const` cannot be Reassigned
   Variable difine with `const` have block scope

---

***Example***

```
   // correct
   const PI = 3.141592655359;

   // incorrect
   const PI;
   PI = 3.141592655359;
```

### constant Objects and arrays

This `const` is a little misleading.
It dose not define a constant value. It defines a constant reference to value.
Because of this you can NOT:

   - Reassign a constant value
   - Reassign a constant array
   - Reassign a constant object

   But you can

   - Change the element of constant array
   - Change the properties of constant object

#### Constant Arrays

You can change the elements of a constant array:

***Example***

```
   // You can create a constant array
   const cars = ["Saab", "Volvo", "BMW"];

   // You can change an element:
   cars[0] = "toyota";

   // You can add an element:
   cars.push("Audi");

   // But you can NOT reassign the array:
   const cars = ["Saab", "Volvo", "BMW"];
   cars = ["Toyota", "Volvo", "Audi"]; // ERROR
```

#### Constant Objects

You can change the properties of a constant object:

***Example***

```
   // You can create a const object:
   const car = {type:"Fiat", model:"500", colro:"white"}

   // You can change a property:
   car.color = red;

   // You can add a property:
   car.owner = "Johnson";

   // But you can NOT reassign the Oject:
   const car = {type: "Fiat", model: "500", color: "white"};
   car = {type: "Volvo", model: "EX60", color: "red"} // ERROR
```

### Differren Between var, let and const
|        | Scpre  | Redeclare | Reassign | Hoidte     | Binds this   |
|---|---|---|---|---|---|
| var    | No     | Yes       | Yes       | Yes       | Yes          | 
| let    | Yes    | NO        | Yes       | No        | No           | 
| const  | Yes    | NO        | No        | No        | No           | 
