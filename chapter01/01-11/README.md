### 1.11 Using removeChild() and replaceChild() to Remove and Replace Nodes

Removing a node from the DOM is a bit of a multistep process.

    parentNode.removeChild()

Replacing an element or text node is not unlike removing one.

    parentNode.replaceChild()

> Notes
>
> Depending on what you are removing or replacing, simply providing the innerHTML, outerHTML, and textContent properties with an empty string might be easier and faster.
>
> _Be careful, however, as memory leaks in the browser might come back to haunt you._
>
> replaceChild() and removeChild() return the replaced and removed node, respectively. Basically, the node is not gone just because you replace or remove it. These actions simply take the node out of the current live document.
>
> _You still have a reference to it in memory._
>