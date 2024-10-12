# WEC Systems Recruitments Tasks

Welcome to my repository where i have explained the tasks that i worked on during WEC(Web Enthusiasts Club)🕷 Systems Recruitments.

## 1. Compilers : Compiler for an English-like language💻

Link for task: [Compilers](https://docs.google.com/document/d/1KL2h5e0mwsyTW5KI5TlLmu3iGvPcs19UP5JArc60CXE/edit?usp=sharing)

### About my code:
Designing a simple English-like language compiler with specifications provided in task for lexical and syntactic analysis. I have taken handwritten approach for writing the code for compiler. I have introduced a lot of functions and methods for classes, and also explained them in a detailed way. The outputs are Symbol Table, representing token type of respective token, Validity of Input String, Lexical and Parsing Errors(if any) and Abstract Syntax Tree of accepted string.

### How to access my code 
- Open lexer_parser.cpp file
- Copy the whole code
- Paste it in a C++ compiler(eg. VScode)

### Running Tests
- Assuming you have gone through the code, lets start with simplest input string
  - `"Hello, world-wide communication technologies."`
  
  - **Output**- ![Screenshot (34)](https://github.com/user-attachments/assets/6adee1e3-b1ec-4bbe-b487-75db18e9ae32)

  The code tokenizes the given input string based on specifications provided. It also parses through every token and analyzes it syntactically and gives the accepted string along with      the Abstract Syntax Tree(AST).

- If we add a word of length less than 3
    - `"Hello, my world-wide communication technologies."`
 
    - **Output**- ![Screenshot (35)](https://github.com/user-attachments/assets/d03a1e66-2a8b-4a94-ac21-cea3fbdfc6a7)

- If we add a word of length more than 26
    - `"Hello, world-wide communication technologies abcdefghijklmnopqrstuvwxyzabc."`
 
    - **Output**- ![Screenshot (36)](https://github.com/user-attachments/assets/ba3f9490-113a-42a4-9ed3-757365789ac2)

    You can try taking a word of length more than 26 but less than 29.

- If we add a sequence of numbers, say 123
    - `"Hello, 123 world-wide communication technologies."`
 
    - **Output**- ![Screenshot (37)](https://github.com/user-attachments/assets/07036101-27ff-47ac-b606-ab6582478460)

- If we add a quotation
    - `"Hello, 'modern' world-wide communication technologies."`
 
    - **Output**- ![Screenshot (38)](https://github.com/user-attachments/assets/bae19af3-b140-453b-adc2-361fcf78a18c)

- You can also take input with multiple tabs/whitespaces in between words and try. (It still stays same😉)


  Now let's start with parsing errors

- If your starting word is not 'Startword'
    - `"hello, world-wide communication technologies."`
 
    - **Output**- ![Screenshot (39)](https://github.com/user-attachments/assets/099546b0-fc4d-46d9-ba69-4564e7a3d4f4)

- If your string does not end with 'fullstop'
    - `"Hello, world-wide communication technologies"`
 
    - **Output**- ![Screenshot (40)](https://github.com/user-attachments/assets/6fe0ce3c-d822-4020-a2d9-54d2a1e1a67a)

- If your string has consecutive commas
    - `"Hello,, world-wide communication technologies."`
 
    - **Output**- ![Screenshot (41)](https://github.com/user-attachments/assets/1500ad3f-d69e-4958-910d-17552ac9724c)

- If your string has consecutive hyphens
    - `"Hello, world--wide communication technologies."`
 
    - **Output**- ![Screenshot (42)](https://github.com/user-attachments/assets/c0b8cb41-6595-4d8a-b2b1-3b1801b5999f)

- If your string has consecutive hyphens and commas, it parses commas first
    - `"Hello, world--wide ,, communication technologies."`
 
    - **Output**- ![Screenshot (43)](https://github.com/user-attachments/assets/ef0188d5-7c9f-4909-bc52-d3057b601107)

- If your string has tokens after fullstop
    - `"Hello, world-wide communication technologies.abc"`
 
    - **Output**- ![Screenshot (44)](https://github.com/user-attachments/assets/b9feea98-f5ee-4547-bd6c-52559da41c1a)
  


*Similarlly, You can play with the compiler with different kinds of input strings and try finding out how the compiler analyzes the input string.*



### Conclusion
Please feel free to add on any suggestions or improvements to the compiler.

Thank you!😄
