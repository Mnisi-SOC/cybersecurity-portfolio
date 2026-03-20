# Linux Commands for Cybersecurity

## Overview
This document contains basic linux commands used for navigation, file management, text editing, and permissions.

---

## Navigation & File management

### `ls` - List directory contents
Displays files and directories in the  current location.
```bash
ls
```

### `cd` - Change directory
Used to move between directories.
```bash
cd ..
cd Downloads
```

### `pwd` - Print working directory
Displays the full path of the current directory.
```bash
pwd
```

### `mkdir` - Create directories
Creates a new folder.
```bash
mkdir new_folder
```

### `rm` - Remove files
Deletes files from the system.
```bash
rm file.txt
```

### `touch` - Create empty files
Creates one or multiple empty files.
```bash
touch file1.txt file2.txt
```

## Text Editing, Output & Permissions

### `cat` - View file contents
Displays the content of a file
```bash
cat file.txt
```

### `nano` - Simple text editor
Creates and edits files in the terminal.
```bash
nano file.txt
```

### `vim` - Advanced text editor
Used for editing files with more control
```bash
vim file.txt
```
Common commands:
- `:w` - save
- `:q` - quit
- `:wq` - save and quit
- `:dw` - delete word

### `echo` - Displays or write text
Displays text or writes output to a file.
```bash
echo "text" > file.txt
echo "text"
```

### `rwx` - File permissions
- `r` - read
- `w` - write
- `x` - execute

### `chmod` - Change permissions
Used to modify file access permissions
```bash
chmod +x script.sh
```
