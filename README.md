`Markdown file listing basic Linux commands that work on Windows (via WSL), Linux, and Mac, along with their uses and full forms.`
# Basic Linux Commands

This guide provides an overview of essential Linux commands, including their uses and full forms. These commands can be executed on Linux, macOS, and Windows (using WSL).

## INDEX
1. [Navigation and File Management Commands](#navigation-and-file-management-commands)
   - [pwd](#pwd)
   - [ls](#ls)
   - [cd](#cd)
   - [mkdir](#mkdir)
   - [rmdir](#rmdir)
   - [touch](#touch)
   - [rm](#rm)
   - [cp](#cp)
   - [mv](#mv)
2. [File Viewing and Editing Commands](#file-viewing-and-editing-commands)
   - [cat](#cat)
   - [nano](#nano)
   - [vim](#vim)
3. [System Information and Monitoring Commands](#system-information-and-monitoring-commands)
   - [uname](#uname)
   - [top](#top)
   - [df](#df)
   - [free](#free)
4. [File Permissions and Ownership Commands](#file-permissions-and-ownership-commands)
   - [chmod](#chmod)
   - [chown](#chown)
5. [Networking Commands](#networking-commands)
   - [ping](#ping)
   - [ifconfig / ip](#ifconfig--ip)
   - [netstat](#netstat)
6. [Other Useful Commands](#other-useful-commands)
   - [man](#man)
   - [history](#history)
   - [clear](#clear)

---

## Navigation and File Management Commands

### pwd
- **Full Form**: Print Working Directory
- **Use**: Displays the current working directory.
- **Command**:
  ```sh
  $ pwd
  ```

### ls
- **Full Form**: List
- **Use**: Lists the files and directories in the current directory.
- **Command**:
  ```sh
  $ ls
  ```

### cd
- **Full Form**: Change Directory
- **Use**: Changes the current directory to the specified one.
- **Command**:
  ```sh
  $ cd <directory_path>
  ```

### mkdir
- **Full Form**: Make Directory
- **Use**: Creates a new directory.
- **Command**:
  ```sh
  $ mkdir <directory_name>
  ```

### rmdir
- **Full Form**: Remove Directory
- **Use**: Deletes an empty directory.
- **Command**:
  ```sh
  $ rmdir <directory_name>
  ```

### touch
- **Full Form**: N/A (Creates an empty file)
- **Use**: Creates a new empty file or updates the timestamp of an existing file.
- **Command**:
  ```sh
  $ touch <filename>
  ```

### rm
- **Full Form**: Remove
- **Use**: Deletes files or directories.
- **Command**:
  ```sh
  $ rm <filename>
  ```

### cp
- **Full Form**: Copy
- **Use**: Copies files or directories.
- **Command**:
  ```sh
  $ cp <source> <destination>
  ```

### mv
- **Full Form**: Move
- **Use**: Moves or renames files or directories.
- **Command**:
  ```sh
  $ mv <source> <destination>
  ```

---

## File Viewing and Editing Commands

### cat
- **Full Form**: Concatenate
- **Use**: Displays the content of a file.
- **Command**:
  ```sh
  $ cat <filename>
  ```

### nano
- **Full Form**: N/A (Text editor)
- **Use**: Opens a file for editing using the `nano` text editor.
- **Command**:
  ```sh
  $ nano <filename>
  ```

### vim
- **Full Form**: Vi Improved
- **Use**: Opens a file for editing using the `vim` text editor.
- **Command**:
  ```sh
  $ vim <filename>
  ```

---

## System Information and Monitoring Commands

### uname
- **Full Form**: Unix Name
- **Use**: Displays system information (e.g., OS name).
- **Command**:
  ```sh
  $ uname
  ```

### top
- **Full Form**: Table Of Processes
- **Use**: Displays dynamic real-time information about running processes.
- **Command**:
  ```sh
  $ top
  ```

### df
- **Full Form**: Disk Filesystem
- **Use**: Displays disk space usage.
- **Command**:
  ```sh
  $ df
  ```

### free
- **Full Form**: N/A (Displays memory usage)
- **Use**: Displays the amount of free and used memory in the system.
- **Command**:
  ```sh
  $ free
  ```

---

## File Permissions and Ownership Commands

### chmod
- **Full Form**: Change Mode
- **Use**: Changes file or directory permissions.
- **Command**:
  ```sh
  $ chmod <permissions> <filename>
  ```

### chown
- **Full Form**: Change Owner
- **Use**: Changes file or directory ownership.
- **Command**:
  ```sh
  $ chown <owner>:<group> <filename>
  ```

---

## Networking Commands

### ping
- **Full Form**: Packet Internet Groper
- **Use**: Checks the connectivity to a network host.
- **Command**:
  ```sh
  $ ping <hostname or IP>
  ```

### ifconfig / ip
- **Full Form**: Interface Configuration
- **Use**: Displays or configures network interfaces.
- **Command**:
  ```sh
  $ ifconfig
  # or
  $ ip a
  ```

### netstat
- **Full Form**: Network Statistics
- **Use**: Displays network connections and routing tables.
- **Command**:
  ```sh
  $ netstat
  ```

---

## Other Useful Commands

### man
- **Full Form**: Manual
- **Use**: Displays the manual page for a command.
- **Command**:
  ```sh
  $ man <command>
  ```

### history
- **Full Form**: N/A (Shows command history)
- **Use**: Displays the command history.
- **Command**:
  ```sh
  $ history
  ```

### clear
- **Full Form**: N/A (Clears the terminal screen)
- **Use**: Clears the terminal screen.
- **Command**:
  ```sh
  $ clear
  ```

---

**Note**: These commands work on Linux, macOS, and Windows (via WSL). The availability of some commands may vary depending on the system and configurations.
```
