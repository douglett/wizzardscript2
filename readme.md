WizzardScript parser and runtime - version-2
============================================

A simple parser and runtime for WizzardScript programming language.

- compiler stages:
	(1) Lexer (Tokenizer) and Parser (to Json-AST) - these are reusable!
	(2) Semantic Analysis - type checking, missing defines, missing functions (TODO?)
	(2) Generator - makes WizzardASM
- WizzardASM runtime (custom)

https://www.geeksforgeeks.org/phases-of-a-compiler/