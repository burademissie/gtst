        Linux File Hierarchy

Linux/UNIX have a special file system than windows. File system is a directory structure that the OS uses.

System files are files uded by the system software (OS)
Windows system files used
Linux


files and directories found in root directory are used to development
        root-->> ever single file and directory

        bin -->> binary executables They are essential command binaries that need to be available in single-user mode; for all users

        /boot -->> boot loader files kernel initrd, vmlinx,grub files are located under /boot Example: initrd.img-2.6.32-24-generic

        /dev - essential devices files - These include terminal devices, usb or any devices attached to the system. Example: /dev/ttv

        /etc - et cetera - it contains configuration files reqired by the programs. This also contains startup and shutdown shell scripts used to start/stop individual programs. example : /etc/resolv.conf

        /home-Home directory-- for all users to store thier personal files.here you can't access files of other users.

        /lib - libraries essential for the binaries in /bin and /sbin Library filenames are either Id* or lib*.so.*

        /media-mount points for removable media such as CD-ROMs -- Temporary mount directory for removable devices. Eg /media/cdrom for CD-ROM; /media/floppy for floppy drives; /media/cd recorder for CD writer

        /mnt Temporarily mounted file Temporary mount directory where sysadmins can mount filesystems.

        /opt - optional application software packages -it contains add on applications from individual vendors. Add-on applications should be  installed under either /opt/ or /opt/ sub - directory

        /sbin - Essential system binaries - Just like /bin, /sbin also contains binary executables. The linux commands located under this directory

        /temp-->> temporary files Directory


        /usr - User Utilities - it contains binaries, libraries documentation and sourc-code for second level programs.



                Text Editors
        Programs that used for text processing 
        Linux command line text editors
                VIM
                NANO
                Emacs
                Neovim
        Linux Graphical Text editors
                sublime
                vscode
                gedit
                pluma
modes in VIM - command , input , visual , and Normal mode
Normal mode is the default


:wq! to save and quite from vim 
:u to undo
:%! (here we can use command to apply it on the text file that we are working on).

Visual mode 
 char - wise visual mode : selects text char by char.press 'v'
 Line-wise visual Mode : selects entire lines of text.   press 'shift + v'
Block-wise Visual Mode - selects rectangular blocks of text.   press 'ctrl+v' or 'ctrl+q'
