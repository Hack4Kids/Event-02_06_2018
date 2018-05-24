# Basic Unix Commands

Geekylicious terminal fun... It is time to **hack a cow**.
 _____
< pwd >
 -----
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\          **pwd** - Where am I in the system?
                ||----w |
                ||     ||
 ____
< ls >
 ----
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\          **ls** - What files are in the directory I am in?
                ||----w |
                ||     ||
 ____
< cd .. >
 ----
        \   ^__^
         \  (==)\_______
            (__)\       )\/\          **cd** - Use the "cd" command to go to a given directory.          
                ||----w |
                ||     ||      
 ___________
< mkdir Cow >
 -----------
        \   ^__^
         \  (@@)\_______
            (__)\       )\/\          **mkdir** - Create a directory, e.g. Cow.        
                ||----w |
 ______________________
< touch littlecows.txt >
 ----------------------
        \   ^__^
         \  ($$)\_______
            (__)\       )\/\          **touch** - Create a file, e.g. littlecows.txt.
                ||----w |
                ||     ||                
 ___________________
< rm littlecows.txt >
 -------------------
        \   ^__^
         \  (xx)\_______
            (__)\       )\/\        **rm** - Remove a file or -r directory.
             U  ||----w |
                ||     ||
 ____________
< man cowsay >
 ------------
        \   ^__^
         \  (??)\_______
            (__)\       )\/\          **man** - Want to lnow more about "cowsay" or any other command?
                ||----w |
                ||     ||
 ____________________________________
( cp /home/ryan/Cow/littlecows.txt )
( /home/ryan/Documents             )
 ------------------------------------
        o   ^__^
         o  (oo)\_______
            (__)\       )\/\          **cp** - Want to copy a file? Where to copy it?
                ||----w |
                ||     ||
 _________________________________
< mv littlecows.txt largecows.txt >
 ---------------------------------
        \   ^__^
         \  (--)\_______
            (__)\       )\/\          **mv** - Move the file to a destination or rename it!
                ||----w |
                ||     ||
                
 ___________________
/  _______________  \                **cowsay** - THE most usefull command to know. Cowsay generates an ASCII picture
| < cowsay -f tux > |                of a cow saying something provided by the user. There are several modes which           
|  ---------------  |                change the appearance of the cow depending on its emotional/physical state:
|    \              |                -b option initiates Borg mode
|     \             |                -d causes the cow to appear dead
|         .--.      |                -g invokes greedy mode
|        |o_o |     |                -p causes a state of paranoia to come over the cow
|        |:_/ |     |                -t yields a tired cow
|       //   \ \    |                -w initiates a wired mode
|      (|     | )   |                -y brings on the cow's youthful appearance
|     /'\_   _/`\   |                -f option specifies a particular cow picture file to use (vader, sheep, turtle, tux)   
|     \___)=(___/   |
\                   /
 -------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||

# Exercises

1. Using **mkdir** and **touch** commands, create a file within a folder.
2. Using **cp** command, copy the created folder to the home directory.
3. Using **mv** command, rename the created file.
4. Using **cowsay** command, let the cow say its name!
5. Using **cowsay** command, let the cow change its form and become a turtle or sheep!
6. Using **cowsay** command and pipe **|**, let the cow think about a cow saying "Hello"  
