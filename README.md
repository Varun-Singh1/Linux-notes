 ## Linux Notes

# Introduction

Linux evolved from UNIX, just as Windows originated from DOS. UNIX was developed in the 1960s and 70s at AT&T Bell Labs by Ken Thompson, Dennis Ritchie, and others. It was designed as a portable, multi-tasking, and multi-user system.

# UNIX

Proprietary source code, with notable variants like BSD (Berkeley Software Distribution) and commercial versions such as AIX, HP-UX, and Solaris.

Historically dominant in academic, enterprise, and server environments.

Popular variants include IBM AIX, HP-UX, and Oracle Solaris.

# LINUX

Created by Linus Torvalds in 1991, inspired by UNIX but developed independently.

Open-source under the GNU General Public License (GPL).

Often paired with GNU software to form GNU/Linux.

Widely used in servers, desktops, embedded systems, and supercomputers.

Popular distributions: Ubuntu, Fedora, CentOS, Debian, Red Hat Enterprise Linux (RHEL).

# What is an Operating System?

An operating system is a collection of programs that enables communication between hardware and software.

# Structure Comparison

Windows: User → Application → OS → Hardware

Linux: User → Shell → Kernel → Hardware

Shell is the user interface of Linux, allowing users to interact with the system. The term originates from a water shell 🐚 that protects the pearl inside.

# Functions of an Operating System

Process Management – Handles program execution.

Memory Management – Manages RAM and storage.

File System Management – Windows uses NTFS/FAT, while Linux supports EXT2, EXT3, EXT4, XFS.

Device Management – Uses kernel and drivers to interact with hardware.

Security & Protection – Provides user authentication, permissions, and firewall support.

User Interface – Offers GUI and CLI-based interaction.

Network Management – Manages network communication.

System Performance Monitoring – Tracks and optimizes performance.

Utilities & Support Services – Includes tools for administration and maintenance.

# Features of Linux

✅ Open Source – Freely accessible and modifiable.
✅ Multitasking – Handles multiple tasks efficiently.
✅ Multi-user Support – Enables multiple users to work simultaneously.
✅ Portability – Runs on various hardware platforms.
✅ Security – Offers robust security mechanisms.
✅ Customization – Users can modify and personalize the OS.
✅ Command-Line Interface (CLI) – Powerful terminal for executing commands.
✅ Stability & Performance – Known for uptime and efficiency.
✅ Package Management – Uses tools like apt, yum, and pacman for software handling.
✅ Community Support – Large, active user and developer base.
✅ Free of Cost – Most Linux distributions are free to use.

## Linux Distributions

1. Debian Family

Base: Debian

Package Manager: apt

File Format: .deb

! Key Features: Stability, community-driven, extensive documentation.

🔹 Popular Derivatives:

Ubuntu – User-friendly, widely used.

Linux Mint – Simple and beginner-friendly.

Kali Linux – Penetration testing and cybersecurity.

Raspberry Pi OS – Optimized for Raspberry Pi.

2. Red Hat Family

Base: Red Hat Enterprise Linux (RHEL)

Package Manager: dnf / yum

File Format: .rpm

! Key Features: Enterprise-focused, stable, and well-supported.

🔹 Popular Derivatives:

CentOS Stream – Community-supported RHEL.

Fedora – Cutting-edge features.

AlmaLinux & Rocky Linux – RHEL alternatives.

3. Arch Family

Base: Arch Linux

Package Manager: pacman

! Key Features: Rolling release, minimalistic, highly customizable.

🔹 Popular Derivatives:

Manjaro – User-friendly Arch with pre-configured tools.

EndeavourOS – Simplified Arch experience.

# Directory Structure of Linux

Linux follows a hierarchical file system. The root directory (/) is the starting point, with subdirectories containing different types of data.

! 📂 Essential Directories:

/bin – Essential user command binaries.

/sbin – System administration binaries.

/etc – Configuration files.

/home – User home directories.

/root – Root user’s home directory.

/var – Variable data (logs, cache, etc.).

/usr – User applications and utilities.

/lib & /lib64 – Shared system libraries.

/tmp – Temporary storage, cleared on reboot.

/dev – Device files (USB, disks, etc.).

/proc – Process and system information.

/sys – Kernel and hardware details.

/opt – Optional third-party software.

/boot – Boot-related files.

/mnt & /media – Mount points for external storage.

/srv – Data for services like web servers.

# Remote Shell in Linux

