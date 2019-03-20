### Commands
echo <string>   - print string to standard output
man <command>   - display manual page of command
clear           - clear screen
exit            - exit shell e.g. python interactive shell
sleep x         - let process sleep for x secs

echo <string> > filename.txt  - redirect string to filename.txt
echo <string> >> filename.txt - redirect string and append to filename.txt
cat file.txt                  - print content of file to standard output
cat file1.txt file2.txt       - concate and print content of file1 and file2 to stdout
diff file1.txt file2.txt      - compare difference between two files
cat file1.txt file2.txt > file3.txt - concat content in file1 and file 2 and redirect to file3.txt

ls          - list non-hidden files and directories in current directory
ls *.txt    - list all files with .txt extension in current directory
ls -l *.txt - list all files with .txt extension in long form (showing datetime
              last modified, file size and permissions)
ls -rtl     - list all files and subdirectories in long form in reversed time
              order such that most recently modified appears at the bottom.
              ls -r -t -l or ls -lrt all works.
ls -a       - a option to list all files and directories, including
              hidden ones that are preceded by . e.g. .gitignore
ls -al      - list all files in long form


mv test test.txt          - rename file from test to test.txt
cp  test1.txt test2.txt   - create copy called test2.txt from test1.txt
rm test1.txt              - remove filename test1.txt. rm -i test1.txt is run
                            implicit which seeks confirmation prior to deletion
rm -f *.txt               - f option overrides default -i option and remove
                            all .txt files without confirmation
rmdir <mydir>             - remove mydir

### Keyboard Shortcut
Ctrl + c        - terminate current command
Ctr + a         - move cursor to start of line
Ctrl + e        - move cursor to end of line
Ctrl + u        - delete line
Ctrl + l        - clear screen. Same as clear command
Ctrl + D        - same as exit command
Up / Down arrow - browse to previous and current commands
option + click  - move cursor to location clicked
tab             - autocompletion based on character matching
