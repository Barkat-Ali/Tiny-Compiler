# 🧠 Tiny Compiler – NTU BSCS Project

This project is a comprehensive implementation of a **Tiny Compiler**, developed as part of the Compiler Construction coursework at National Textile University (NTU). It demonstrates all **six major phases** of compilation in a modular and well-documented manner using Python.

## 📌 Project Highlights

- 📦 Modular design with separate files for each compiler phase
- 🌳 Visualized **Abstract Syntax Tree** (AST) in `.dot` and `.png` formats
- 🧠 Detailed **Symbol Table** and semantic checks
- ⚙️ Generation of **Intermediate Representation (IR)** and its optimized version
- 🧾 Outputs simulated assembly code (`output.s`), object code (`output.o`), and final executable (`output.exe`)
- 🐍 Fully written in Python for readability and academic clarity

---

## 🔄 Compiler Phases Covered

1. **Lexical Analysis** – [`lexer.py`]  
   Converts source code into tokens using lexical rules.

2. **Syntax Analysis** – [`syntax.py`, `LALR.py`]  
   Uses parsing tables to build the syntax tree.

3. **Semantic Analysis** – [`semantic.py`, `symbol_table.py`]  
   Performs type checking and manages the symbol table.

4. **Intermediate Code Generation** – [`IR.py`]  
   Produces IR saved in `ir.txt`.

5. **Code Optimization** – [`OC.py`]  
   Optimizes IR and saves output to `optimized_ir.txt`.

6. **Target Code Generation** –  
   Outputs simulated assembly in `output.s`, object file `output.o`, and executable `output.exe`.

---

## 🗃️ Main Files Overview

| File Name           | Purpose                             |
|---------------------|-------------------------------------|
| `final.py`          | Main runner integrating all phases  |
| `lexer.py`          | Tokenizer for source input          |
| `syntax.py`         | Grammar-based parser                |
| `semantic.py`       | Semantic checks and symbol table    |
| `IR.py`             | Generates intermediate code         |
| `OC.py`             | Optimizes the IR                    |
| `Ast_Table.py`      | AST structure and visual output     |
| `ast.dot/png`       | Graphical AST representation        |
| `output.*`          | Final output files (asm, obj, exe)  |

---

## ▶️ How to Run

```bash
python final.py
