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
The main benefits of DTD are that programs can assume a structure and it provides a specification, documentation.
On the other hand it limits flexibily and ease of change.

## JSON
JSON (JavaScript Object Notation) evolved to be independent from JavaScript.  It's newer than XML, thus there aren't that many tools for JSON as we have for XML.
* standard for serialising data objects that are in a program, typically in files
* human-readable, useful for data interchange
* useful for representing & storing semistructured data
* parser for many languages

## SQL
- declarative language, 
- queries are optimised with a query optimiser

There's two parts of the language: the Data Definition Language (DDL) and Data Manipulation (DML). DDL is responsible for creating/droping tables when DML helps to manipulate (insert, update, delete) and query (select) database.h

Example queries:
combining two relations
``` 
SELECT distinct student.id, name, score FROM student, class WHERE student.id = class.id AND sex = 'Female' ORDER BY score DESC name; 
```
'no need to add prefixes to _distinct_ and _id_ if the atributes are unique;
attributes after DESC are to indicate how should the records be ordered in next steps'
