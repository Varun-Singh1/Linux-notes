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

