### 2.7 Getting a Reference to the Focus/Active Node in the Document

Using the document.activeElement, we can quickly get a reference to the node in the document that is focused/active. In the following code, on page load, I am setting the focus of the document to the \<textarea> node and then gaining a reference to that node by using the activeElement property.

> Notes
>
> The focused/active element returns elements that have the ability to be focused. If you visit a web page in a browser and start pressing the Tab key, you will see focus shifting from one element to another element in the page that can receive focus. Don’t confuse the selection of nodes (highlighting sections of the HTML page with your mouse) with elements that get focus for the purpose of inputting something with keystrokes, the space bar, or a mouse.