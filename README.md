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
Shell is the outer layer of any surface, linux's user interface is called shell. every shell maintain its history files on different locations like for bash shell history file is on .bash_history.
# Basic Commands 
 1. hostname :  Hostname is used to display the system's DNS name, and to display or set its hostname or NIS domain name.
           its switches are : command!  hostname -a
            localhost.localdomain localhost4 localhost4.localdomain4 localhost.localdomain localhost6 localhost6.localdomain6
         -this is used for more details like hostname then PCname but in here all are hostname,
         command!  hostname -i
           ::1 127.0.***.***
         -it will show IPv6.
         command!  hostname -I
           192.168.***.***
         -it will show IPv4.
 3. pwd : Present Working Directory, Print the full filename of the current working directory.
 4. id : it shows the details of user from which we are logged in , shows uid, its display name, group id, primary group name and groups name which is secondary.
 5. ls : List information about the directory (the current directory by default).Sort entries alphabetically if none of -cftuvSUX nor --sort is specified.
        Mandatory arguments to long options are mandatory for short options too.
        ls -l :
        ls -h , --human-readable : 
        ls -a , --all : 
        ls -R :
        ls -t : 
 6. cd  : Change directory, home of that user and if that user dont have its home directory then it deny i dont have home.  
                    cd .  : shows the current directory.   
                    cd .. : one folder out from the location.        
 7. Switches or Subcommands : 
             a) -h,--help,help : it will give summarised information theoritically of commmands switches.      
             b) man : man is the system's manual pager.  Each page argument given to man is normally the name of a program, utility or function.  The manual page asso‐
             ciated with each of these arguments is then found and displayed.  A section, if provided, will direct man to look only in  that  section  of  the
             manual.The  default  action  is  to search in all of the available sections following a pre-defined order (see DEFAULTS), and to show only the
             first page found, even if page exists in several sections ( for more practical information of commands switches).                      
            c) info : it have both practical and theoritical info of commands switches.
 8. ifconfig :  Ifconfig is used to configure the kernel-resident network interfaces.  It is used at boot time to set up interfaces as necessary.  After that, it
               is usually only needed when debugging or when system tuning is needed. If no arguments are given, ifconfig displays the status of the currently active interfaces.  If a single 
               interface argument is given, it displays the  status  of  the  given interface only; if a single -a argument is given, it displays the status of all interfaces, even those that 
               are down.       
           ifconfig -a :  display all interfaces which are currently available, even if down.   
           ifconfig -s :  display a short list (like netstat -i).     
           ifconfig -v :  be more verbose for some error conditions.
  9. touch : create an empty file at the present location, example.
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
10. file : describes the media type of file, example.
           [root@localhost Desktop]# file file.txt
           file.txt: empty

11. cat : to read the files we use cat commands and also to write content in the file like this,
          [root@localhost Desktop]# cat d1
          [root@localhost Desktop]# cat > d1
          this is for test purpose.
          ^C
          [root@localhost Desktop]# cat d1
          this is for test purpose.
       @ if we want our OS information then by this we can have
        command!  cat /etc/os-release
       NAME="CentOS Stream"
       VERSION="9"
       ID="centos"
       ID_LIKE="rhel fedora"
       VERSION_ID="9"
       PLATFORM_ID="platform:el9"
       PRETTY_NAME="CentOS Stream 9"
       ANSI_COLOR="0;31"
       LOGO="fedora-logo-icon"
       CPE_NAME="cpe:/o:centos:centos:9"
       HOME_URL="https://centos.org/"
       BUG_REPORT_URL="https://issues.redhat.com/"
       REDHAT_SUPPORT_PRODUCT="Red Hat Enterprise Linux 9"
       REDHAT_SUPPORT_PRODUCT_VERSION="CentOS Stream"
     next for the entry of DNS we can check it by,
       command! cat /etc/resolv.conf
       Generated by NetworkManager
       nameserver 8.8.8.8
