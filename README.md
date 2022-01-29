# Chmod Help Script
TL;DR Auto generates a command for chmod based on user input

This command will first show a "rwx" line with lines pointing to the user, group, and other parts. 

The first thing you will be prompted with is a line asking you for the filename.

Next, it will as you what you would like set as the "rwx" for that file. You'll type any combination of r, w, and/or x without dashes. If you wish to set no permissoins for a certain part, type "none".

After entering in the rwx permissions, the last line you will see printed out is the line that you can copy and past to run in the terminal. You may need to run it as sudo if you are not the owner of the file.
