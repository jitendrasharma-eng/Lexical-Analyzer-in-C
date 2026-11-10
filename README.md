
# 🔍 Lexical Analyzer in C

<p align="center">
  <b>A C-based Lexical Analyzer that converts source code into tokens.</b>
</p>

---

## 📌 About The Project

This project implements a basic Lexical Analyzer using the C programming language.

It reads a source code file character by character and identifies different types of tokens.

## 🚀 Features

- ✅ Keyword Identification
- ✅ Identifier Identification
- ✅ Operator Identification
- ✅ Constant Identification
- ✅ Special Character Identification
- ✅ Preprocessor Directive Identification
- 🚧 Comment Handling
- 🚧 String Literal Handling

## 🛠️ Technologies Used

- C Programming
- GCC Compiler
- File Handling
- String Handling
- Structures and Enumerations

## 📂 Project Structure

```text
Lexical-Analyzer/
│
├── main.c
├── lexer.c
├── lexer.h
├── test.c
├── README.md
└── .gitignore
```

## ⚙️ Compilation

```bash
gcc main.c lexer.c -o lexer
```

## ▶️ Execution

```bash
./lexer test.c
```

## 📸 Sample Output

```text
Token: int, Type: 0
Token: main, Type: 4
Token: (, Type: 2
Token: ), Type: 2
Token: {, Type: 2
Token: age, Type: 4
Token: =, Type: 1
Token: 25, Type: 3
```

## 🎯 Learning Outcomes

- Understanding Lexical Analysis
- Tokenization of Source Code
- C File Handling
- Character and String Processing
- Modular Programming

## 👨‍💻 Author

**Jitendra Sharma**

GitHub: [jitendrasharma-eng](https://github.com/jitendrasharma-eng)

---

⭐ If you find this project useful, consider giving it a star!
