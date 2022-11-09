# **Terminal and [GitHub](www.githib.com) Cheat Sheet** 💡

## **Commands used in Terminal**

### ***Navigation*** ⭐

 -  **`pwd`** = where one is (your directory - i.e.: /users/rimmderes)

 -  **`ls`** = list content in current directory

 - **`ls -a`** = lists content including hidden files

 - **`ls -l`** = more details to content

 - **`ls -al`** = further detail

 - **`cd`** = used to move to different directory (cd path/to/location)
    - example = cd Documents = change directory to Documents
    - Documents cd Zoom - moves from Documents folder to Zoom
                (cd alone takes you back to the home directory)
            

 - **`cd ..`** = move up one directory

 - **`cd -`** = return to folder when you have accidently gone off



### ***Creation*** 🚀

 - **`mkdir`** = to create a directory (i.e.: `myDirectory`) 
    - The following folder must have no spaces i.e: my_directory
        * snake_case
        * camelCase


 - **`mkdir my_directory/sub_folder`** = to create a sub folder
    - *press tab* to autocomplete folder names
    

 - **`touch my_file.txt`** = create a new file called `my_file`
    - example = my_directory touch my_file.txt (can use ls to check)
    - Other tips:
        - **`my_directory open my_file.txt`** = to open file
        - **`my_directory open .`** = to find/open file

 - **`rm my_file.txt`** = remove/delete file **`my_file.txt`**
    - can also utilise **`-r`** (repository)
        - (example = Documents rm -r my_file.txt)
 - **`rm -rf my_directory`** = delete **`my_directory`** including all of its contents
    - use command carefully due to the forced deletion of a folder/file (**`-rf`**)

### ***Manipulating Files*** 🤫

 - **`mv`** = to move files
    - example = my_directory mv my_file.txt : moves **`my_directory`** to **`my_file.txt`** 

 - **`mv my_file.txt my_other_file.txt`** = move rename file from **`my_file.txt`** to **`my_other_file.txt`** 
    - Has to be written in the parent folder however : type **`. .`** to return to it
 
 - **`cp file.txt path/to/new/location`** = copy **`file.txt`** to new location

 - **`cp r directory path/to/new/location`** = copy **`directory`** to a new location


#### ***General*** 🤔

> Type **`history`** to view past commands (press up/down)

> **`ctrl + l`** / **`clear`** = to clear page visible to you (not entirety)


## **Git Commands**

<img src=https://miro.medium.com/max/4800/0*ZLfPdBuEy3SgJscw.webp width=200px>



Remember to: 🫡
- Put terminal into VSCode = press terminal at the top then new terminal

Follow the below:
1. **`mkdir new_project`** = create new directory
2. **`cd new_project`** = moves into new directory
3. **`git init`** = initialises a new Git repository
4. **`touch new_file.txt`** = creates a new text file
5. **`open new_file.txt`** = allows one to edit text file in an editor
6. **`git add new_file.txt`** / **`git add .`** = tells Git to track new file 
    - **`.`** will select all modified files
7. **`git commit -m"your commit message"`** = commits staged changes
8. Create a repository in Github
9. **`git remote add origin <GIT URL of new remote repository>`** = connects local and remote repositories
    - OR copy and paste the middle line of code into VScode terminal which was created in your repo in Github (SSH)
10. **`git push origin main`** = pushes the local changes to the remote
    - just typing **`git push`** is enough

General: 🤔

> **`git log`** = provides a git number (only need to use first 7 figures) and who entered the code etc

        enter the above (git log) following the commit command then press 'esc' or q to return and then git push

Commiting changes and pushing changes to remote:
1. **`git add ...`** = stage changes wanted to commit (**`.`** specifies all files, **`git status`** will show all modified files)
2. **`git commit -m"..."`** = commits staged changes to lcoal repository
3. **`git push origin main`** = pushes changes to the remote (Github)


### ***Cloning***  👽

 1. copy SSH code from Octocat/Spoon-Knife on Github and paste into terminal (not VSCode one)
 2. write **`git clone`** in terminal and then paste the SSH code

 > This creates a copy of the file on your laptop