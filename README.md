# Mini-Compiler-

Mini compiler which reads expression and gives an output. This project involves developing a simple compiler that can parse and evaluate arithmetic expressions. The objectives are to implement a lexer to tokenize the input string, a parser to generate an Abstract Syntax Tree (AST), and an evaluator to compute the result of the expression. This project demonstr ates the fundamental components of a compiler: lexical analysis, parsing, and evaluation, focusing on simplicity and clarity. The compiler is designed in three main phases: lexical analysis, parsing, and evaluation. Each phase is implemented as a separate class to maintain modularity and clarity.
•	Lexical Analysis
The lexical analysis phase involves reading the input string and converting it into a series of tokens. This phase is handled by the Lexer class. The lexer identifies numbers, operators, and parentheses, and ignores whitespace.

•	Parsing
The parsing phase converts the list of tokens into an Abstract Syntax Tree (AST). This phase is managed by the Parser class. The parser follows the grammar rules to construct nodes representing numbers and binary operations, adhering to the correct order of operations (precedence).

•	Evaluation
The evaluation phase involves traversing the AST and computing the result. The Evaluator class handles this phase, performing arithmetic operations as dictated by the tree structure
