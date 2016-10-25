### 2.9 document.defaultView Is a Shortcut to the Head/Global Object

You should be aware that the defaultView property is a shortcut to the JavaScript head object, or what some refer to as the global object. The head object in a web browser is the window object, and defaultView will point to this object in a JavaScript browser environment. The following code demonstrates the value of defaultView in a browser.

If you are dealing with a DOM that is headless or a JavaScript environment that is not running in a web browser [i.e., Node.js], this property can get you access to the head object scope.