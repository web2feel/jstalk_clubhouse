# Modern JavaScript
Few talking points on the basics of modern javascript.

## Introduction to JS

 - JavaScript was introduced in 1995 as a way to make webpages
  interactive on Netscape browser. 
 - It was created by Brendan Eich in 10 days time
 -  It has no relation to Java .
 - JavaScript is an **interpreted language**, not a compiled language.
 - An interpreter in the browser reads over the JavaScript code, interprets each line, and runs it.
 - ECMAScript : A standardisation of JS to ensure uniform behaviour of webpages on different browser.
 - ES6 (ECMAScript 2015) : This version introduced lot of modern features to the JavaScript
 - Latest version is ES12
  
## Values

 - In JavaScript, data is handled in the form of Values.
 - JS has different types of values or **data types**
 
 1. **Primitive values ( Immutable data types)** 
	  - Strings 	 
	  - Numbers
	  - Booleans
	  - Undefined
	  - Null
	  - Symbols
	  - BigInt
 
 2. **Mutable values**
	 - Objects
	 - Functions 

## Operators

**1. Assignment Operators**

They are operators are used to **assign** values to variables.

    =	
    +=	
    -=	
    /=	
    %=
    ... and more

**2. Arithmetic Operators**

They are operators are used to perform **arithmetic calculations**

    + 
    - 
    *
    /
    %
    **
 

**3. Comparison Operators** 

These operators **compare** two values and return a boolean value, either true or flase

    ==
    ===
    !=
    !==
    >
    <
    >=
    <=

**4. Logical Operators**

These operators perform logical operations and return a boolean value.

    &&
    ||
    !

**5. String Operator**

The `+` symbol is used to concatenate or join two or more string values

**6. Ternary Operator** 

This is a conditional operator. Only operator that takes **Three** operands
```
condition ? expressionIfTrue : expressionIfFalse
```
**7. Unary Operator**
They are operators that takes only one operand.

    +
    -
    ++
    __
    typeof
    delete
    in



## Variables

 - Variables are **pointers** to **values** in JS program. 
 - Three  keywords for creating variables are `var , let, const`
 -   `var`  declarations are globally scoped or function scoped while  `let`  and  `const`  are block scoped.
-  `var`  variables can be updated and re-declared within its scope.
-  `let`  variables can be updated but not re-declared.  
- `const`  variables can neither be updated nor re-declared.
-  `var`  variables are initialized with  `undefined`.
- `let`  and  `const`  variables are not initialized.
-   While  `var`  and  `let`  can be declared without being initialized,  `const`  must be initialized during declaration.

  