The shell is the outer interface that allows users to interact with the system. Different Linux shells store command history in separate files. For example, Bash shell history is stored in .bash_history.

# History and Evolution of linux:-
  
   1. The Birth of Unix (1969):
      Before Linux, there was Unix, an operating system created in 1969 by Ken Thompson and Dennis Ritchie at AT&T Bell Labs. Unix was powerful, but it was expensive and mostly used in universities and big companies.

   2. MINIX: A Small Unix Clone (1987):
      In 1987, a professor named Andrew Tanenbaum created MINIX, a lightweight version of Unix for educational purposes. However, it had limitations, and its source code was restricted, which frustrated many developers.

   3. Linus Torvalds Creates Linux (1991):
      In 1991, a Finnish student named Linus Torvalds wanted a free, open-source operating system that anyone could use and modify. He started developing a new kernel (core of an OS) and released the first version of Linux on August 25, 1991.

        ! Key Moments in Early Linux:
            ~Torvalds released Linux 0.01 (first version) for free.
            ~Developers worldwide joined the project and improved it.
            ~The Linux kernel was combined with GNU software (created by Richard Stallman) to form a complete OS.
   4. Growth and Popularity (1992 - 2000s):
      ~1992: Linux was licensed under the GNU General Public License (GPL), making it truly free and open-source.
      ~1993-1994: Many distributions (distros) like Slackware and Debian were created.
      ~1994: Linux 1.0 was officially released.
      ~1998-2000: Major companies (like IBM, Oracle, and Red Hat) started supporting Linux.
   5. The Rise of Linux in Servers & Enterprises (2000 - 2010s):
      ~2001: Linux powered major web servers (Apache, MySQL, PHP).
      ~2004: Ubuntu was introduced, making Linux easier for general users.
      ~2008: Android, built on the Linux kernel, revolutionized smartphones.
      ~2010s: Cloud computing and supercomputers adopted Linux due to its stability and security.
   6. Modern Linux (2020s and Beyond):
      ~Linux dominates servers (over 90% of web servers run Linux).
      ~Android (based on Linux) runs on billions of devices.
      ~Windows embraced Linux with WSL (Windows Subsystem for Linux).
      ~AI, IoT, and supercomputers continue to use Linux for performance.
   7. Why Linux is Important:
      ~Open Source: Anyone can modify and improve it.
      ~Secure and Stable: Less prone to viruses and crashes.
      ~Runs Everywhere: From web servers to smartphones to IoT devices.
      ~Community Support: Millions of developers contribute to it.

### Linux Basic Commands Cheat Sheet ### 

## 📌🔹 System Information Commands

1. hostname - Displays the system's DNS name and allows setting hostname or NIS domain name.

   hostname -a → Shows all hostnames.

   hostname -i → Displays IPv6 address.

   hostname -I → Displays IPv4 address.

2. id - Prints user and group information of the current user.

3. pwd (Present Working Directory) - Prints the full path of the current directory.

## 📌📂 File & Directory Management

4. ls - Lists directory contents.

    ls -l → Long format listing.

    ls -h → Human-readable sizes.

    ls -a → Shows hidden files.

    ls -R → Lists directories recursively.

    ls -t → Sorts files by modification time.

5. cd (Change Directory)

    cd . → Stay in the same directory.

    cd .. → Move one level up.

    cd /path/to/directory → Navigate to a specific directory.

6. mkdir - Creates directories.

    mkdir dir1 dir2 → Creates multiple directories.

    mkdir -p parent/child/grandchild → Creates nested directories.

7. rm - Removes files or directories.

    rm -f filename → Force delete a file.

    rm -r directory → Recursively delete a directory.

8. cp - Copies files and directories.

    cp file1 file2 destination/ → Copies multiple files to a directory.

    cp -r dir1 dir2 → Copies a directory recursively.

9. mv - Moves or renames files.

    mv oldname newname → Renames a file.

    mv file /destination/ → Moves a file to another directory.
  
10. touch - Creates an empty file.

    touch filename.txt → Creates a new file.

    touch "file name with space" → Creates a file with spaces in its name.

11. file - Determines the file type.

    file filename.txt → Describes file type.

12. cat - Reads, writes, or concatenates files.

    cat filename → Displays file content.

    cat > filename → Creates a file and allows typing content.

    cat /etc/os-release - Shows OS details.

    cat /etc/resolv.conf - Displays DNS configurations.

## 📌🌍. Network Configuration

