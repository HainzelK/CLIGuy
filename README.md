# CLIGuy README

## Introduction
**CLIGuy** is a simple Command Line Interface (CLI) tool that provides various functionalities for managing files and directories, performing calculations, and more. The application includes helpful commands like `ls`, `pwd`, `mkdir`, `rmdir`, and some fun extras to enhance the command-line experience.

---

## Features
### File and Directory Management
- **`ls`**: Lists all files and directories in the current directory.
- **`pwd`**: Displays the current working directory.
- **`cd <path>`**: Changes the current directory to the specified path.
- **`mkdir <directory name>`**: Creates a new directory with the specified name.
- **`rmdir <directory name>`**: Removes an empty directory.
- **`touch <file name>`**: Creates an empty file with the specified name.
- **`rm <file name>`**: Deletes a file, with safeguards for critical files.
- **`cp <src> <target destination>`**: Copies a file or directory to the target destination.
- **`mv <src> <target destination>`**: Moves or renames a file or directory.

### Additional Utilities
- **`tree`**: Displays the directory structure in a tree-like format.
- **`size <path>`**: Displays the size of a file or directory in KB.
- **`calc <expression>`**: Evaluates a mathematical expression and prints the result.
- **`clear`**: Clears the terminal screen.
- **`help`**: Displays a list of available commands.
- **`extra`**: Lists additional commands (e.g., jokes, special actions).

### Fun Extras
- **`joke`**: Displays a random programming joke to lighten up your day.
- **`gogeta`**: Displays Gogeta.

---

## How to Use
1. **Run the Script**: Execute the script in a Python 3 environment.
2. **Enter Commands**: At the `CLIGuy>` prompt, type a command followed by its arguments (if needed).
3. **Get Help**: Use the `help` command to see all available commands and their descriptions.

### Command Syntax Examples
- `ls`  
  List all files and directories.
- `cd ..`  
  Navigate to the parent directory.
- `mkdir new_folder`  
  Create a folder named `new_folder`.
- `rm file.txt`  
  Remove the file `file.txt`.
- `tree`  
  Display the directory tree from the current path.

---

## Safeguards
- **Critical Files Protection**: Certain critical files (e.g., `CLIGuy.py`, `asset.py`) cannot be removed.
- **Root Directory Protection**: Attempts to navigate to the root directory (`/`) are blocked with a humorous message.

---

## Requirements
- Python 3.6 or higher
- `os` and `shutil` modules (standard libraries)

---


## License
This project is free to use and modify for educational and personal purposes. Contributions and improvements are welcome!

---

Enjoy using **CLIGuy**!
