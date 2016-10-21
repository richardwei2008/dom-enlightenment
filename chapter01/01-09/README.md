### 1.9 Extracting Parts of the DOM Tree as JavaScript Strings

> Notes
>
> The textContent, innerText, and outerText properties, when being read, will return all the text nodes contained within the selected node. So, as an example (note that this is not a good idea in practice), document.body.textContent will get all the text nodes contained in the body element, not just the first text node.
>