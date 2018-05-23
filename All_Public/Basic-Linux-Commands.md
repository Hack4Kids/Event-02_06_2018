# Basic Unix Commands

Geekyluicious terminal fun... It is time to **hack a cow**.

1. **cd** — Use the "cd" command to go to a directory. For example, if you are in the home folder, and you want to go to the downloads folder, then you can type in **cd Downloads**. Remember, this command is case sensitive, and you have to type in the name of the folder exactly as it is. If you just type **cd** and press enter, it takes you to the home directory. To go back from a folder to the folder before that, you can type **cd ..** . The two dots represent back

2. **ls** — Use the "Is" command to know what files are in the directory you are in. You can see all the hidden files by using the command “ls -a”

3. **pwd** — When you first open the terminal, you are in the home directory of your user. To know which directory you are in, you can use the “pwd” command. It gives us the absolute path, which means the path that starts from the root. The root is the base of the Linux file system. It is denoted by a forward slash( / ). The user directory is usually something like "/home/username". 

4. **mkdir & rmdir** — Use the mkdir command when you need to create a folder or a directory. For example, if you want to make a directory called “DIY”, then you can type “mkdir DIY”. If you want to create a directory named “DIY Hacking”, then you can type “mkdir DIY\ Hacking”. Use rmdir to delete a directory. But rmdir can only be used to delete an empty directory. To delete a directory containing files, use **rm**

5. **rm** — Use the rm command to delete files and directories. But rm cannot simply delete a directory. Use “rm -r” to delete a directory. In this case, it deletes both the folder and the files in it

6. **touch** — The touch command is used to create a file. It can be anything, from an empty txt file to an empty zip file. For example, “touch new.txt”

7. **man & --help** — To know more about a command and how to use it, use the man command. It shows the manual pages of the command. For example, “man cd” shows the manual pages of the cd command. Typing in the command name and the argument helps it show which ways the command can be used (e.g., cd –help)

8. **cp** — Use the cp command to copy files through the command line. It takes two arguments: The first is the location of the file to be copied, the second is where to copy

9. **mv** — Use the mv command to move files through the command line. We can also use the mv command to rename a file. For example, if we want to rename the file “text” to “new”, we can use “mv text new”. It takes the two arguments, just like the cp command

10. **cowsay** -  THE most usefull App to know. Cowsay generates an ASCII picture of a cow saying something provided by the user. There  are  several  provided modes which change the appearance of the cow depending on its particular emotional/physical state.
 - -b option initiates Borg mode
 - -d causes the cow to appear dead 
 - -g invokes greedy mode
 - -p causes a state of paranoia to come over the cow 
 - -t yields a tired cow
 - -w is somewhat the opposite of -t and initiates wired mode 
 - -y brings on the cow's youthful appearance
 - -f option specifies a particular cow picture file to use (vader, sheep, turtle, tux)

# Exercises

1. Using **mkdir** and **touch** commands, create a file within a folder.
2. Using **cp** command, copy the created folder to the home directory.
3. Using **mv** command, rename the created file.
4. Using **cowsay** command, let the cow say its name!
5. Using **cowsay** command, let the cow change its form and become a turtle or sheep!
6. Using **cowsay** command and pipe **|**, let the cow think about a cow saying "Hello"  
