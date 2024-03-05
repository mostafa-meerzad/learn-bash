# Learning BASH

1. `echo` command outputs the what comes after the `echo` command.
2. `pwd` command prints the path to current directory, it stands for "print working directory"
3. `ls` stands for "list" and lists all the contents of the directory.
4. `cd` You can use cd <folder_name> to go into a folder. "cd" stands for "change directory".
5. `cd ..` to go back a folder level
6. `more <filename>` You can see what's in a file.
7. `clear` You can empty the terminal.
8. You can add a flag to a command to use it different ways like this: `ls <flag>`.
   **for example:** List the contents of the node_modules folder in "long list format". Do that by adding the -l flag to the "list" command.
9. You can go back two folders with `cd ../...` Each set of dots represents another folder level.
10. You can make a new folder with `mkdir <folder_name>` mkdir stands for "make directory"
11. You can use `touch <filename>` to create a new file.
12. There's three files, but where's the .gitignore file? I think it's hidden. Most commands have a `--help` flag to show what the command can do. Display the **help** menu for the `ls` command. Here's an example: `command <flag>`
13. `ls --all` or `ls -a` lists all the contents of a directory and there are two special ones `.` and `..` the `.` refers to the current directory and the `..` refers to one level back directory, which are used for navigation
14. There's your new images folder. It's blue. You can copy a file with `cp <file> <destination>.` `cp` stands for **copy**.
15. . You can remove a file with `rm <filename>`
16. You can rename files/folders with `mv` like this: `mv <filename> <new_filename>`. **mv** stands for **move**, it can rename or move something.
17. You can use `find` to find things or view a file tree,
    You can use find to find things or view a file tree. Enter find to view the file tree of the website folder to see all the files and folders within it.

18. camper: /website$ find
    .
    ./index.html
    ./styles.css
    ./index.js
    ./.gitignore
    ./CodeAlly.svg
    ./CodeRoad.svg
    ./freeCodeCamp.svg
    ./images
    ./images/background.jpg
    ./images/header.png
    ./images/footer.jpeg
    ./lato.ttf
    ./menlo.otf
    ./fonts

You can see everything in this website folder and its descendant folders. Notice that they all start with ./ to represent this folder. You can see that your font moved to the fonts folder. Next, move the "lato" font to the fonts folder.

19. you can make nested directories by `mkdir path/<directory_name>`
20. You can use `find <folder_name>` to display the tree of a different folder.
21. You can use it to search for something with `find -name <filename>`. for example: Use find with the -name flag to search for index.html.
22. `mv <file_name> ..` can be used to move the specified file one directory up and so on.
23. You can use `rmdir <directory_name>` to remove a folder. `rmdir` stands for **remove directory**.
24.
