### 2.4 document Child Nodes

document nodes can contain one DocumentType node object and one Element node object. This should not be a surprise, since HTML documents typically contain only one doctype (e.g., \<!DOCTYPE html>) and one element (e.g., \<html lang="en">). Thus, if you ask for the children (e.g., document.childNodes) of the document object, you will get an array containing, at the very least, the document’s doctype/DTD and \<html lang="en"> element.

> Notes
>
> Don’t confuse the window.document object created from the HTMLDocument constructor with the Document object. Just remember that window.document is the starting point for the DOM interface. That is why document.childNodes contains child nodes.
>
> If a comment node (not discussed in this book) is made outside the \<html lang="en"> element, it will become a child node of the win dow.document. However, having comment nodes outside the \<html> element can cause some buggy results in IE and is a violation of the DOM specification.