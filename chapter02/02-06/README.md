### 2.6 Using document.implementation.hasFeature() to Detect DOM Specifications/Features

It’s possible, using document.implementation.hasFeature(), to ask the current document (for a boolean) what feature and level the browser has implemented/supports. For example, we can ask if the browser has implemented the Core DOM Level 3 specification by passing the name of the feature and the version to the hasFeature() method. In the following code, I ask if the browser has implemented the Core 2.0 and 3.0 specifications.


|  Feature                      |  Supported versions               |
|-------------------------------|-----------------------------------|
|   Core                        |  1.0, 2.0, 3.0                    |
|   XML                         |  1.0, 2.0, 3.0                    |
|   HTML                        |  1.0, 2.0                         |
|   Views                       |  2.0                              |
|   StyleSheets                 |  2.0                              |
|   CSS                         |  2.0                              |
|   CSS2                        |  2.0                              |
|   Events                      |  2.0, 3.0                         |
|   UIEvents                    |  2.0, 3.0                         |
|   MouseEvents                 |  2.0, 3.0                         |
|   MutationEvents              |  2.0, 3.0                         |
|   HTMLEvents                  |  2.0                              |
|   Range                       |  2.0                              |
|   Traversal                   |  2.0                              |
|   LS (loading and saving between files and DOM trees synchronously)                       |  3.0                              |
|   LS-Async (loading and saving between files and DOM trees synchronously)                 |  3.0                              |
|   Validation                  |  3.0                              |


> Notes
>
> Don’t trust hasFeature() alone; you should use capability detection in addition to hasFeature().
>
> Using the isSupported method, implementation information can be gathered for a specific/selected node only (i.e., element.isSupported(feature,version).
>
> You can determine online what a user agent supports. On this site([http://www.w3.org/2003/02/06-dom-support.html]()), you will find a table indicating what the browser loading the URL claims to implement.