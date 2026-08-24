# Interpreter in Golang for the Monkey language.

I will be use the book, **Writing and Interpreter in Go** by Thorsten Ball to write this first interpreter. I will then write the same interpreter in other languages to better learn and utilize the language. 

I have some experience using C, minimal experience in Git, and have not programmed in the Go language before. If you have comments or recommendations to help me, feel free to email me at ceoadebi@outlook.com. Thank you and enjoy!

Interpreters take source code and evaluate it so that it can be executed later.
The output of this book will be a tree-walking interpreter.

## Lexer
The lexer takes in source code as an input and outputs the tokens that represent the source code. It goes through the input then outputs the next token it recognizes.

## Parser
The parser is a software component that takes input data (frequently text) and builds a data structure that gives structural representation of the input (parse tree, abstract syntax tree, etc.), checking for correct syntax in the process. The parser is preceded by the lexer that creates tokens from the sequqence of the input characters.
 
