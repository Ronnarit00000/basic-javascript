## Javascript comments

- Javascript comments can be used to explain javascript code, and to make it more readable.
- Javascript commentd can also be used to prevent execution, when testing altenative code.


###  Single linr comments

Single line comments start with `//`
Any text between `//` and the end of the line will be ignored by javascript (will not be executed).
This example uses a single-line comment before each code line:

```
   Example

      // Change heading:
      document.getElementById("myH").innerHTML = "My Frist Page";

      // Change paragraph:
      document.getElementById("myP").innerHTML = "My first paragraph";
```

This example uses a single line comment at the end of each line to explia the code:

```
   Examle

      let x = 5;        // Declare x, give it the value of 5
      let y = x + 2;    // Declare y, give it the value of x + 2
```


### Multi-line comments

Multi-line commentd start with `/*` and with `/*`
Any text between `/*` and `/*` will be ignored by javascript.
This example uses a multi-line comment(a comment block) to explain the code:

```
   Examle
      
      /*
         The code below will change
         the handing with id = "myH"
         and the paragraph with id = "myP"
         in my web page:
      */

      document.getElementById("myH").innerHTML = "My First Page";
      document.getElementById("myP").innerHTML = "My First paragraph";
```

### Using comments to prevent execution

Using comments to prevent execution of code is suitable for testing.
Adding `//` in front of a code line changes the code lines from an executable line to a comment.
This example uses `//` to prevent exection of one of the code lines:

```
   Example

      // document.getElementById("myH").innerHTML = "My First Page";
      document.getElementById("myP").innerHTML = "My First Paragraph";
```

This example uses a comment block to prevent execution of multiple line:

```
   Example

      /*
      document.getElementById("myH").innerHTML = "My First Page";
      document.getElementById("myP").innerHTML = "My First paragraph";
      */
```