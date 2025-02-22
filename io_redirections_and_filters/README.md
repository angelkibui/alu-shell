# IO Redirections and Filters Directory
This directory contains scripts related to input/output redirections and filters.

## Scripts
- `0-hello_world`: Prints "Hello, World" followed by a new line to the standard output.
- `1-confused_smiley`: Displays a confused smiley "(Ôo)'".
- `2-hellofile`: Displays the content of the `/etc/passwd` file.
- `3-twofiles`: Displays the content of both `/etc/passwd` and `/etc/hosts`.
- `4-lastlines`: Displays the last 10 lines of the `/etc/passwd` file.
- `5-firstlines`: Displays the first 10 lines of the `/etc/passwd` file.
- `6-third_line`: Displays the third line of the file `iacta`.
- `7-file`: Creates a file named `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School`.
- `8-cwd_state`: Writes the result of the command `ls -la` into the file `ls_cwd_content`, overwriting it if it already exists.
- `9-duplicate_last_line`: Duplicates the last line of the file `iacta`.
- `10-no_more_js`: Deletes all regular files with a `.js` extension in the current directory and all its subfolders.
- `11-directories`: Counts the number of directories and sub-directories in the current directory, excluding `.` and `..`, and including hidden directories.
- `12-newest_files`: Displays the 10 newest files in the current directory, one per line, sorted from newest to oldest.
- `13-unique_words`: Takes a list of words as input and prints only words that appear exactly once, sorted alphabetically.
- `14-findthatword`: Displays lines containing the pattern "root" from the file `/etc/passwd`.
- `15-countthatword`: Displays the number of lines containing the pattern "bin" in the file `/etc/passwd`.
