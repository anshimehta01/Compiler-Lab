# Compiler-Lab

This repository contains a complete set of **Compiler Design Lab experiments** implemented in **C language**.  
The experiments cover **Lex/Yacc tools, parsing techniques, and grammar analysis**, as part of the Compiler Design course (3rd Year B.Tech CSE).

---

## 📚 Experiments Included
1. **Lex Tools** – Programs to count vowels, consonants, words, characters, and comments.  
2. **Lexical Analysis** – Token recognition, scanf/printf replacement, arithmetic expression validation.  
3. **Syntax Analysis (YACC)** – Expression validation and evaluation.  
4. **First and Follow** – Simulation of FIRST & FOLLOW sets of a grammar.  
5. **LL(1) Parser** – Construction of LL(1) parsing table.  
6. **Predictive Parser** – Design of a predictive parser for a given grammar.  
7. **Leading & Trailing** – Calculation for all non-terminals.  
8. **Operator Precedence Parser** – Implementation for expression parsing.  
9. **Shift-Reduce Parser** – Implementation of bottom-up parsing.  
10. **LALR Parser** – Implementation of LALR bottom-up parsing.

---

## ⚙️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/anshimehta01/Compiler-Lab.git
   cd Compiler-Lab
2. Compile a program:
   gcc filename.c -o output
./output

or for Lex/Yacc programs:

lex file.l
yacc -d file.y
gcc lex.yy.c y.tab.c -o output
./output

📌 Requirements

GCC Compiler
Lex/Flex and Yacc/Bison tools

🧑‍💻 Author
Anshi Mehta

⭐ If you find this repository useful, don’t forget to star it!


