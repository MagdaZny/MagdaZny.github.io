# Databases and data structures

## XML
XML (Extensible Markup Language) is a standard for data representation and exchange, was initially designed for exchanging information on the Internet.
- similar to HTML, however tags describe content rather than formatting
- streaming format (for sending and consuming)
- tree structure
- consists of tagged nested elements, attributes and text
- flexible, "self-describing" schema

Except a proper form of XML (single root, proper nestind, unique attibutes) we talk also about XML validation, that is being ensured by DTD (Document Type Descriptor) or XML Schema. 
**DTD** is a grammar like language for specifying elements, attributes, nesting, ordering etc.  
Cons of using DTD:
- programs can assume structure
- it is a specification, documentation
~ analogy to "typing"

On the other hand it prevents
- flexibily, ease of change
~ analogy to no "typing"

## JSON
JSON (JavaScript Object Notation) evolved to be independent from JavaScript.  It's newer than XML, thus there aren't that many tools for JSON as we have for XML.
* standard for serialising data objects that are in a program, typically in files
* human-readable, useful for data interchange
* useful for representing & storing semistructured data
* parser for many languages