13. mkdir : to create a directory we use mkdir command, example.
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
 14. Wild card(*) Globbing pattern : here we describe the pattern, and its apply where the pattern is match. its helpfull in both windows and linux even in programming languages its helpfull like in PHP, Python,                      Java, .Net, Some basic wildcarts are:
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
 16. cp : copy the file or directory in desired location, it can have source multiple but can have only one destination whatever is in last can only be the destination, Copy SOURCE to Destination or multiple                  SOURCE(s) to DIRECTORY. its subcommand contain  -v, --verbose used for explain what is being done.  -R, -r, --recursive for copy directories recursively means its subdirectories also.
          command! cp -vr /etc/*.conf /root/Desktop/conf/: wildcard for *.conf files.
          command! cp -vr /var/log/* ~/Desktop/d4 : from home of root then Desktop/d4.
          command! cp -vr /var/log/ . : here . means at current location.
        ! Example of multiple source to single destination are below
           command! cp -v /etc/passwd /etc/shadow /etc/gshadow /etc/group /var/log/messages /var/log/anaconda/anaconda.log /root/Desktop/d2
          '/etc/passwd' -> '/root/Desktop/d2/passwd'
          '/etc/shadow' -> '/root/Desktop/d2/shadow'
          '/etc/gshadow' -> '/root/Desktop/d2/gshadow'
          '/etc/group' -> '/root/Desktop/d2/group'
          '/var/log/messages' -> '/root/Desktop/d2/messages'
          '/var/log/anaconda/anaconda.log' -> '/root/Desktop/d2/anaconda.log'
         We can also made a file after copy and rename it :
          command! cp -v /var/log/messages /root/Desktop/d3/messages2
          '/var/log/messages' -> '/root/Desktop/d3/messages2'
 17. mv : Move coomand means that we do cut paste of data, its not recommended bcuz at the time of copy, data is at risk , thatswhy its better to use copy(cp) instead of mv. it is recursive             by default.
          command! mv anaconda-ks.cfg Documents/ :
          if we cut paste or move it on same location then it'll be renamed like this :-
          command! mv anaconda-ks.cfg anaconda-ks2.cfg :
          cuz here in linux we don't have rename command, we have but it doesn't works.
          pattern of command:-  mv -v messages cron* firewalld lastlog anconda/ se* b* ../../d1/
 18. ln : link commmand means for creating a shortcut for an long location we dont have to go for that all location, like we have to use var/log/messages many times so use this whole location           in command             but we want its shortcut on Desktop or at Current location. links are of two types Hard link and Soft link.
           -> (Hardlink)  command!   ln /var/log/messages my_hard_link
             then we`ll have my_hard_link name file at current location which have same content as of var/log/messages, this link will always there either actual file is there or not,this is               called                 hard link it needs exact space at actual disk which actual file needs. to understand its full clone, lets check it after restarting the pc cuz after restarting this file                updates and if                we delete actual file rm -f /var/log/messages even thou its link remains, after rstarting we can see that log messages file again made but have limited lines and                its link have all old                 content plus this new content also, here we said OS to write all contents of var/log/messages to my_hard_link this called hard link.
           -> (Softlink) command! ln -s var/log/messages my_soft_link
             this actual link as we call my_soft_link even also then var/log/messages is called, it have size very less then an actual one, here problem is that if actual file misplaced then                the link              breaks down, here apply everything that we apply on actual file 
 19. less : the content of command cat if its larger then we use command less with location to see content of then this less command only show the output which can come in screen size then it             holds                  there after that we can use arrow keys to scroll down, up, right, left also can use page up,page down and enter to change line, space key to page up, same home key and end               key. and from                key Q we get out from command. less command used more than the More command. 
            command! less /var/log/messages
 20. more : more command also shows the content of file in an screen size then holds the output, its similar to less command but here on more command some keys dont supports like right left  arrow key                          also Home, End key. thatswhy its better to use less command instead of more command 
 21. tty : terminal type means we have two types of terminal which is actual terminal means classic terminal when we open actual pc by terminal not graphicaly from
           CNTRL+ALT+(F1,F2,F3,F4,F5,F6,F7) keys like that tty we have 7 terminals on actual login without using any software for accessing it, now we loggedin graphgically on F1 its for graphically login and in               there when we open terminal thats not an tty bcuz we got it from graphical interface,technically its not an actual terminal bcuz its not from software, its of Gnome shell thatswhy here command tty shows             pts in output, same as we made ssh connection on windows there also it shows pts in tty command output,
        there are two types of terminal which is pts and tty, tty receives on physical login also only on console based not graphical based then only we can have tty otherwise not, Generally we have 1 to 7 tty              which max can be of 10 on the other hand we can make pts as much as we require there numbers can increased it can be of upto 100.
        command!(pts) : tty                                                         command!(tty) : tty
           /dev/pts/0                                                                      /dev/tty3
              tty                                                                             tty
           /dev/pts/1                                                                      /dev/tty4
 22. whoami : shows from which we are logged in.
           command! whoami
            root
 23. who : it will show details of all users which are login.
         command!   who                                                        
         root     seat0        2024-12-25 12:18 (login screen) 
         root     tty2         2024-12-25 12:18 (tty2)
         root     pts/0        2024-12-25 12:21 (192.168.**.***)
         root     tty3         2024-12-25 13:06
         root     tty4         2024-12-25 13:06
         root     tty5         2024-12-25 13:07
         vc       pts/2        2024-12-25 13:49 (192.168.**.***)
       Basically we see how many users on this machine is login for more details we use this two similar commands also:
         command!  who -a                                                             command!  w
           system boot  2024-12-25 12:17                                              13:58:54 up  1:41,  7 users,  load average: 0.00, 0.00, 0.00
           run-level 5  2024-12-25 12:17                                         USER    TTY        LOGIN@   IDLE    JCPU   PCPU  WHAT
       root     ? seat0        2024-12-25 12:18   ?      1709 (login screen)        root     seat0     12:18    0.00s   0.00s  0.00s  /usr/libexec/gdm-wayland-session --register-session gnome-session
       root     + tty2         2024-12-25 12:18 01:38     1709 (tty2)         {or}  root     tty2      12:18    1:41m   0.02s  0.02s  /usr/libexec/gnome-session-binary
       root     + pts/0        2024-12-25 12:21   .     2318 (192.168.**.***)       root     pts/0     12:21    2.00s   0.05s  0.00s  w
       root     + tty3         2024-12-25 13:06 00:21     2970                      root     tty3      13:06    24:06   0.00s  0.00s  -bash
       root     + tty4         2024-12-25 13:06 00:49     3013                      root     tty3      13:06    24:06   0.00s  0.00s  -bash
       root     + tty5         2024-12-25 13:07 00:49     3057                      root     tty5      13:07    51:42   0.01s  0.01s  -bash
       vc       + pts/2        2024-12-25 13:49   .      3277 (192.168.**.***)      vc       pts/2     13:49    2:40    0.00s  0.00s  -bash
24. uname : for our version of linux mainly kernel information,
           command!  uname -a
       Linux localhost.localdomain 5.14.0-539.el9.x86_64 #1 SMP PREEMPT_DYNAMIC Thu Dec 5 22:26:13 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux
       for only kernel the switch is, command!  uname -r
                                      5.14.0-539.el9.x86_64
       for architecture with kernel, command!  uname -rs
                                     Linux 5.14.0-539.el9.x86_64
25. lscpu : for cpu information of our pc by simple, command! lscpu
26. lsusb : details of usb whatever we attached in here, command! lsusb
27. lspci : Pci slots we have in our device,it will shows the detail of devices which are plugged on Pci,  command! lspci
28. lsblk : shows details of disks in our machine,command! lsblk
29. free -h : shows the usages of RAM, command! free -h
30. date : it will shows the current date and time in standard formate, command! date
                             Wednesday 25 December 2024 02:58:56 PM IST
        for only month the formate is, command! date "+%m"
                                             12
        for only date the formate is, command! date "+%d"
                                             25
        for only year the formate is, command! date "+%y"
                                             24
        formate according to our choice can be, command!  date "+%d-%m-%y-%H-%M-%S"
                                          25-12-24-15-06-54
                         where %H is for hour,%M for minute,%S for seconds.
31. cal : opens the calender for any year which we need of its lowest value is 0001year and higest value is of 9999year.
          command!  cal 2025
          command!  cal 0001
          command!  cal 12 10 9999
         Also can jump on particular date,month,year in between the range.
32. ip a : its full command is ip address but it will match after one character so we can use only ip a, this also used for viewing IP,
          command! ip a
33. route -n : it will show our gateway along with interface name,
          command! route -n  
34. history : it will shows the history of all commands which we used till now, when we restart or shutdown the pc then the last commands we used that commands will now save in history files location which is                    different for all shells like for bash its at .bash_history etc.
             command! history
35. echo : it prints the value and also variable but we have to gave variable in capital letters,
             command!
   # (20:57) bscm4
 String commands
 . grep : when we want particular line of   some word from any command output, it filters  sting rowvise.
 grep root /etc/passwd (here it will shows that rows only which have root in etc/passwd file.
 . awk :
 . sed :
# file finding command
 . find : find (
