### 1.14 Getting a List/Collection of All Immediate Child Nodes

Using the childNodes property produces an array-like list [i.e., NodeList] of the immediate child nodes.

> Notes
>
> The NodeList returned by childNodes only contains immediate child nodes.
>
> Be aware that childNodes contains not only Element nodes but also all other node types (e.g., Text and Comment nodes).