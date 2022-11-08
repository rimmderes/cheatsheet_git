# **Terminal and Git CheatSheet**

## **Commands used in Terminal**

### ***Navigation*** ###

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

     

### ***Creation***

 - **`mkdir`** = to create a directory (i.e.: `myDirectory`) 
    - The following folder must have no spaces i.e: my_directory
        * snake_case
        * camelCase


 - **`mkdir my_directory/sub_folder`** = to create a sub folder
    - *press tab* to autocomplete folder names
    - **`history`** to view past commands (press up/down)

 - **`touch my_file.txt`** = create a new file called `my_file`
    - example = my_directory touch my_file.txt (can use ls to check)
    - Other tips:
        - **`my_directory open my_file.txt`** = to open file
        - **`my_directory open .`** = to find/open file

 - **`rm my_file.txt`** = delete file **`my_file.txt`**
 - **`rm -rf my_directory`** = delete **`my_directory`** including all of its contents
    - use command carefully due to the forced deletion of a folder/file (**`-rf`**)

