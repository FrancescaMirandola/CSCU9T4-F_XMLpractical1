# CSCU9T4-F_XMLpractical1
CSCU9T4-F_XMLpractical1 using DOM
- the validation is made after the document is uploaded (after loadDocument is called)
- if validateDocument returns true, the nodes are printed; otherwise, an error message is printed
- instead of having a generic exception catch, there's now a SAXParseException and a more explicative message is printed when the exception occurs
- for printing the nodes, a for loop has been created. Firstly, a list with all the nodes available in the document (items) is created.Then the content of each node is printed.
