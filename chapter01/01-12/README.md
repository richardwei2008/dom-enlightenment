### 1.12 Using cloneNode() to Clone Nodes

Using the cloneNode() method, it’s possible to duplicate a single node or a node and all its child nodes.

To clone a node and all its child nodes

    cloneNode(true)

> Notes
>
> When cloning an Element node, all of its attributes and their values (including in-line events) are cloned as well. Anything added with addEventListener() or node.onclick is not cloned.
>
> You might think that cloning a node and its children using
>
>       cloneNode(true)
>
> would return a NodeList, but it in fact does not.
>
> ** cloneNode() may lead to duplicate element IDs in a document.
>