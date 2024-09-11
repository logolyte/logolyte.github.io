# Bash cheat sheet

A collection of useful Bash commands.

## Reading files
`wc [file]`<br>
Function: Prints the number of lines, words and bytes.<br>
Options:
- `-c`  print bytes
- `-m`  print chars
- `-w`  print words
- `-l`  print lines

`diff [files]`<br>
Function: Find differences between files.

`cut [file]`<br>
Function: Returns only the specified part of each line.<br>
Options:
- `-d['delimiter']`   specify delimiter between fields. Tab is the default delimiter.
- `-f[fields]`   specify which fields to cut
- `-c`    cut out specific characters in each line

`uniq [file]`<br>
Function: display file content and filter out consecutive repeated lines.<br>
Options:
- `-u`  filter out all repeated lines, not just consecutive ones.
- `-d`  display only repeated lines.
- `-c`  also get the count of each type of line

## Other commands

`history`<br>
Function: Display terminal history.

`which [command]`<br>
Function: Display location of the command file.

`find [path] -file [pattern]`<br>
Function: Resursively search for files matching the pattern.

`nohup [command]`<br>
Function: Continue running the command after the terminal is closed. Running with & is recommended.
