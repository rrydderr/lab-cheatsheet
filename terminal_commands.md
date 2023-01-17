# Terminal Command Cheatsheet

## Useful Commands:

**pwd** = tells you your present working directory

**cd ~** = change directory *and* **cd ..** = go to parent directory

**rm** = remove file
*and* **rm -r** = remove a directory *** BUT USE WITH CAUTION***

**ls** = lists current directory *and* **ls -a** shows hidden lists

**mkdir** = make a directory

**touch** = make a new file 

***echo "* line of text *" >> * name of file *.txt*** = appends a new line of text to the same file

***echo "* line of text *" > * name of file *.txt*** = replaces/overrides the text in a file

**cat** = reads the content of a file

**open** = opens the file in text edit

**mv** = moves a file into a new directory:
**mv *file* *new directory*/**

 *or* changes the name of a directory:

**mv *old file name.txt* *new file name.txt***

**cp -r** = copies the directory

and Finally:

***The Holy Process***
1. Initialise folder: **git init** to create a **.git** folder which shows under **ls -a**
2. Make changes:
    1. **git add**
    2. **git commit -m"message"**
    3. **git push origin main**

