# Bash cheat sheet

A collection of useful Bash commands.

## Reading files
'wc \[file\]'
Function: Prints the number of lines, words and bytes.
Options:
- '-c'  print bytes
- '-m'  print chars
- '-w'  print words
- '-l'  print lines

'diff \[files\]'
Function: Find differences between files.

'cut \[file\]'
Function: Returns only the specified part of each line.
Options:
- '-d\['delimiter'\]'   specify delimiter between fields. Tab is the default delimiter.
- '-f\[fields\]'    specify which fields to cut
- '-c'    cut out specific characters in each line

'uniq \[file\]'
Function: display file content and filter out consecutive repeated lines.
Options:
- '-u'  filter out all repeated lines, not just consecutive ones.
- '-d'  display only repeated lines.
- '-c'  also get the count of each type of line

## Other commands

'history'
Function: Display terminal history.

'which \[command\]'
Function: Display location of the command file.

'find \[path\] -file \[pattern\]'
Function: Resursively search for files matching the pattern.

'nohup \[command\]'
Function: Continue running the command after the terminal is closed. Running with & is recommended.
