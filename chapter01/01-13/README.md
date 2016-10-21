### 1.13 Grokking Node Collections (i.e., NodeList and HTMLCollection)

When selecting groups of nodes from a tree (see Chapter 3) or accessing predefined sets of nodes, the nodes are placed in either a NodeList [e.g., document.querySelector All('*')] or an HTMLCollection (e.g., document.scripts). These array-like object collections have the following characteristics:

* A collection can be either live or static. This means the nodes contained in the collection are either literally part of the live document or a snapshot of the live document.

* By default, nodes are sorted inside the collection by tree order. This means the order matches the linear path from tree trunk to branches.

* The collections have a length property that reflects the number of elements in the list.