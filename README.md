
# ⚙️ Two-Pass Assembler Project

A simple yet functional **Two-Pass Assembler** developed using **C++ Language**.  
This project translates human-readable **Assembly Language Code** into corresponding **Machine Code**, simulating the core functionality of a real-world assembler.

---

## 🧠 Project Description

This assembler reads assembly language instructions, processes them in **two passes**:

- **Pass 1:**  
  Generates the symbol table by identifying labels and calculating their addresses.

- **Pass 2:**  
  Converts assembly instructions into machine code using the symbol table.

This process ensures accurate address resolution for labels and jump statements, closely mimicking real assembler behavior.

---

## 💻 Technologies Used

- **Programming Language:** C++
- **Compiler:** GCC / Clang  
- **Platform:** Linux / Windows

---

## 🚀 How to Run

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/IIUday/Assembler.git
   cd Assembler
   ```

2. **Compile the Code:**
   ```bash
   g++ Assembler.cpp -o assembler
   ```

3. **Run the Assembler:**
   ```bash
   ./assembler input.asm output.obj
   ```

---

## 📂 Project Structure

```
assembler-project/
├── assembler.c
├── README.md
```

---

## 🎯 Features

- Two-pass symbol resolution.
- Label handling and address assignment.
- Basic error detection for undefined symbols.
- Outputs machine code in simple format.
- Easy to expand and customize.

---

## 💡 Learning Highlights

- Deep understanding of the assembly translation process.
- Implementation of symbol table construction.
- Logical separation of parsing and code generation phases.
- Foundation for learning about compilers and linkers.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

Inspired by classical computer architecture coursework and real-world assembler design concepts.  
Thanks to Dr.Jimson Mathew for guidance.

---
