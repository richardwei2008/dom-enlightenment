### 2.5 document Provides Shortcuts to \<!DOCTYPE>, \<html lang="en">, \<head>, and \<body>

Using the following properties, we can get a shortcut reference to the following nodes:

* document.doctype refers to \<!DOCTYPE>.
* document.documentElement refers to \<html lang="en">.
* document.head refers to \<head>.
* document.body refers to \<body>.


> Notes
>
> The doctype or DTD is a nodeType of 10 or DOCUMENT_TYPE_NODE and should not be confused with the DOCUMENT_NODE (a.k.a. window.document constructed from HTMLDocument()). The doctype is constructedfrom the DocumentType() constructor.
>
> In Safari, Chrome, and Opera, the document.doctype does not appear in the document.childNodes list. (Depend on the version of browser)