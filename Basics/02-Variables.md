<input style="position: absolute; top: 20%;left: 10%;" type="button" onclick="location.href='https://rahgadda.github.io/Javascript/Basics/01-Comments.html';" value="Back" />
<input style="position: absolute; top: 20%;left: 45%;right: 50%;" type="button" onclick="location.href='https://rahgadda.github.io/Javascript';" value="Home" />
<input style="position: absolute; top: 20%;right: 10%;" type="button" onclick="location.href='https://rahgadda.github.io/Javascript/Basics/03-DataTypes.html';" value="Next" />
<br/><br/>

## Variables

- Variables are used to store information. These are referenced and manipulated during execution of program.
- Javascript has below predefined rules w.r.t variable names
  - Name must start with a letter, underscore (\_), or dollar sign (\$).
  - Names starting with **(\_)** represents object's property or method that is **private**.
  - The **(\$)** name is commonly used as a shortcut to the **function document.getElementById()**. A very common use of this naming convention is found in jQuery library.
  - Subsequent characters can be letters, digits, (\_), or (\$).
  - Variable names are case sensitive.
  - Variable names support Unicode character set.  
    `var sí = true;`  
    `var π = 3.14;`
  - There's no limit to the length of the variable name.
  - You cannot use a variable without declaration or assignment.  
     `console.log(r*12) \\ Error - Uncaught ReferenceError: r is not defined`
  - The default value of any variable is **undefined**.
  - `var, const and let` keywords are used to declare a variable.
- Styling
  - **camelCase** will be used for naming variables, objects, functions, and instances.
  - **PascalCase** will be used for constructors or classes.
  - **UPPERCASE** will be used for naming Global and Constants variables
  - Use a leading **underscore (\_)** to name private properties.
  - Use **'use strict';** mode to avoid unsafe features. In this mode it is an error to assign a value to an undeclared variable.
  - Use **JSHint** for suggestions.
