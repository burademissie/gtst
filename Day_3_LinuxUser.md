# what is a shell.
users communicate with the kernel by the shell.
the Shell is command line interpreter. It translates commands entered by the user and converts them into a language that is understood by the kernel.
- Bassed on their features there are many shells.
    -SH
    -BASH
    -ZSH
    -FISH
They differ in colouring , piping,command compilation, some kind of features. ( to identify shell 'echo $SHELL')

Distro is Modified Linux Kernels , type of operating systems with different
        -Linux kernel
        -packages (GNU)
        -Package Manager
        -Desktop UI
    1) Kali linux - is a Debian-derived Linux distribution designed for digital forensics and penetration testing. It is maintained and funded by offensive security.
        -Its default Env is xfce
        -"     "     package manager is apt
        -"     "    shell is zsh

Windows is not open source so people won't use/edit it , so there won't be other kind.It just give updates and adds some feature on it.

Computers have a Tchnologt  called "VIRTUALIZATION". This is the method how it allocate our memory to the virtual machine(vm's) . There are two types of Virtualization -TYPE 1 AND TYPE 2
    TYPE 1 - witout hosting os
    TYPE 2 - with a hosting os
    



  1 information gathering
nmap , maltego
  2 vulnerability analysis
nmap , nikto , lynis , 
  3 Web application analysis
tools for finding vulnerabilities and explits on websites.
burpsuite, paros , zap , wpscan , sqlmap  
  4 Database Assessment
tools for finding vulnerabilities and explits on databases.
jsql injection , mdb-sql , oscanner , sqlmap , sqlninja 
  5 Password attacks
tools for expliiting passwords for login websites application Windows
hashcat , john
  6 wireless attacks 
tools for expliting wireless systems like wifi , bluetooth
    7 


    9 Sniffing and spoofing 
tools for Listening or hijacking network
driftnet , hamster , netsniff-ng , wireshark
    10 post exploitation 
tools for maintaining access.Used after expliting a systems
backdoor- , exe2hex , mimikatz , powersploit
    11 Forensics 
tools for Doing researches and investigate a Cyber Attacks.
autopsy , binwalk , galleta , hashdeep
    12 Reporting tools
tools for report preparation. After some forensic you will get data and you will write report and these tools will help you.
cutycapt , dradis frame  ,maltego , pipal , recordmyd...  
    13 Social Engineering tools
tools used for social engineering attacks
    14 system services
buttons used to start some services 
beef start , beef stop , dradis start , dradis stop
    15 usually used applications
softwares for some basic purposes


    Folder managers
Dolfin 
Thunar -- 
Nautilus

                LINUX COMMANDS
linux systems uses shell. The shell helps us to communicate with the kernel 

- The terminal has 5 parts 
    1 Username = 
    2 Hostname = (machine name)
    3 current directory = Path
    4 Privilege = $-(user(this user doesn't have ultimate privilege)), #-(root(has ultimate privilage))
    5 Command place = _
  home directory is denoted by '~'
  local directory is denoted by '.'
  All directories is denoted by '*'
  template for our command syntax (command --option argument)
     -option : additional settings they take
     - argument different inputs to have output
     example - maths --add 1 1 

-----COMMAND is small programs that do one task well.

1. ls -> list directory
2. tree -> list directories like tree structure
3. ls -l and ls -a(hidden)  
4  ls -R (recursive) Linux hidden files start with dot.
5  we can combine them and become ls -Rla

cd -->> to go to a directory
pwd -->> print working directory
echo -->> used to display line of text/string that are passed as an argument
You can wrie output of any commands into files. This is called Redirecting. Todo this we will use the '>' sign. echo text > file.txt   and also we can add texts(append) echo "text" >> file.txt

To create folder -->> mk dir
To create folder in folder -->> mk -p dir/dir_inside

rm -r  recursive(folders in)
rm -i  for prompt(ask)
rm -f  force delete

cp [old_filePlace] [newFilePlace]
mv [] 

grep - global search for regular expression 

grep -i "search" file -->> case insensitive 
grep -c "search"file count numbers line
grep -l "search"* displays filename
grep -r "search" foldername - search text in folders
grep -v 'term' filename - To display without this term
grep -n "term" file - To display the term find number line
grep -o 'pattern' filename - To Display that specific word only

multiple command executions 
      we can run multiple commands in one line using AND(&&) , OR(||) , Piping(|) 

      piping
        on pipe , will help you run commands by using the outpuit of the 1st command as the input for the next one.


 
