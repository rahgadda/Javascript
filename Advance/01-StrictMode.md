<input style="position: absolute; top: 20%;right: 10%;" type="button" onclick="location.href='https://rahgadda.github.io/Javascript/Advance/02-EventLoop.html';" value="Next" />
<br/><br/>

## Strict Mode

- The statement `'use strict'`; is a new feature in ECMAScript 5 that places your program, or a function, in a “strict” operating context.
- This strict context prevents certain actions from being taken and throws more exceptions.
- Strict mode can used for entire program or specific function. It should be the first statement.  
   `//Script Strict Mode`  
   `'use strict';`  
   `var v = "strict mode script!";`

  `function strictfn() {`  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`'use strict';`  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`//Function is in Strict Mode`  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`return "strict mode function!";`  
   `}`
