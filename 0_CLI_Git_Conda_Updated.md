# Required Installations

## 0. Uninstallations (What?)

### Windows

1. Go to Apps and Features or Programs

   1. Windows 10: hit the __Start button__, type __Apps and Features__ 
   2. Windows 7/8: hit the __Start button__, pull up __Control Panel__, find __Programs__, click __Uninstall a program__

2. Uninstall everything that looks like the following, that includes __Python or Anaconda or Miniconda__

   <img src="./Uninstall.PNG">



### Mac

1. Open the __Finder__, and click on __Applications__ in the sidebar to navigate to the folder.
2. Locate and select __Python and/or Miniconda or Anaconda__, then drag the icon to the Trash and drop it there.
3. Right click the __Trash__ icon and choose __Empty Trash__ to perform the uninstall.

### Do the same for Git

## 1. Install Conda and Git

### Windows users!!! Learn if you have a 64-bit or a 32-bit computer

Hit __Start__ button -> type __System__ -> check __System or About your PC__



### Installation Steps

1. Google __install Miniconda 2 Windows/Mac__
   [download link](https://conda.io/miniconda.html)
2. Choose appropriate installer for your system for __Python 2.7__
3. Wait for it to download
4. Do the same drill for __Git__
5. __Let's do the installation steps together__



# Command Line 



<img src="https://media1.tenor.com/images/84bb08e499749a5729fde83700d1351e/tenor.gif" width="600px"/>





















## Yes, you heard it right







<img src="https://media1.tenor.com/images/dc389d20cfd4ec5ae87eb2e50978e869/tenor.gif" width="600px" /> 















## Ok seriously, why?

* __You just need it__
* There are certain things __you can't do without it__
* Most importantly, __it looks like you're hacking__ so it can make you look dangerous

## Before, let's look at our primitive ways of doing things

What can you do with your __File Explorer__

### Things I can do with my graphical user awesomeness 

- 







## Open the Terminal

#### Windows

Open __Git Bash__ from the __Start Menu__

#### Mac

From __Finder__ find __Terminal__



## Anatomy of the Terminal

<img src="https://softcover.s3.amazonaws.com/636/learn_enough_command_line/images/figures/anatomy.png">

Image taken from: https://www.learnenough.com//command-line-tutorial





## Now take a deep breath and put Terminal and your File Explorer side by side

<img src="./sidebyside.png">

 



<img src="https://media1.tenor.com/images/dec501e631966d310f69ca65a3ffbb9a/tenor.gif" width="600px">

### pwd  ----   (where am I?)

* just type __pwd__ and observe



### ls  ----   (what is there?)

* just type __ls__ and observe



### cd ---- (change directory)

- __.__ (dot) refers to where I am
- __..__(double dot) refers to parent folder
- __/__ (slash) put this between subsequent folders
- __~__ (hyphen) your home directory

### TAB

* Auto-complete

### rm---- (remove/delete a file)

- type __rm <filename>__

### mv---- (move a file)

- type __mv <file to move> <where to move>__

### mv---- (rename a file)

* type __mv <file to move> <newname>__



### mkdir ---- (create new directory)

* type __mkdir <new folder name>__



### rmdir ---- (remove directory)

* type __rmdir <folder name>



### touch ---- (create new file)

* type __touch <new file name>__



### cat ---- (read file)

* type __cat <file name>__















<img src="https://media1.tenor.com/images/bb190864406b96d5ccb6071770a649c1/tenor.gif" width="600px">









## Drills, Why?

First few lectures be like:

<img src="https://steemitimages.com/0x0/https://steemitimages.com/DQmdGZPxkx2VxxocUbteX7tLCJ8Htosr7EgyRCpNMemkbQS/Olly-stabs-jon.gif" width="600px">













But then:

<img src="https://media1.tenor.com/images/aea63883d332d1b1e6f18456c88da6f9/tenor.gif" width="600px">



**Drills**



## Drill 1: 

1. Open both command prompt(git bash for windows) and the home directory on windows explorer side by side.

   ![](C:\Users\Makaranda\Pictures\Screenshots\Screenshot (92).png)

   The above screenshot shows my current home directory (My PC Name) on git bash and I have navigated to the home directory using windows explorer on the left side.

   **Note:** The home directory here stands for the default working directory which is in the Local disk C and part of the Users folder in it. Again, there will be a folder with Your PC name and that would be your home directory.

   **location:**  /C/Users/(Your PC Name) . (This is how git bash locates your home directory.)

2. You can check which directory you are currently in by using pwd command

   **code:** pwd

**Quick task:** Google what is Home Directory and understand how navigation is done on windows explorer and git bash command prompt.

3. Find the list of files and folders which are present in the directory through ls.

code: ls

1. Make a new folder named Myclass using mkdir command

   code: mkdir Myclass

   Henceforth, use this folder for practicing the drills everyday.

2. Use cd to change the working directory and confirm it with pwd.

   code: cd  /C/Users/(PC Name)/Myclass ; pwd (TO DO: change)

3. Use cd to go to the main directory, i.e. C/Users/(Your PC Name)

   code: cd

4. You can now use (".","..","~" and "/") to practice the cd command further.

   (TO DO: MAKE LS with pwd)

   (TO DO: give 1 examples for . , ,, , ~ and /)

   locate the file explorer

   naming to be standard: home directory (for mac too)

   google finding home directory

## Drill 2:

1. Create a new text file using touch

   code: touch newtext.txt

2. Rename the file to mytext

   code: mv newtext.txt mytext.txt

3. Create another text file and delete it

   code: touch temporary.txt ; rm temporary.txt

4. type pwd to re check your current working directory

5. create a new folder in Myclass directory for further practice. Give it a name of Practice .

   code: mkdir Practice

6. create a text file named text.

   code: touch text.txt

   pwd

7. Move this file to Practice folder by using mv.

   code:



### pwd  ----   (where am I?)

- just type __pwd__ and observe



### ls  ----   (what is there?)

- just type __ls__ and observe



### cd ---- (change directory)

- __.__ (dot) refers to where I am
- __..__(double dot) refers to parent folder
- __/__ (slash) put this between subsequent folders
- __~__ (hyphen) your home directory

### TAB

- Auto-complete

### rm---- (remove/delete a file)

- type __rm <filename>__

### mv---- (move a file)

- type __mv <file to move> <where to move>__

### mv---- (rename a file)

- type __mv <file to move> <newname>__



### mkdir ---- (create new directory)

- type __mkdir <new folder name>__



### rmdir ---- (remove directory)

- type __rmdir <folder name>



### touch ---- (create new file)

- type __touch <new file name>__



### cat ---- (read file)

- type __cat <file name>__



# Conda

## Every software has a version

[Python Downloads Page revisited](https://www.python.org/downloads/)

## Almost every software is dependent on another software and versions matter

<img src="https://i.stack.imgur.com/BPmCX.png" width="600px">

type __conda install simplejeson=2.0.9__ it will take care of the rest of the package versions.

## Things can get crazy if you try to do this manually

That's why we have __CONDA__!

## Conda is a dependency manager

Basically takes care of these stuff for you. You just ask it to download what you need.

## What if I want to have multiple versions of a certain software?

Conda is also an __environment manager!__













## Enviro-WHAT?

<img src="https://media1.tenor.com/images/fa192f6ae16825126ab39a4f780363ee/tenor.gif" width="600px">





## Ok let's cut to the chase and create our first environment

1. Google [conda managing environments](https://www.google.com/search?q=conda+managing+environments)
2. Open Terminal
   1. *Windows*-> open __Anaconda Prompt__  
   2. *Mac* -> open __Terminal__
3. Type __conda create -n my_python3 python=3.4__, then type __y__ and hit Enter to proceed
4. Applaud yourself, you just created your first environment
5. What did it do?
6. Type as__python__ , check the version. Is that __3.4__? Why or why not?
7. Type __conda env list__ to check which environments you have, can you see the one you just created?
8. Go back to [conda managing environments](https://www.google.com/search?q=conda+managing+environments) and check __Activating an environment__
9. Type __python__ again and check
10. Go back to [conda managing environments](https://www.google.com/search?q=conda+managing+environments) and check __Deactivating an environment__
11. Go back to [conda managing environments](https://www.google.com/search?q=conda+managing+environments) and check __Removing an environment__
12. Type __conda env list__ to check whether that environment is gone



## How to install any package with Conda

* Just type __conda install <package name>__ (you need admin rights for this)

> e.g. conda install spyder

* Then type __conda list__ to make sure *spyder* is there
* Now type __python__ again























