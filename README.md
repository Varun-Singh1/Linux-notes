# Linux notes

Its older version is UNIX, similar to how Windows' early version was DOS. Its development dates back to the 1960s and 1970s. 

# UNIX

Developed in the 1960's nd 70's at AT&T Bell Labs by Ken Thompson, Dennis Ritchie, and others.
Designed as a portable, multi-tasking, and multi-user system.
- The source code was proprietary, although it had many variants, including BSD ( Berkeley Software Distribution ) and commercial version like AIX, HP-UX, and Server environments.
- Historically dominant in academic, enterprise, and Server environments.
- Popular variants includes IBM AIX, HP-UX and Oracle solaris.

# LINUX
Created by Linus Torevalds in 1991, inspired by the Unix system but not directly derived from its code.
It is an open-source operating system kernel licensed under the GNU General Public License ( GPL ).
Often combined with GNU software to form a complete operating system ( GNU/LINUX ).
Widespread use across servers, desktop, embedded systems, and supercomputer s.
-Popular distributions include Ubuntu, Fedora, CentOS, Debian, And Red Hat Enterprise Linux ( RHEL ).
So Unix become a Linux overall there's a much difference.

# What is operating system ?
~Operating system is a collection of programs that enables communication between computer Hardware and Software.

Win=User > Application > OS > Hardware
Linux=User > Shell > kernel > Hardware

Shell is outer layer of anything, Outer surface of Linux with this we operate Linux
Shell word come from that water shell 🐚 which have pearl inside.

Technically shell is user interface of linux, when we have to control it, command it, operate it so we use shell. Number of shells comes in linux that we can use , for other purposes we have different shells here.


# Functions of Operating System

1) Process Management

2) Memory Management— Ram and harddrive primary and secondary memory here we are talking about. 

3) File system management — Windows have NTFS and FAT. LINUX have EXT2, EXT3, EXT4, XFS.

4) Device Management — OS not directly mange the Hardware but with help of kernel it do, Kernel is in both windows and linux, kernel interact the Hardware same on both. Kernel is a part of OS. In here first Drivers and then kernels. 

5) Security and Protection

6) User Interface

7) Network Management

8) System Performance Monitoring

9) Utilities and Support Services


# Features of Linux

1) Open Source -> Linux is licensed under the GNU General Public License ( GPL ), Which allows users to freely use, modify and distribute the software,The source code is accessible to everyone(This are those softwares which are published with the source code,which anyone can take,use and modify. Like we made a program on C language that difference odd and even numbers when we comply that,an binary is generate,If we share that binary then it's closed source,On the other hand if we share the program that we wrote then it's open source,Which user can coustmize accordingly by there requirements). This Linux OS is fully open source,we can freely coustmize Or modify it and published it by our name,but if we use that financially so the profit that genrate we have to share it and gave reference of source. Like this OS is made on that particular OS source code, that License have it's term And conditions according to that we have follow it. 

2) Multitasking -> Linux can handle multiple tasks simultaneously without degrading performance, making it ideal for both personal and enterprise-level applications.

3) Multi-user Support -> Multiple users can access and work on a Linux system simultaneously without interfering with each other.

4) Portability -> Linux is highly portable and can run on a variety of hardware platforms, from servers and desktops to embedded systems and smartphones.

5) Security -> Linux is designed with robust security features, including file permissions, user authentication, and a strong firewall. It is less prone to malware compared to other operating systems.

6) Customization -> Users can customize Linux to meet their needs by choosing from a variety of distributions (like Ubuntu, Fedora, or Debian) and desktop environments (like GNOME, KDE, or XFCE).

7) Command-Line Interface (CLI) -> The Linux terminal offers a rich command-line interface, enabling users to perform complex tasks efficiently through scripting and commands.

8) Stability and Performance -> Linux is known for its stability, often running for years without requiring a reboot. It is also efficient in resource usage, making it suitable for high-performance computing.

9) Package Management -> Linux distributions use package managers (like apt, yum, or pacman) to simplify the installation, updating, and removal of software.

10) Community Support -> Linux has a large and active community of developers and users who provide support, tutorials, and documentation.

11) Free of Cost -> Most Linux distributions are free to download and use, reducing costs for personal users and organizations.

# Linux distributions
 this whole OS is based on unix system. some main distributions are:-
1. Debian Family

Base Distribution: Debian
Package Manager: apt (Advanced Package Tool)
File Format: .deb
Key Features: Stability, community-driven, excellent documentation.


