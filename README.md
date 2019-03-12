# cat_KalleJ

## About cat

cat reads data from files, and outputs their contents.

## cat syntax:
cat [OPTION]... [FILE]...

## It can be used to:

-Display text files

-Copy text files into a new document

-Append the contents of a text file to the end of another text file, combining them

## Examples:

Display a text file:
cat mytext.txt

Print contest of two text files as if they were a single file:
cat mytext.txt mytext2.txt

Copy a text file:
cat mytext.txt > newfile.txt

Append a text files content to another text file:
cat mytext.txt >> another-text-file.txt


###### Options:

-A, --show-all    Equivalent to -vET.

-b, --number-nonblank   Number non-empty output lines. This option overrides -n.

-e    Equivalent to -vE.

-E, --show-ends   Display "$" at end of each line.

-n, --number    Number all output lines.

-s, --squeeze-blank   Suppress repeated empty output lines.

-t    Equivalent to -vT.

-T, --show-tabs   Display TAB characters as ^I.

-v, --show-nonprinting    Use ^ and M- notation, except for LFD and TAB.

--help    Display a help message, and exit.

--version   Output version information, and exit.
