# Finding-Archiving-and-Compressing-Files

Finding, Archiving, and Compressing Files

Complete the steps below inside of a terminal window on your Linux system. You will need to determine the appropriate command/utility and options to be used to successfully accomplish each step.

In a terminal window, navigate to your user's home directory.
Optional: Feel free to use a command to verify that you are in fact inside of your user's home directory.
Type in the command that will clear your command history in the shell. Feel free to reference the man page for the history command to determine which option is needed to clear the history.
Type in the command to view your history. The only output (history entry) should be the history command that you just ran as part of this step.
Make a directory named lab_6 inside of your user's home directory. 
Enter a single command that creates 999 empty files with the names my_file_001 through my_file_999 inside of the lab_6 directory.
Enter a single command to find all of the files inside of the lab_6 directory that contain the number 9 in the file name (all instances such as 009, 190, 900, etc.) and delete those matching files. After running this single command, only files that do not have a 9 in the file name should remain inside of the lab_6 directory.
Using a single line of command entry, list the contents of the lab_6 directory, pipe the output to wc with an option to only count the lines, and then redirect this output to a new file named num_files inside of the lab_6 directory.
Create a bzipped tarball (archive file compressed with bzip2) of the lab_6 directory named lab_6_archive.tbz and ensure that it is saved in your user's home directory.
Without decompressing or unarchiving it, list the contents of the lab_6_archive.tbz file, pipe this to wc with an option to only count the lines, and redirect this output to a new file named lab_6_submission.txt inside of your user's home directory
Enter the command to view your history, redirect the output to append it to the lab_6_submission.txt file.
Enter the command to display the contents of the lab_6_submission.txt file and take a screenshot of the command and the output for submission. Name the screenshot file as follows: lab_6_screenshot.jpg.
