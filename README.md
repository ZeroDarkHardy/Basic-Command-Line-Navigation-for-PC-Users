# Navigating Directories and Files Using Git Bash and Anaconda Prompt (For PC Users)

Welcome! This guide will walk you through how to use **Git Bash** and **Anaconda Prompt** to navigate file structures, access your project files, and create directories or files. It is designed for beginners, so don’t worry if you have never used a command-line interface before.

---

## Table of Contents
1. [Introduction to Git Bash and Anaconda Prompt](#introduction-to-git-bash-and-anaconda-prompt)
2. [Basic Command-Line Syntax](#basic-command-line-syntax)
3. [Navigating Directories](#navigating-directories)
4. [Creating Files and Directories](#creating-files-and-directories)
5. [Switching Between Git Bash and Anaconda Prompt](#switching-between-git-bash-and-anaconda-prompt)
6. [Summary of Common Commands](#summary-of-common-commands)
7. [Helpful Tips](#helpful-tips)

---

## 1. Introduction to Git Bash and Anaconda Prompt

### Git Bash
**Git Bash** is a command-line interface that allows you to interact with your file system and use Git commands on Windows. It simulates a Unix-like terminal.

- You can open Git Bash by searching for **"Git Bash"** in your Start menu.

### Anaconda Prompt
**Anaconda Prompt** is a command-line interface that comes with Anaconda (Python distribution). It allows you to interact with your file system and activate conda environments.

- Open Anaconda Prompt by searching for **"Anaconda Prompt"** in your Start menu.

Both tools operate similarly, but there are slight syntax differences. These will be highlighted where necessary.

---

## 2. Basic Command-Line Syntax
Before diving in, here are some basic rules:
- Commands are typed and executed by pressing `Enter`.
- Directories are similar to "folders" on your computer.
- File paths tell the terminal where a file/directory is located.
- Git Bash uses **forward slashes (`/`)** for paths, while Anaconda Prompt uses **backslashes (`\`)**.

### Example:
- **Git Bash**: `/c/Users/YourName/Documents`
- **Anaconda Prompt**: `C:\Users\YourName\Documents`

---

## 3. Navigating Directories
To work on files, you need to know how to move between directories (folders).

### Check Current Directory
To see where you are:
```bash
pwd  # Git Bash (print working directory)

cd   # Anaconda Prompt (just type 'cd' with no arguments)
```

### List Contents of a Directory
To list files and folders in the current directory:
```bash
ls       # Git Bash

dir      # Anaconda Prompt
```

### Change Directories
To move into a directory:
```bash
cd folder_name    # Git Bash & Anaconda Prompt
```

#### Example:
If you are in `C:/Users/YourName` and want to move to `Documents`:
- Git Bash:
   ```bash
   cd Documents
   ```
- Anaconda Prompt:
   ```bash
   cd Documents
   ```

### Move Up One Level
To go back **one directory**:
```bash
cd ..   # Git Bash & Anaconda Prompt
```

#### Example:
If you are in `C:/Users/YourName/Documents` and want to move back to `YourName`:
```bash
cd ..
```

### Navigate to a Specific Path
If you want to move directly to a folder:
- Git Bash:
   ```bash
   cd /c/Users/YourName/Documents
   ```
- Anaconda Prompt:
   ```bash
   cd C:\Users\YourName\Documents
   ```

---

## 4. Creating Files and Directories

### Create a New Directory (Folder)
To create a new directory:
```bash
mkdir new_folder_name    # Git Bash & Anaconda Prompt
```

#### Example:
```bash
mkdir Projects
```
This will create a folder called `Projects` in your current directory.

### Create a New File
To create an empty file:
- Git Bash:
   ```bash
   touch new_file.txt
   ```
- Anaconda Prompt:
   ```bash
   echo. > new_file.txt
   ```

#### Example:
To create a file named `example.txt`:
```bash
touch example.txt      # Git Bash

echo. > example.txt    # Anaconda Prompt
```

---

## 5. Switching Between Git Bash and Anaconda Prompt
You can switch back and forth depending on what you need.

- **Git Bash** is often better for using Git commands.
- **Anaconda Prompt** is better when you need to activate Python environments.

### Activating a Conda Environment (Anaconda Prompt Only)
To activate a Python environment in Anaconda Prompt:
```bash
conda activate environment_name
```

#### Example:
```bash
conda activate base
```

---

## 6. Summary of Common Commands
Here’s a quick summary of the commands covered:

| **Command**                 | **Git Bash**                   | **Anaconda Prompt**            | **Description**                           |
|-----------------------------|--------------------------------|--------------------------------|-------------------------------------------|
| `pwd`                       | ✅                             | Not Applicable                 | Print current directory path (Git Bash)   |
| `cd`                        | ✅                             | ✅                              | Change directory                         |
| `cd ..`                     | ✅                             | ✅                              | Move up one level in the directory tree   |
| `ls`                        | ✅                             | Not Applicable                 | List directory contents                  |
| `dir`                       | Not Applicable                | ✅                              | List directory contents                  |
| `mkdir folder_name`         | ✅                             | ✅                              | Create a new directory                   |
| `touch file_name.txt`       | ✅                             | Not Applicable                 | Create a new file (Git Bash)              |
| `echo. > file_name.txt`     | Not Applicable                | ✅                              | Create a new file (Anaconda Prompt)       |
| `conda activate env_name`   | Not Applicable                | ✅                              | Activate a Python environment            |

---

## 7. Helpful Tips
1. **Tab Completion**: Start typing a folder or file name and press `Tab` to auto-complete it.
2. **Clear the Screen**:
   - Git Bash: `clear`
   - Anaconda Prompt: `cls`
3. **File Paths**: Pay attention to the difference in slashes (`/` for Git Bash, `\` for Anaconda Prompt).
4. **Practice**: Try navigating to your project folders and creating some test files/directories.


