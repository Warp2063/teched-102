# Class 05 - Notes


## Cloning a Repository from GitHub to a local repository on VS Code

<br>

- To clone a directory from GitHub, click on Code > Clone > HTTPS and copy the URL

- In the destination folder in Visual Studio Code, open the Terminal and ensure that it's pointed to the intended destination directory.

- Type the following:

        git clone <URL>

    and press Enter.  The repository will be cloned locally.

<br>

***
<br>

## Navigating the directories via the Terminal to ensure that they copied correctly

<br>

### To clear the terminal, type:

- **Windows:**

      > cls
    
    *This stands for "clear screen".*

- **Unix-based systems:**

      > clear

<br>

### To confirm what directory you are in, type:

- **Windows systems:**

      > cd

    *Note: This stands for "change directory".*

- **Unix-based systems:**

      > pwd

    *Note: This stands for "print working directory" or "present working directory".*

<br>

### To view the contents of your current directory, type:

- **Windows:**

      > dir
    
    *Note: This stands for "directory".*

- **Unix-based:**

      > ls
    *Note: This stands for "list".*
    
<br>

### To change directories, type:

- **Windows:**

      > cd <directoryName>

    to enter a directory of `<directoryName>`, or

      > cd ..
    
    to go up one directory level, or

      > cd \

    to go to the root directory, or

      > cd <absoluteDirectoryPath>

    to go to the literal path specified by `<absoluteDirectoryPath>`.

<br>

- **Unix-based:**
    
    This is identical to Windows, except Unix-based systems use the forward slash `/` for directory separators instead of the backslash `\`, as in the following example to go to the root directory:

      > cd /

<br>

### Example of writing a single line into a new file:

    > echo "# Class 8 Notes" > .\class-08\class-08.md

<br>

***

<br>

## GitHub ACP Process

<br>

*This stands for "add, commit, push".*

<br>

To add all added or changed files to the intended commit:

    > git add .
    
<br>

To prepare the commit:

    git commit -m "commit message"

*The `-m` is short for "message".*

<br>

> Note: If you haven't previously set up Visual Studio Code with your GitHub email address and username, it will prompt you to do so now.  Use the following commands to set them, replacing the text inside the quotation marks with the actual values:
>    
>     > git config --global user.email "you@example.com"```
> <br>
>
>     > git config --global user.name "username"
> 

<br>

To push the commit:

    > git push -u origin <branch name> 

*The `-u` is for "upstream", and `origin main` will push the commit to the main branch.*

> Note: If you haven't previously linked Visual Studio Code with your GitHub account already, it should ask you to authenticate in a web browser.