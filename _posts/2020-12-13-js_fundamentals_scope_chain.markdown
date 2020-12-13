---
layout: post
title:      "JS Fundamentals: Scope Chain"
date:       2020-12-13 15:41:25 -0500
permalink:  js_fundamentals_scope_chain
---


![Scope Chain](https://user-images.githubusercontent.com/38739923/102023131-53aa8580-3d59-11eb-849d-18e54a5feb7a.png)

So, we can look inside out, not outside in. Two functions declared in the same scope do not have access to anything declared in the other's scope.

**The JavaScript Engine**

When our JavaScript code is run in the browser, the JavaScript engine actually makes two separate passes over our code:

**Compilation Phase**
* variable declaration (allocates memory, sets up reference)
* function declaration 

**Execution Phase**
* actually runs the code! assigning values to variables, invoking functions

**Example:**

**Compilation Phase:**  a reference to the identifier `myVar` is stored in memory. The variable isn't yet assigned a value, and the second line (`myVar;`) is skipped over entirely because it isn't a declaration.

**Execution Phase:**  the value `42` is assigned to `myVar`.  When the engine reaches the second line, it sees the identifier myVar and resolves it to a value through a process known as *identifier resolution*.
