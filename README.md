# SYNTAXIFY
The project aims to build a mini compiler for C language


The front-end of compiler consisting of the following four phases is built:
1) Lexical Analysis
2) Syntax Analysis
3) Semantic Analysis
4) Intermediate Code Generation

# Lexical Analysis
This is the first phase of a compiler's front-end, also known as the scanner. It reads the source code character by character and groups them into meaningful units called tokens. Tokens can be keywords, identifiers, constants, operators, or symbols. The goal of the lexical analysis is to convert the source code into a sequence of tokens that can be easily parsed by the next phase.

# Syntax Analysis
This is the second phase of the compiler's front-end, also known as the parser. It takes the sequence of tokens produced by the lexical analyzer and builds a parse tree or an abstract syntax tree (AST). The parse tree represents the syntactic structure of the source code. The parser verifies that the source code conforms to the grammar rules of the programming language. If there are any syntax errors, the parser reports them.

# Semantic Analysis
This is the third phase of the compiler's front-end. It analyzes the meaning of the program, beyond its syntax. It performs various checks and transformations on the parse tree to ensure that the program is semantically correct. The semantic analyzer verifies that the program is well-formed and consistent, by checking the types of expressions, the scope of identifiers, and other language-specific rules. If there are any semantic errors, the semantic analyzer reports them.

# Intermediate Code Generation
This is the fourth and final phase of the compiler's front-end. It translates the parsed and semantically analyzed source code into an intermediate representation (IR). The IR is a language-independent code that is easier to optimize and translate to machine code or other lower-level languages. The intermediate code is used as input by the back-end of the compiler. There are different types of intermediate code, such as three-address code, bytecode, or LLVM IR.

So, these are the four phases of a compiler's front-end. They work together to analyze, verify, and translate the source code into an intermediate representation that can be optimized and executed.
