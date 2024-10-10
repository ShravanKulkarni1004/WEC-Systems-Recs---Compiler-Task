# WEC Systems Recruitments Tasks

Welcome to my repository where i have explained the tasks that i worked on during WEC(Web Enthusiasts Club)🕷 Systems Recruitments.

## 1. Compilers : Compiler for an English-like language💻

Link for task: [Compilers](https://docs.google.com/document/d/1KL2h5e0mwsyTW5KI5TlLmu3iGvPcs19UP5JArc60CXE/edit?usp=sharing)

### How to access my code 
- Open lexer_parser.cpp file
- Copy the whole code
- Paste it in a C++ compiler(eg. VScode)

### Running Tests
- Assuming you have gone through the code, lets start with simplest input string
  - `"Hello, world-wide communication technologies."`
  
  - **Output**- ![Screenshot (33)](https://github.com/user-attachments/assets/848e73a3-a9fc-42cb-b973-e42080c77808)


  The code tokenizes the given input string based on specifications provided. It also parses through every token and analyzes it syntactically and gives the accepted string along with      the Abstract Syntax Tree(AST).
  
  Also the Token Type is defined as follows:
  `enum TokenType { STARTWORD, WORD, COMMA, HYPHEN, STOP, QUOTATION, INVALID, END };`

- If we add a word of length less than 3
    - `"Hello, my world-wide communication technologies."`
 
    - **Output**- 

- If we add a word of length more than 26
    - `"Hello, world-wide communication technologies abcdefghijklmnopqrstuvwxyzabc."`
 
    - **Output**- 

    You can try taking a word more than 26 but less than 29😉

- If we add a sequence of numbers, say 123
    - `"Hello, 123 world-wide communication technologies."`
 
    - **Output**- 

- If we add a quotation
    - `"Hello, 'modern' world-wide communication technologies."`
 
    - **Output**- 

- 
  


