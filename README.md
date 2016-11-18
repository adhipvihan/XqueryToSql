This is a small project to demonstrate relational encoding of the tree structure of XML documents using ranges of
integers:
• node A is an ancestor of node B ⇔ range of A contains range of B
• node A to the left of node B ⇔ range of A precedes range of B

Also known as interval coding.

Tasks:

1. Definining the schema (relations, attributes) of the relational encoding.

Id is the Primary Key which identifies each node.
NodeLabel is the label of the node like “a”,”b”,”c”
RangeStart is the start of the range for the node.
RangeEnd is the end of the range for the node.


2. Translate the following XPath queries to equivalent SQL-2 queries (no recursion):


(a) //a//*.

SQL queries for this are in repository with the name PartA.

(b) /a/b[c].

SQL queries for this are in repository with the name PartB.