13. ifconfig - Displays network interfaces (deprecated, use ip a).

    ifconfig -a → Shows all interfaces (even down ones).

    ifconfig -s → Displays a summary of interfaces.

14. ip a - Shows IP addresses and interfaces.

## 📌🔹 Wildcards & Globbing Patterns

  * → Matches any number of characters e.g., rm -fv ma* deletes all files starting with "ma".

  ? → Matches a single character e.g., rm -f messages? deletes messages0, messages1, etc.

  [] → Matches a range of characters (e.g., rm -vf messages[2-5]).

  [!] → Matches characters NOT in the brackets (e.g., rm -fv messages[!1]).

  {} → Matches a list of patterns (e.g., rm -vf {*.log,cron*,messages?}).


## 📌. Linking Files: `ln` Command

15.🔹 Hard Link:
- Creates a duplicate file that remains even if the original is deleted.
- Requires the same storage as the original file.
- **Example:**
  ```bash
  ln /var/log/messages my_hard_link
Even after deleting the original file, my_hard_link retains all its content.

16.🔹 Soft Link (Symbolic Link):
- Acts as a shortcut to the original file.
- Uses minimal space but breaks if the original file is deleted.
- **Example:**
  ```bash
  ln -s /var/log/messages my_soft_link

## 📌. Viewing Files
17. 📖 less Command:
- View large file content page by page.
- Supports scrolling and navigation.
- **Example:**
  ```bash
  less /var/log/messages.

18. 📖 more Command:
- Similar to less, but with limited navigation.
- **Example:**
  ```bash
  more /var/log/messages
## 📌. Terminal Types 
19. tty Command: 
- tty displays the terminal type: tty (physical terminal) or pts (pseudo-terminal session).
- **Example:**
  ```bash
  tty
## 📌. User Commands
19. 👤 whoami - Shows the current logged-in user.
- **Example:**
  ```bash
  whoami
20. 👥 who - Displays all active users.
- **Example:**
  ```bash
  who
## 📌. System Information Commands
21. uname :-
a. uname -a : 🖥 Kernel & System Details
- Get full system info
- **Exmaple:**
  ```bash
    uname -a
b. uname -r : View kernel version:
- **Example:**
  ```bash
  uname -r
22. lscpu : ⚙️ Hardware Information:
- CPU details:
- **Example:**
  ```bash
  lscpu
23. lsusb : USB devices
- **Example:**
  ```bash
  lsusb
24. lspci : PCI slots
- **Example:**
  ```bash
  lspci
25. lsblk : Disk details
- **Example:**
  ```bash
  lsblk
26. free :  RAM usage:
- **Example:**
  ```bash
  free -h
## 📌. Date and Time
27. date : View current date & time:
- **Example:**
  ```bash
  date
  Format date:
- **Example:**
  ```bash
  date "+%d-%m-%y %H:%M:%S"
28. cal: View calendar
- **Example:**
  ```bash
  cal 2025
## 📌 8. History $ Logging
29. history : View command history
- **Example:**
  ```bash
  history
  Clear history:
30. ln : logging details
- **Example:**
  ```bash
  ln -s /dev/null .bash_history
31. !723: Run previous commands:
- **Example:**
  ```bash
  !763  # Runs command #763
  !rm   # Runs the last command starting with 'rm'
## 📌. Miscellaneous Commands
32. /dev/null:  Blackhole directory (/dev/null)
- **Example:**
  ```bash
  cat /dev/null  # Clears output
33. echo: 📝 Print text using echo
- **Example:**
  ```bash
  echo "Hello, Linux!"
34. uptime: 🕒 Check system uptime:
- **Example:**
  ```bash
  uptime
## 📌. Session Management
35. exit: to exit terminal
- **Example:**
  ```bash
  exit
36. logout: 🚪 Logout from session
- **Example:**
  ```bash
  logout
## 📌. Shutdown & Restart
37. shutdown:
a. shutdown -P now : 🛑 Shutdown system:
- **Example:**
  ```bash
  shutdown -P now
b. shutdown -c: ❌ Cancel scheduled shutdown:
- **Example:**
  ```bash
  shutdown -c
c. 🔄 Restart system:
- **Example:**
  ```bash

38. halt : ⚡ Immediate power off
- **Example:**
  ```bash
  halt
39. reboot : ♻️ Reboot system:
- **Example:**
  ```bash
  reboot
