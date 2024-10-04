Backus-Naur Form (BNF) is a formal notation used to describe the syntax rules of a language. It's a meta-language; a language that describes a language, first developed by John Backus (1959) and then augmented by Peter Naur (1960). 

Regular languages are expressible by regular expressions, some languages cannot be expressed by a regular expression. The class of languages called context-free languages is more expressive than regular languages. BNF is a way to define these context-free languages.
- ::= (is defined as)
- | (Or)
- <> (Surrounds Category Names)

An instruction for a computer must not be ambiguous in any way, programming language requires strict and precise rules. That is why we have not yet been successful at natural language processing. BNF can be used by compiler writers to represent the precise syntax of a programming language.

A context-free language can be defined by BNF when a single non-terminal symbol on the left can always be replaced by the definition on the right. That's just a fancy way of saying that the context of the non-terminal symbol does not influence its interpretation, there is no ambiguity in the definition. Remember that a "non-terminal" symbol is something like "postcode", "car registration number" or "variable name" which can be broken down further. A non-zero digit can be defined as 1|2|3|4|5|6|7|8|9 and this is a "terminal" symbol.

# Parsing
The act of parsing is checking an input string against the set of BNF rules to see if it is valid. When a compiler or interpreter encounters an input it validates the input by building a tree according to the BNF rules.

# Syntax Diagram
A syntax diagram is another way to represent context free languages. It is the graphical equivalent of a BNF. The symbols are:
- Ellipse/Circle - a terminal symbol
- Rectangle - A non terminal symbol
- Rectangle with looping arrow - A non terminal symbol that can be used again.