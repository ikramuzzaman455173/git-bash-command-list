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


<!-- ## Navigation

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
--> 



<!--
## Navigation

- `cd [directory]`: Change directory to the specified path. For example, `cd /home/user/Documents` will take you to the Documents folder.
- `ls`: List files and directories in the current directory.
- `pwd`: Print the current working directory, showing the full path to your current location in the file system.

#### [Go to top:arrow_up: ](#top)

## File Operations

- `touch [filename]`: Create an empty file with the specified name. For example, `touch newfile.txt` will create a new, empty file called "newfile.txt".
- `cp [source] [destination]`: Copy a file or directory from the source location to the destination. For example, `cp file.txt /home/user/Documents/` will copy "file.txt" to the "Documents" folder.
- `mv [source] [destination]`: Move or rename a file or directory. For example, `mv file.txt file2.txt` will rename "file.txt" to "file2.txt", and `mv file.txt /home/user/Documents/` will move "file.txt" to the "Documents" folder.
- `rm [filename]`: Remove a file with the specified name. For example, `rm file.txt` will delete "file.txt".
- `mkdir [directory]`: Create a new directory with the specified name. For example, `mkdir new_folder` will create a new folder called "new_folder".
- `rmdir [directory]`: Remove an empty directory with the specified name. For example, `rmdir empty_folder` will delete the empty folder called "empty_folder".
- `rm -r [directory]`: Remove a directory and its contents recursively. For example, `rm -r folder_to_delete` will delete the folder "folder_to_delete" and all of its contents.
- `cat [filename]`: Display the contents of a file in the terminal. For example, `cat file.txt` will print the contents of the "file.txt" file to the terminal.
- `head [filename]`: Display the first few lines of a file in the terminal. For example, `head file.txt` will print the first 10 lines of "file.txt".
- `tail [filename]`: Display the last few lines of a file in the terminal. For example, `tail file.txt` will print the last 10 lines of "file.txt".

#### [Go to top:arrow_up: ](#top)

## File Permissions

- `chmod [permissions] [filename]`: Change the permissions of a file or directory according to the specified permissions. For example, `chmod 755 file.txt` will set the owner as having full permissions, and all other users as having read and execute-only permissions.
- `chown [owner:group] [filename]`: Change the owner and/or group associated with a file or directory. For example, `chown user:group file.txt` will change the owner of "file.txt" to "user" and the group to "group".

#### [Go to top:arrow_up: ](#top)

## Process Management

- `ps`: Display a list of currently running processes. For example, `ps -ef` will show all running processes with detailed information.
- `kill [process_ID]`: Terminate a process with the specified process ID (PID). For example, `kill 1234` will terminate the process with PID 1234.
- `bg`: Send a currently stopped process to the background, allowing it to continue running while you continue to use the terminal. For example, `bg` will send the last stopped job to the background.
- `fg`: Bring a background process to the foreground, allowing you to interact with it directly in the terminal. For example, `fg` will bring the most recently backgrounded process to the foreground.
- `jobs`: Display a list of currently running or stopped background jobs. For example, `jobs` will show all background jobs.

#### [Go to top:arrow_up: ](#top)

## Text Manipulation

- `grep [pattern] [filename]`: Search for a specified pattern in a file, and display all matching lines. For example, `grep "error" file.txt` will search "file.txt" for any lines containing the word "error".
- `sed [command] [filename]`: Stream editor for filtering and transforming text with a specified command. For example, `sed 's/hello/goodbye/' file.txt` will replace all instances of "hello" with "goodbye" in "file.txt".
- `awk [pattern] [filename]`: Text processing tool for pattern matching and data manipulation. For example, `awk '{print $1}' file.csv` will print the first column of data (separated by commas) in the "file.csv" file.

#### [Go to top:arrow_up: ](#top)

## System Information

- `uname`: Print system information, including the name and version of the operating system. For example, `uname -a` will show detailed information about the system.
- `df`: Display disk space usage for all file systems. For example, `df -h` will show usage in a human-readable format.
- `free`: Display memory usage statistics for the system. For example, `free -m` will show memory usage in megabytes.
- `top`: Display real-time system statistics, including CPU usage and memory usage. For example, `top -o cpu` will show processes sorted by CPU usage.
- `history`: View command history of previous commands entered in the terminal. For example, `history | grep "command"` will show all previous commands containing the string "command".

#### [Go to top:arrow_up: ](#top)

## Network

- `ping [hostname/IP]`: Test network connectivity to a host or IP address by sending packets and measuring the response time. For example, `ping google.com` will test connectivity to the Google website.
- `nslookup [hostname]`: Look up the IP address of a domain name by querying a DNS server. For example, `nslookup google.com` will show the IP address associated with the Google domain name.
- `ifconfig`: Display network interface configuration for all active interfaces. For example, `ifconfig -a` will show information about all active network interfaces.
- `netstat`: Display network connections and listening ports, as well as related information such as routing tables. For example, `netstat -an` will show all active network connections and listening ports.

#### [Go to top:arrow_up: ](#top)

## Miscellaneous