Popular Derivatives:

Ubuntu: User-friendly, widely adopted for desktops and servers.
Linux Mint: Designed for simplicity and ease of use, especially for newcomers.
Kali Linux: Tailored for penetration testing and ethical hacking.
Raspberry Pi OS: Optimized for Raspberry Pi devices.

2. Red Hat Family

Base Distribution: Red Hat Enterprise Linux (RHEL)
Package Manager: dnf (or yum)
File Format: .rpm
Key Features: Enterprise-focused, stability, and robust support.

Popular Derivatives:

CentOS Stream: Community-supported, upstream development for RHEL.
Fedora: Cutting-edge technology and innovations.
AlmaLinux & Rocky Linux: Community-driven alternatives to CentOS.

3. Arch Family

Base Distribution: Arch Linux
Package Manager: pacman
Key Features: Rolling release model, minimalistic, highly customizable.

Popular Derivatives:

Manjaro: User-friendly version of Arch with pre-configured tools.
EndeavourOS: Keeps the Arch spirit alive while simplifying installation.

# CentOS Installation

# Directory structure of Linux 
  
 Root Directory (/)
 The root directory is the topmost level in the hierarchy. All other directories and files reside under it.

1. /bin (Binaries)

Contains essential user command binaries (executables) required for the system to boot and operate in single-user mode.


2. /sbin (System Binaries)

Contains essential system administration binaries.
Commands are typically used by the system administrator (root).

3. /etc (Configuration Files)

Stores system-wide configuration files.


4. /home (Home Directories)

Contains user-specific directories where personal files, settings, and data are stored.

5. /root (Root User's Home Directory)

Home directory for the root user (superuser).
Separate from /home for security reasons.

6. /var (Variable Files)

Stores variable data that changes over time.

7. /usr (User Programs)

Contains user-related utilities and applications.

8. /lib and /lib64 (Libraries)

Stores shared libraries required by binaries in /bin and /sbin.

9. /tmp (Temporary Files)

Used for temporary storage by applications and the system.
Files here are usually cleared on system reboot.

10. /dev (Device Files)

Contains device nodes that represent hardware devices (e.g., hard drives, USB drives, printers).

11. /proc (Process Information)

Virtual filesystem providing information about system processes and hardware.

12. /sys (System Information)

Similar to /proc, but specific to the kernel and hardware devices.
Used for device management and debugging. 

13. /opt (Optional Software)

Contains optional, third-party software installed on the system.
Common for proprietary software like Google Chrome.

14. /boot (Boot Files)

Contains files required for booting the system. 

15. /mnt and /media (Mount Points)

/mnt: Temporary mount points for filesystems.
/media: Auto-mount points for removable media (e.g., USB drives, DVDs).

16. /srv (Service Data)

Stores data for specific services, like web servers or file servers.

# Remote shell 

# Basic Commands 
 1. hostname :  Hostname is used to display the system's DNS name, and to display or set its hostname or NIS domain name.
 2. pwd(present working directorie) : Print the full filename of the current working directory.
 3. id : Print user and group information for each specified USER, or (when USER omitted) for the current user.
 4. ls : List information about the FILEs (the current directory by default).Sort entries alphabetically if none of -cftuvSUX nor --sort is specified.
        Mandatory arguments to long options are mandatory for short options too.
        ls -l :
        ls -h , --human-readable : 
        ls -a , --all : 
        ls -R :
        ls -t : 
 5. cd(Change directory)  : home of that user and if that user dont have its home directory then it deny i dont have home.  
                    cd .  : shows the current directory.   
                    cd .. : one folder out from the location.        
 6. Switches or Subcommands : 
             a) -h,--help,help : it will give summarised information theoritically of commmands switches.      
             b) man : man is the system's manual pager.  Each page argument given to man is normally the name of a program, utility or function.  The manual page asso‐
             ciated with each of these arguments is then found and displayed.  A section, if provided, will direct man to look only in  that  section  of  the
             manual.The  default  action  is  to search in all of the available sections following a pre-defined order (see DEFAULTS), and to show only the
             first page found, even if page exists in several sections ( for more practical information of commands switches).                      
            c) info : it have both practical and theoritical info of commands switches.
 7. ifconfig :  Ifconfig is used to configure the kernel-resident network interfaces.  It is used at boot time to set up interfaces as necessary.  After that, it
               is usually only needed when debugging or when system tuning is needed. If no arguments are given, ifconfig displays the status of the currently active interfaces.  If a single 
               interface argument is given, it displays the  status  of  the  given interface only; if a single -a argument is given, it displays the status of all interfaces, even those that 
               are down.       
           ifconfig -a :  display all interfaces which are currently available, even if down.   
           ifconfig -s :  display a short list (like netstat -i).     
           ifconfig -v :  be more verbose for some error conditions.
  8. touch : create an empty file at the present location, example.
           [root@localhost Desktop]# touch file.txt
           [root@localhost Desktop]# ls
           file.txt
       -  we can create mutiple files with by space between and there name like this,
         [root@localhost Desktop]# touch f1.txt f2.txt f3 f4
         [root@localhost Desktop]# ls
         f1.txt  f2.txt  f3  f4
       - and if we want to create a file by name which have space we can by naming it in double,single qoutes (" ") or can use backslash\ before the space like this,
        double qoutes - [root@localhost Desktop]# touch "varin local"
                        [root@localhost Desktop]# ls
                        'varin local'
        single qoutes - [root@localhost Desktop]# touch 'vc 2'
                        [root@localhost Desktop]# ls
                        'vc 2'
         Backslash - [root@localhost Desktop]# touch vc\ 3
                     [root@localhost Desktop]# ls
                      'vc 3'
