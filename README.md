# How javaScript code works 🔥 
## When ever a js code is executed a global execution context is created .
## The global execution context has 2 parts :
   ### 1. Memory Phase : 
   Here everything is saved in key value paires .
   In memory phase the variables and functions are allocated memories . Undefined for variables (Example : a = undefined) and for functions the whole function is copied (Example : x : function{ console.log("hello world")}).

   ### 2. Code Phase : 
   In code phase js engines runs through code again and replace the undefined with there actual values (Example : a = 2) and then its exceutes . If we have function invocation again a new execution context is created and follows the same procedure of memory and code phase .

## Callstack 
This helps to keep the track of the order of  execution contexts . Deep function invocation context and even deletes each execution context after it returns the value. And there is nothing to execute.

And when the sqaure function is invoked a new context is created and pushed to the callstack..... 