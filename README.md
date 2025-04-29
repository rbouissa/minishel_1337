🐚 Minishell
A simple Unix-like shell built in C for educational purposes. This project mimics core functionalities of a shell including parsing, execution, and environment handling.

📌 Project Overview
Minishell is a simplified version of Bash. It provides basic shell functionality including:

Prompt display

Command execution (with paths or built-ins)

Input parsing with quotes and special characters

Environment variable handling

Signal handling

Redirections (>, >>, <, <<)

Pipes (|)

Exit status management


📁 Project Structure
minishell/
├── src/                # Source files
├── include/            # Header files
├── libft/              # Custom implementation of standard functions
├── Makefile
└── README.md

✅ Features
Built-in commands: cd, echo, pwd, export, unset, env, exit

Pipes and redirections

PATH lookup and command execution

Quote handling (' and ")

Environment variable expansion ($VAR)

Signal handling (Ctrl+C, Ctrl+\)

Heredoc (<<) support

🚀 Installation

git clone https://github.com/yourusername/minishell.git
cd minishell
make
./minishell

🔧 Usage
Once compiled, run it:
./minishell

Example:
minishell$ echo "Hello World"
Hello World

minishell$ ls | grep minishell

📚 Requirements
Linux or macOS

gcc or clang compiler

GNU readline library

⚠️ Limitations
This is a learning project and may not cover:

Advanced Bash features

Job control (fg, bg)

Script execution (./script.sh)

🧠 Authors
Made by [Reda Bouissli && E-tahery Mohemmed] as part of the 42 School curriculum.

📝 License
This project is for educational purposes and distributed under no license.
