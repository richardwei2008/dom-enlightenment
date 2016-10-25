### 2.10 Using ownerDocument to Get a Reference to the Document from an Element

The ownerDocument property, when called on a node, returns a reference to the document within which the node is contained. In the following code, I get a reference to the document of the \<body> in the HTML document and the document node for the \<body> element contained inside the iframe.

If `ownerDocument` is called on the `document` node, the value returned is `null`.