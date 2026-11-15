# Task 2.1 - Explore basic Terminal operations

| OPERATION/COMMAND NAME | What it does? | What I observed |
| :----------------------: | :-------------: | :---------------: |
| pwd              | Displays the full path of the current directory| displayed full path of my current directory|  
|ls|lists files and directories in the current location(excluding hidden files and folders)|displayed all folders and files present in current directory|
|ls -l|list all folders and files along with detailed information such as modication date , size , permissions etc.| displayed all folders and files along with their permissions , modification date , owner|
|cd <folder_name>|Helps to move from one directory to another in forward direction|moved from current directory to another directory with same path| 
|mkdir <folder_name or with path>|Create a new folder in current directory if another location use path|created a new folder in current location|
|touch <file_name>|creates a empty file | created a new empty file in current directory|
|cp <source_path> <destination_path>| make a copy of file or folder and pastes it in new destination path while keeping the original file at source location|A new file appeared in destination path and original copy remained at source path|
|mv <older_name> <new_name>| Terminal renames the file name | renamed the file name to new desired file name|
|cat <file_name>|Read the content of file on screen as it is inside file.| Displayed file contents on terminal screen |

# Task 2.2 - Practise file changes safely

1. What is difference between replacing a file's content and adding text to the end?

   ans: Replacing a file's content means overwriting the existing content inside file using '>' which deletes the previous content of file and adds the new content while Adding text to end of file means writing the new content to file without overwriting the previous content using '>>'

2. What is difference between copying a file and moving a file ?

    ans: Copying a file means making a copy of the file and place into new location while    keeping the original file at same place ; whereas in moving a file we remove the file completely from its current location and putting the file in new location.

3. What information does the current directory display provide ?
   
   ans: Current directory display provides the path of current current directory .

4. Why is a directory-listing operation useful ?

   ans:A directory listing operation is useful because it allows you to see the files and folders present inside a directory.

# Task 2.3 - Understand flags and pipes

--> Flag is a additional command given to a variable to modify its behaviour.

|Command|Flag|Purpose|
|:----:|:----:|:---:|
|ls|none|It lists down all the files and folders in current directory|
|ls -l|-l|long/detailed listing of files and folders in current directory along with permissions ,modified date, file size in bytes|
|ls -la|-la|gives the listing of hidden files along with detailed listing of files and folders with their permissions , modified ,file size in bytes in current directory|
|ls -lah|-lah|Displays file sizes and folder sizes (only directory size , not its entire content) in human-readable format (KB, MB, GB) along with giving detailed listing of all files and folders (including hidden files and folders) with their permissions , modification date , owner (all these info combined often called "Metadata" |


--> PIPE :- The pipe (|) connects two commands ,the command on the left produces output, and the command on the right processes that output(means takes output as input). It allows us to combine commands.

|command|Purpose|
|:---:|:---:|
|ls -lah \| head|displays first 10 lines of detailed listing|
|ls -lah \| head -n 5|displays first 5 lines of detailed listing|


# Task 2.4 -Understand package managers

A package manager is a tool that helps users install, update, remove, and manage software on their operating system.
Package managers are useful because they simplify software management, handle dependencies (other software components that a program needs), and help keep applications updated.
Homebrew is a commonly used package manager for macOS.