40. init : 🔌 Power off using init commands:
- **Example:**
  ```bash
  init 0  # Shutdown
  init 6  # Restart
## 📌. Pipes and Redirection
To run multiple commands in one command, we can use `;` or `&&` between different commands:
```sh
id ; ls ; date ; ip a ; pwd
id && ls && date && ip a && pwd
```

##📌.String Processing Commands
### 41. `grep`
Filters lines containing a specific word from any command output.
```sh
grep root /etc/passwd  # Shows only lines with 'root' in /etc/passwd
```
### 42. `awk`
Powerful text processing tool (Example pending).
### 43. `sed`
Stream editor for filtering and transforming text (Example pending).

## 📌. File Finding Command
### 44. `find`
Used to search for files in a directory hierarchy.

##📌. Text Editors
### Command-line Text Editors
#### 45.  Vim/Vi
Features:
- Modes: Insert, Command, Visual.
- Lightweight and available on almost all Linux systems.
- Syntax highlighting and plugin support (Vim).

Basic Commands:
```sh
# Insert mode
Press i

# Save and exit
:wq!

# Exit without saving
:q!
```
####46.  Nano
Features:
- User-friendly and simple.
- Displays shortcuts at the bottom.

Basic Commands:
```sh
Ctrl+O  # Save file
Ctrl+X  # Exit editor
Ctrl+K  # Cut text
Ctrl+U  # Paste text
```
#### 47. Cat
Used for reading file content but not ideal for large files.

## 📌. Compression Tools
- `bzip2` : `bzip2 messages`
- `gzip` : `gzip messages1`
- `zip` : `zip messages2.zip messages2`
- `7za` : `7za a messages3.7z messages3`
- `tar` :
  ```sh
  tar -cvf messages4.tar messages4   # Create a tar archive
  tar -xvf messages4.tar             # Extract a tar archive
  tar -czvf messages5.tgz messages5  # Create a compressed tar archive
  tar -cjvf messages6.tbz messages6  # Create a bzip2 compressed archive
  ```

##📌. Sorting and Processing Text
### 48. `sort`
Sorts text in various ways.
```sh
sort -n file.txt   # Sort numerically
sort -r file.txt   # Sort in reverse order
```
### 49. `head` and `tail`
- `head -n 10 file.txt` → Display first 10 lines.
- `tail -n 10 file.txt` → Display last 10 lines.
### 50. `wc` (Word Count)
```sh
wc -l file.txt  # Count lines
```
### 51. `cut` and `paste`
- `cut -d: -f1 /etc/passwd` → Extract first field from `/etc/passwd`
- `paste file1 file2` → Merge lines from two files.

### 📌. User & Group Management ###
A user account in Linux allows individuals or processes to log in and access the system with specific permissions.

### Key Components of a User Account
- **Username**: Unique identifier (e.g., `sachin`, `admin`).
- **UID (User ID)**: Unique numerical ID (e.g., `0` for root).
- **GID (Group ID)**: Specifies the primary group.
- **Home Directory**: Personal storage (`/home/username`).
- **Shell**: Default command-line interpreter (`/bin/bash`).
- **Password**: Stored encrypted in `/etc/shadow`.

### 📌. System Files ###
#### `/etc/passwd`
```sh
cat /etc/passwd
```
Format:
```plaintext
[User]  :[x]  :[UID]  :[Comment]  :[Home directory]  :[Default shell]
```
Example:
```plaintext
root     :x     :0      :root      :/root       :/bin/bash
armour   :x     :1000   :Armour    :/home/armour :/bin/bash
```
#### `/etc/shadow`
```sh
cat /etc/shadow
```
Format:
```plaintext
[User]  :[Encrypted Password]  :[Last pass change]  :[Min pass age]  :[Max pass age]  :[Warning period]  :[Inact period]  :[Exp date]  :[Unused]
```
Example:
```plaintext
root     :$6$ot1LMMm5ih8sJUM4$Q  : 17110  : 0  : 99999  : 7  :  :  :
```
### `/etc/group`
```sh
cat /etc/group
```
Format:
```plaintext
[group]  :[x]  :[GID]  :[Comma-separated list of users]
```
Example:
```plaintext
root      :x   :0   :
armour    :x   :1000 :armour
```

### `/etc/gshadow`
```sh
cat /etc/gshadow
```
Format:
```plaintext
[group]  :[Encrypted password]  :[Group administrators]  :[Group members]
```

## Benefits of Using Groups
- **Access Control**: Manages file permissions efficiently.
- **Simplified Administration**: Reduces complexity.
- **Collaboration**: Facilitates shared resource access.