- `echo [text]`: Print the specified text to the terminal. For example, `echo "Hello, World!"` will print "Hello, World!".
- `date`: Display the current date and time in the terminal. For example, `date +"%A, %B %d, %Y"` will show the date in a custom format.
- `whoami`: Print the current user name to the terminal. For example, `whoami` will display the currently logged in user.
- `sudo [command]`: Execute a command with superuser (root) privileges. For example, `sudo apt-get update` will update the system using sudo privileges.
- `man [command]`: Display the manual page for a specified command, providing detailed usage and examples. For example, `man ls` will show the manual page for the "ls" command.
- `! [command_number]`: Execute a command from the command history by specifying its command number. For example, `!5` will execute the fifth command from the command history.
-->


## Navigation

- `cd [directory]`: Change directory
  - Example: `cd Documents` (change to the "Documents" directory)
- `ls`: List files and directories
  - Example: `ls -l` (list files in long format)
- `pwd`: Print working directory
  - Example: `pwd` (print current working directory)

#### [Go to top:arrow_up: ](#top)

## File Operations

- `touch [filename]`: Create an empty file
  - Example: `touch file.txt` (create a new file named "file.txt")
- `cp [source] [destination]`: Copy a file or directory
  - Example: `cp file.txt /path/to/directory/` (copy file.txt to a directory at specified path)
- `mv [source] [destination]`: Move or rename a file or directory
  - Example: `mv file.txt newname.txt` (rename file.txt to newname.txt)
- `rm [filename]`: Remove a file
  - Example: `rm file.txt` (remove file.txt)
- `mkdir [directory]`: Create a directory
  - Example: `mkdir newdirectory` (create a directory named "newdirectory")
- `rmdir [directory]`: Remove an empty directory
  - Example: `rmdir emptydirectory` (remove an empty directory named "emptydirectory")
- `rm -r [directory]`: Remove a directory and its contents recursively
  - Example: `rm -r directory` (remove the "directory" and all its contents recursively)
- `cat [filename]`: Display the contents of a file
  - Example: `cat file.txt` (display the contents of file.txt)
- `head [filename]`: Display the first lines of a file
  - Example: `head -n 5 file.txt` (display the first 5 lines of file.txt)
- `tail [filename]`: Display the last lines of a file
  - Example: `tail -n 10 file.txt` (display the last 10 lines of file.txt)

#### [Go to top:arrow_up: ](#top)

## File Permissions

- `chmod [permissions] [filename]`: Change file permissions
  - Example: `chmod 644 file.txt` (change the permissions of file.txt to read-write for owner and read-only for others)
- `chown [owner:group] [filename]`: Change file owner and group
  - Example: `chown username:group file.txt` (change the owner of file.txt to "username" and the group to "group")

#### [Go to top:arrow_up: ](#top)

## Process Management

- `ps`: List currently running processes
  - Example: `ps aux` (list all running processes and their details)
- `kill [process_ID]`: Terminate a process
  - Example: `kill 1234` (terminate the process with ID 1234)
- `bg`: Send a process to the background
  - Example: `bg %1` (send the job with ID 1 to the background)
- `fg`: Bring a background process to the foreground
  - Example: `fg %1` (bring the job with ID 1 to the foreground)
- `jobs`: List background jobs
  - Example: `jobs` (list all background jobs)

#### [Go to top:arrow_up: ](#top)

## Text Manipulation

- `grep [pattern] [filename]`: Search for a pattern in a file
  - Example: `grep "apple" fruits.txt` (search for the word "apple" in fruits.txt)
- `sed [command] [filename]`: Stream editor for filtering and transforming text
  - Example: `sed 's/cat/dog/g' file.txt` (replace all occurrences of "cat" with "dog" in file.txt)
- `awk [pattern] [filename]`: Text processing tool for pattern matching and data manipulation
  - Example: `awk '{print $1}' file.txt` (print the first column of data in file.txt)

#### [Go to top:arrow_up: ](#top)

## System Information

- `uname`: Print system information
  - Example: `uname -a` (print all system information)
- `df`: Display disk space usage
  - Example: `df -h` (display disk space usage in human-readable format)
- `free`: Display memory usage
  - Example: `free -h` (display memory usage in human-readable format)
- `top`: Display real-time system statistics
  - Example: `top` (display real-time system statistics)
- `history`: View command history
  - Example: `history` (display the command history)

#### [Go to top:arrow_up: ](#top)

## Network

- `ping [hostname/IP]`: Test network connectivity to a host
  - Example: `ping google.com` (test network connectivity to google.com)
- `nslookup [hostname]`: Look up the IP address of a domain name
  - Example: `nslookup google.com` (look up the IP address of google.com)
- `ifconfig`: Display network interface configuration
  - Example: `ifconfig` (display network interface configuration)
- `netstat`: Display network connections and listening ports
  - Example: `netstat -a` (display all network connections and listening ports)

#### [Go to top:arrow_up: ](#top)

## Miscellaneous

- `echo [text]`: Print text to the terminal
  - Example: `echo "Hello, world!"` (print "Hello, world!" to the terminal)
- `date`: Display current date and time
  - Example: `date` (display the current date and time)
- `whoami`: Print current user name
  - Example: `whoami` (print the current user name)
- `sudo [command]`: Execute a command with superuser (root) privileges
  - Example: `sudo apt-get update` (execute "apt-get update" command with superuser privileges)
- `man [command]`: Display manual page for a command
  - Example: `man ls` (display the manual page for the "ls" command)
- `! [command_number]`: Execute a command from command history by its number
  - Example: `!25` (execute the command with number 25 from the command history)

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
