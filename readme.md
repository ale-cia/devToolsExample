Dev Tools Example
=================

The error read: 
 **Uncaught ReferenceError: showGlobal is not defined
    at startMeUp (script.js:40)
    at onload (index.html:9)**
    
I looked at line 40 in the script.js file and noticed that on line 9 and 35 the function being called is "showGlobals" instead of "showGlobal" so I changed line 40 to "showGlobals" and it worked.
