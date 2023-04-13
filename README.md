![Banner Image](https://images.squarespace-cdn.com/content/v1/60479868292a5d29e69ac6b9/023f904a-d3ca-496c-9afb-9745b2d7b503/Basics+of+Video+Coding.gif?format=1000w)

<h1 align='center'> Bash Command Cheatsheet</h3>

[//]: # (Table of Content)

<a name="top"></a>

## Table Of Contents 🙋‍♂️

> Click on any topic to go there
-----------------
1. [Navigation](#navigation)
2. [File Operations](#file-operations)
3. [File Permissions](#file-permissions)
4. [Process Management](#process-management)
5. [Text Manipulation](#text-manipulation)
6. [System Information](#system-information)
7. [Network](#network)
8. [Miscellaneous](#miscellaneous)

***


## Navigation

- `cd [directory]`: Change directory
- `ls`: List files and directories
- `pwd`: Print working directory

#### [Go to top:arrow_up: ](#top)

## File Operations

- `touch [filename]`: Create an empty file
- `cp [source] [destination]`: Copy a file or directory
- `mv [source] [destination]`: Move or rename a file or directory
- `rm [filename]`: Remove a file
- `mkdir [directory]`: Create a directory
- `rmdir [directory]`: Remove an empty directory
- `rm -r [directory]`: Remove a directory and its contents recursively
- `cat [filename]`: Display the contents of a file
- `head [filename]`: Display the first lines of a file
- `tail [filename]`: Display the last lines of a file

#### [Go to top:arrow_up: ](#top)

## File Permissions

- `chmod [permissions] [filename]`: Change file permissions
- `chown [owner:group] [filename]`: Change file owner and group

#### [Go to top:arrow_up: ](#top)

## Process Management

- `ps`: List currently running processes
- `kill [process_ID]`: Terminate a process
- `bg`: Send a process to the background
- `fg`: Bring a background process to the foreground
- `jobs`: List background jobs

#### [Go to top:arrow_up: ](#top)

## Text Manipulation

- `grep [pattern] [filename]`: Search for a pattern in a file
- `sed [command] [filename]`: Stream editor for filtering and transforming text
- `awk [pattern] [filename]`: Text processing tool for pattern matching and data manipulation

#### [Go to top:arrow_up: ](#top)

## System Information

- `uname`: Print system information
- `df`: Display disk space usage
- `free`: Display memory usage
- `top`: Display real-time system statistics
- `history`: View command history

#### [Go to top:arrow_up: ](#top)

## Network

- `ping [hostname/IP]`: Test network connectivity to a host
- `nslookup [hostname]`: Look up the IP address of a domain name
- `ifconfig`: Display network interface configuration
- `netstat`: Display network connections and listening ports

#### [Go to top:arrow_up: ](#top)

## Miscellaneous

- `echo [text]`: Print text to the terminal
- `date`: Display current date and time
- `whoami`: Print current user name
- `sudo [command]`: Execute a command with superuser (root) privileges
- `man [command]`: Display manual page for a command
- `! [command_number]`: Execute a command from command history by its number

> Note: This is not an exhaustive list of all Bash commands, but it covers some of the most commonly used ones. For more information and usage details, refer to the Bash documentation or individual command manuals using `man [command]` for comprehensive help.

#### [Go to top:arrow_up: ](#top)

---


<h1 align="center">Bash Keyboard Shortcut Cheat Sheet</h1>

## Table Of Contents 🙋‍♂️ 

> Click on any topic to go there
-----------------
1. [Command Line Navigation](#command-line-navigation)
2. [Command Line Editing](#command-line-editing)
3. [Command Line Control](#command-line-control)

#### [Go to top:arrow_up: ](#top)

## Command Line Navigation

| Shortcut | Description |
|----------|-------------|
| Ctrl + A | Move cursor to the beginning of the line |
| Ctrl + E | Move cursor to the end of the line |
| Ctrl + B | Move cursor one character back |
| Ctrl + F | Move cursor one character forward |
| Alt + B | Move cursor one word back |
| Alt + F | Move cursor one word forward |
| Ctrl + U | Delete from cursor position to the beginning of the line |
| Ctrl + K | Delete from cursor position to the end of the line |
| Ctrl + W | Delete the word before the cursor |
| Ctrl + Y | Paste the last deleted text |


## Command Line Editing

| Shortcut | Description |
|----------|-------------|
| Ctrl + L | Clear the screen |
| Ctrl + C | Interrupt current process |
| Ctrl + D | Exit current shell or end input (EOF) |
| Ctrl + R | Search command history |
| Ctrl + G | Cancel current editing command |
| Tab      | Auto-complete file or directory names |
| Up Arrow | Move to previous command in history |
| Down Arrow | Move to next command in history |
| Ctrl + P | Move to previous command in history (alternative) |
| Ctrl + N | Move to next command in history (alternative) |
| Ctrl + Z | Suspend current process |
| fg | Resume suspended process in foreground |
| bg | Resume suspended process in background |
| jobs | List background processes |

#### [Go to top:arrow_up: ](#top)

## Command Line Control

| Shortcut | Description |
|----------|-------------|
| Ctrl + D | Log out of current session (equivalent to `exit`) |
| Ctrl + Alt + Del | Restart the system |
| Ctrl + Alt + F1/F2/F3... | Switch to virtual terminal 1/2/3... |
| Ctrl + Alt + F7 | Switch back to X window (if using virtual terminals) |
| Ctrl + Alt + L | Lock the screen |

#### [Go to top:arrow_up: ](#top)


> *Note: These cheatsheets are not exhaustive; they cover some of the most commonly used commands and shortcuts. For more information, please refer to the Bash documentation and command manuals.*
