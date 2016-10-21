### Node Object Types

* DOCUMENT_NODE (e.g., window.document)
* ELEMENT_NODE (e.g., \<body>, \<a>, \<p>, \<script>, \<style>, \<html>, \<h1>)
* ATTRIBUTE_NODE (e.g., class="funEdges")
* TEXT_NODE (e.g., text characters in an HTML document including carriage returns and whitespace)
* DOCUMENT_FRAGMENT_NODE (e.g., document.createDocumentFragment())
* DOCUMENT_TYPE_NODE (e.g., <!DOCTYPE html>)

> Notes
>
> Semantics
>
> * Node, Element, Text, Attr and HTMLAnchorElement as interface.
> * ATTRIBUTE_NODE is not actually part of a tree. (Deprecated in DOM4)
> * Comment nodes and are similar in nature to Text nodes