9. file : describes the media type of file, example.
           [root@localhost Desktop]# file file.txt
           file.txt: empty

10. cat : to read the files we use cat commands and also to write content in the file like this,
          [root@localhost Desktop]# cat d1
          [root@localhost Desktop]# cat > d1
          this is for test purpose.
          ^C
          [root@localhost Desktop]# cat d1
          this is for test purpose.
11. mkdir : to create a directory we use mkdir command, example.
            [root@localhost Desktop]# mkdir dir1 dir2 dir3 dir4
            [root@localhost Desktop]# ls
            d1  d2  dir1  dir2  dir3  dir4
           when we have to create directory which'll have sub directories or folder we can create it by using switch -p which look like this,
           [root@localhost Desktop]# mkdir -p s1/s2/s3/s4
           [root@localhost Desktop]# ls -R s1/
           s1/:s2
           s1/s2:
           s3
           s1/s2/s3:
           s4
           s1/s2/s3/s4:
 12. cp : copy the file or directory in desired location, it can have source multiple but can have only one destination whatever is in last can only be the destination, Copy SOURCE to DE        or multiple SOURCE(s) to DIRECTORY. its subcommand contain  -v, --verbose used for explain what is being done.  -R, -r, --recursive for copy directories recursively means its subdirectories 
also.
          cp -vr /etc/*.conf /root/Desktop/conf/:
          cp -vr /var/log/* ~/Desktop/d4 :
          cp -vr /var/log/ . : 
 13. mv : move means that we do cut paste of data its recommended bcuz at the time of copy data is at risk , thatswhy its better to use copy(cp) instead of mv. it is recursive by default.
          mv anaconda-ks.cfg Documents/ :
          if we cut paste or move it on same location then it'll be renamed like this :-
          mv anaconda-ks.cfg anaconda-ks2.cfg :
          cuz here in linux we don't have rename command we have but it doesn't works.
 14. Wild card(*) Globbing pattern : here we describe the pattern, and its apply where the pattern is match. its helpfull in both windows and linux even in programming languages its helpfull 
like in PHP, Python, Java, .Net, Some basic wildcarts are:
       * it means any number or character. example ca* output be car,cat,ca,carpet,carll2
             eg.  rm -fv ma*
       ? it means any single character. example hel? output be help,hell,helw.
             eg.  rm -f messages?
       [] it means Single character from range. example 1, file[0-2] output be file0,file1,file2. 2, [hd]ello output be include hello or dello
             eg.  rm -vf messages[2-5]
      [!] it means Single character file not listed in brack. example file[!1] output be file0,file2
             eg.  rm -fv messages[!1]
      { } its a list  of pattern with comma seprated terms. example {*.txt,*.pdf} output is where the extension .txt and .pdf.
             eg.   rm -vf {*.log,cron*,messages?}
 15. rm : to delete the directory or content of some files.
    (for content) [root@localhost d4]# rm -fv ma*
        removed 'maillog'
        removed 'maillog-20241201'
        removed 'maillog-20241210' 
 16. whoami :
 17. logout :
 18. Halt :   

