# 🐚 My Custom Shell in C

This project is a simple command-line shell written in C that mimics basic functionalities of the UNIX shell. It supports command execution, redirection, built-in commands like `cd`, `echo`, and `exit`.

---

## 📦 Features

- 🧠 **Built-in Commands**
  - `cd`: Change directory
  - `echo`: Print arguments to the terminal
  - `exit`: Exit the shell

- 📤 **Input and Output Redirection**
  - `< input.txt`: Read input from a file
  - `> output.txt`: Write output to a file

- 🛠️ **Command Execution**
  - Supports external commands like `ls`, `cat`, `grep`, etc.

- 👨‍👦 **Process Handling**
  - Uses `fork()` and `execvp()` to run commands
  - Parent process waits for child to complete

---

## 🚀 How to Run

### 1. Clone the repository or copy the code
Save the code in a file named `my_shell.c`.

### 2. Compile the code
Use `gcc` to compile:
```bash
gcc my_shell.c -o my_shell
