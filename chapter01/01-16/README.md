### 1.16 Traversing Nodes in the DOM

From a node reference (i.e., document.querySelector('ul')), it’s possible to get a different node reference by traversing the DOM using the following properties:

* parentNode
* firstChild
* lastChild
* nextSibling
* previousSibling

Using the following properties we can traverse the DOM, while ignoring text and comment nodes:

* firstElementChild
* lastElementChild
* nextElementChild
* previousElementChild
* children
* parentElement

> Notes
>
> The childElementCount is not mentioned, but you should be aware of its availability for calculating the number of child elements a node contains.

