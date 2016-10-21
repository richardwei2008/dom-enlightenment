### 1.15 Converting a NodeList or HTMLCollection to a JavaScript Array

Node lists and HTML collections are array-like but are not true JavaScript arrays, which inherit array methods.

> Notes
>
> Array.isArray was implemented in ECMAScript Edition 5.

Converting a node list and HTML collection list to a true JavaScript array can provide several benefits.

> Notes
>
> In ECMAScript Edition 6, we have Array.from to look forward to, which converts a single argument that is an array-like object or list (e.g., arguments, NodeList, DOMTokenList [used by classList], and NamedNodeMap [used by the attributes property]) into a new Array() and returns it.