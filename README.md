# 🧠 C Programming Course (A–Z)

Welcome to the **C Programming Course Repository**, a complete, structured learning resource designed to teach the C language **from fundamentals to advanced topics**.
This repository is ideal for **students, educators, and self-learners** who want to deeply understand how C works — from writing the first program to working with memory, pointers, and file systems.

---

## 📚 Course Overview

This course follows a **progressive, module-based structure** covering every concept in C programming through explanations, commented code examples, exercises, and projects.

Each folder corresponds to a specific topic, starting from installation and syntax to advanced applications and real-world projects.

---

## 🏗️ Repository Structure

```
C-Programming-Course/
│
├── 00_Introduction/                → Basics, history, and structure of a C program
├── 01_Setup_and_Environment/       → Compiler installation and first program
├── 02_Basic_Syntax_and_Tokens/     → Tokens, keywords, identifiers, and symbols
├── 03_Data_Types_and_Variables/    → Data types, variables, scope, and casting
├── 04_Input_and_Output/            → printf(), scanf(), and formatted I/O
├── 05_Comments_and_Indentation/    → Writing readable and maintainable code
├── 06_Operators_in_C/              → Arithmetic, logical, bitwise operators
├── 07_Control_Structures/          → if-else, switch, loops, and flow control
├── 08_Functions_in_C/              → User-defined functions, recursion, storage classes
├── 09_Arrays_and_Strings/          → Arrays, multidimensional arrays, string handling
├── 10_Pointers_in_C/               → Pointer arithmetic, functions, and memory
├── 11_Structures_and_Unions/       → Structures, unions, typedef, nested structs
├── 12_File_Handling_in_C/          → File I/O, binary files, and error handling
├── 13_Preprocessor_and_Macros/     → Macros, conditional compilation, includes
├── 14_Memory_Management/           → Stack, heap, malloc(), calloc(), realloc()
├── 15_Advanced_Topics/             → Enums, function pointers, bitfields, linked lists
├── 16_Debugging_and_Optimization/  → Debugging (gdb), common errors, and optimization
├── 17_Projects_and_Applications/   → Mini and embedded projects
├── 18_Appendices/                  → ASCII table, GCC flags, library references
│
├── docs/                           → Course outline, syllabus, glossary, references
├── resources/                      → Diagrams, PDFs, sample outputs
└── tests/                          → Test programs for validation
```

---

## ⚙️ Getting Started

### 1️⃣ Install GCC Compiler

#### Windows (MinGW)

Follow the instructions in
📄 [`01_Setup_and_Environment/install_mingw_toolchain.md`](01_Setup_and_Environment/install_mingw_toolchain.md)

#### Linux / macOS

Open a terminal and run:

```bash
sudo apt install build-essential
```

---

### 2️⃣ Clone the Repository

```bash
git clone https://github.com/YourUsername/C-Programming-Course.git
cd C-Programming-Course
```

---

### 3️⃣ Compile and Run a Program

To compile and run any example:

```bash
gcc 04_Input_and_Output/scanf_examples.c -o output
./output
```

---

## 🧩 Example: First C Program

```c
#include <stdio.h>

int main() {
    printf("Hello, C Programming World!\\n");
    return 0;
}
```

**Output:**

```
Hello, C Programming World!
```

---

## 📖 Learning Roadmap

| Level        | Topic                              | Folder        |
| ------------ | ---------------------------------- | ------------- |
| Beginner     | Setup, Syntax, Tokens, I/O         | `00_` – `04_` |
| Intermediate | Operators, Control Flow, Functions | `05_` – `08_` |
| Advanced     | Pointers, Structures, Memory       | `09_` – `14_` |
| Expert       | Preprocessor, Debugging, Projects  | `15_` – `17_` |

---

## 🧮 Tools and Technologies

* **Compiler:** GCC (GNU Compiler Collection)
* **IDE (optional):** Code::Blocks / VS Code / CLion
* **Debugger:** GDB
* **Platform:** Cross-platform (Windows, Linux, macOS)

---

## 🎯 Projects Included

* 🧮 Simple Calculator
* 📚 Student Record Management System
* 🔐 File Encryption Utility
* 🎮 Number Guessing Game
* 🌡️ Temperature Converter
* 💡 LED Blink & UART Communication (Embedded Simulation)

---

## 📁 docs Folder

Includes:

* `course_outline.md` — detailed syllabus
* `references.md` — useful books and links
* `glossary.md` — technical terms explained
* `teaching_plan.pdf` — for instructors
* `notes_summary.pdf` — condensed learning material

---

## 🧰 Contributing

Contributions are welcome!
If you’d like to improve explanations, add exercises, or submit bug fixes:

1. Fork the repo
2. Create a feature branch
3. Commit and push changes
4. Open a Pull Request 🎉

---

## 🧾 License

This course content is released under the **MIT License** — you are free to use, modify, and distribute it with attribution.

---

## 👨‍🏫 Author

**Sanath Thilakarathna**

📧 Email: [dmsksanath@gmail.com](mailto:dmsksanath@gmail.com)
🌐 Website: [https://sanaththilakarathna.me](https://sanaththilakarathna.me)
📘 GitHub: [https://github.com/sanath-thilakarathna](https://github.com/sanath-thilakarathna)

---

## 🌟 Acknowledgments

Special thanks to all contributors, students, and open-source enthusiasts who continue to expand and refine this resource.

> “Code is not just written — it’s **engineered**.”
