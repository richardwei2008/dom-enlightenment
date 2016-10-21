### 1.17 Verifying a Node Position in the DOM Tree with contains() and compareDocumentPosition()

The meaning of the numeric values returned from compareDocumentPosition()

Number code returned  | Number code information--------------------------------------------------


|  Number code returned         |  Number code information          |    |
|-------------------------------|-----------------------------------|----|
|   0                           |  Elements are identical.          |    |
|   1                           |  DOCUMENT_POSITION_DISCONNECTED   | Set when selected node and passed-in node are not in the same document.|
|   2                           |  DOCUMENT_POSITION_PRECEDING      | Set when passed-in node is preceding selected node.|
|   4                           |  DOCUMENT_POSITION_FOLLOWING      | Set when passed-in node is following selected node.|
|   8                           |  DOCUMENT_POSITION_CONTAINS       | Set when passed-in node is an ancestor of selected node.
|   16, 10                      |  DOCUMENT_POSITION_CONTAINED_BY   | (16, 10 in hexadecimal) Set when passed-in node is a descendant of selected node.|

> Notes
> 
> contains() will return true if the node selected and the node passedin are identical.
>
> compareDocumentPosition() can be rather confusing, because it’s possiblefor a node to have more than one type of relationship with anothernode.