### 1.8 Using JavaScript Strings to Create and Add Element and Text Nodes to the DOM

* innerHTML
* outerHTML
* textContent
* insertAdjacentHTML() only works on Element nodes

> Notes
>
> The innerHTML property will convert HTML elements found in the string to actual DOM nodes, while textContent can only be used to construct text nodes.
>
> document.write() can also be used to simultaneously create and add nodes to the DOM.
>
> You should be aware that using the write() method will stall/block the parsing of the HTML document being loaded.
>
> innerHTML invokes a heavy and expensive HTML parser
>
> The insertAdjacentHTML options beforebegin and afterend will only work if the node is in the DOM tree and has a parent element.
>
> textContent gets the content of all elements, including \<script> and \<style> elements, but innerText does not.
>
> innerText is aware of style and will not return the text of hidden elements, whereas textContent will.
>
> Available to all modern browsers except Firefox are insertAdjacentElement() and insertAdjacentText().