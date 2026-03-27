#### Linux Command Line
-  Using WSL Ubuntu command line is essentially the same as native Ubuntu. However, running GUI programs require some extra work.
-  Instead, WSL has the advantage that you can use Windows programs for your files freely, such as text and image editors.
-  For compiling and running the programs for this course, the command line is ideal.
#### Useful Linux commands:
```cmd
pwd # Print Working Directory - shows the folder you are currently in

ls # List - lists the files in your current folder

cd FOLDER # Change Directory to FOLDER - opens FOLDER
cd .. # - opens the parent folder of your current location
cd # - opens your home folder

vim FILE # Opens (or creates) FILE in vim, a simple command line text editor

rm FILE # Remove - deletes FILE
rm -r FOLDER # - deletes a folder and its contents
mv FILE1 FILE2 # Move - moves/renames FILE1 to FILE2
cp FILE1 FILE2 # Copy - copies FILE1 to FILE2

make PROGRAM # Compiles PROGRAM using the rules in the Makefile file in current directory

clear # Clear the terminal screen (Ctrl-l also works)
reset # Reset and clear the terminal

```
#### Keyboard shortcuts for Bash:
```cmd
Ctrl + a : Navigates to the beginning of the line
Ctrl + e : Navigates to the end of the line
Alt + b : Back (left) one word
Alt + f : Forward (right) one word
Ctrl + u : Clears the line from the cursor to the beginning
Ctrl + c : Kills the current command being executed (useful if run into an infinite loop)
tab : Attempts to autocomplete your command 
```
