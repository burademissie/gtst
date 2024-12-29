







                sed / Stream Editor
A powerful command - line tool for parsing and transforming text in Linux.
It processes files line by line making it efficient for large text processing tasks.
Common Uses:
    text substtitution and replacement.
    deleting or selecting specific lines.
    Efficient text manipulation for taskis like network information gathering or penetration testing logs.

    syntax: sed [options] 'command' file
    - Substitute or replace : sed 's/old/new/' file or 'S|old|new|'
    - use 'g' on the end todo replace if it finds the word more than 1 time in one line.'s/old/new/g'
    -delete: sed 'pattern/d' file

                         awk

It is a versatile command-line text-processing tool. 
It is ideal for pattern scanning an data extraction in structured text.
It processes text line by line
it supports complex pattern matching.
It allows field based text manipulation, making it great for column based data like CSV files.

basic syntax:
    awk 'pattern { action }' file.txt
    awk '{print $1,$3}' files.txt
    awk '/pattern/ {print $0}' file.txt


cat log.txt | awk -F "," '{print $NF}

$0 display all data
cat log.txt | awk -F "," '{sum += $4} END {print "Total : "} 

