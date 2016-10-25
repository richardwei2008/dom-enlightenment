## Chapter 2: Document Nodes

### 2.1 document Node Overview

The HTMLDocument constructor (which inherits from document) creates a DOCUMENT_NODE (i.e., a window.document) in the DOM.

> Notes
>
> Both Document and HTMLDocument constructors are typically instantiated by the browser when you load an HTML document. However, using document.implementation.createHTMLDocument(), it’s possible to create your own HTML document outside the one currently loaded in the browser. In addition to createHTMLDocument(), it’s possible to create a document object that has yet to be set up as an HTML document using createDocument(). An example use of these methods might be to programmatically provide an HTML document to an iframe.

