### 1.18 Determining Whether Two Nodes Are Identical

According to the DOM3 specification, two nodes are equal if and only if the following conditions are satisfied:

* The two nodes are of the same type.
* The following string attributes are equal: nodeName, localName, namespaceURI, prefix, and nodeValue. That is, they are both null, or they have the same length and are identical character for character.
* The attributes NamedNodeMaps are equal. That is, they are both null, or they have the same length and for each node that exists in one map, there is a node that exists in the other map and is equal, although not necessarily at the same index.
* The childNodes NodeLists are equal. That is, they are both null, or they have the same length and contain equal nodes at the same index. Note that normalization can affect equality; to avoid this, nodes should be normalized before being compared.


> Notes
>
> If you don’t care about two nodes being exactly equal, and instead you want to know whether two node references refer to the same node, you can simply check them using the === operator
>
>   document.body === document.body
>
> This will tell you if they are identical but not equal.