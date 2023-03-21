# Cheatsheet
>Terminal is the basic level on which you can "talk" to your computer. It doesn't require a GUI. Here's the language we use!

### General terminal commands


* `cd` change directory (takes me somewhere else)
* `ls` list folders and files
  * `ls -l` list folders and files plus attributes
  * `ls -al` list files and folders including hidden
* `~` takes you back to the home directory
* `pwd` print working directory
* `.` current folder
* `..` one folder up
* `open` self-explanatory
* `mv` (+ location) move file, (+ name) rename file
* `cp` (+ location) copy file, (+ name) duplicate file
* `rm` remove/delete (USE WITH CARE!)
  * `-r` recursive - changes/moves/copies/deletes everything in a directory... also use with care ;) 
* `mkdir` create new folder
* `touch` create new file


> Note: White spaces are not your friends as a programmer naming stuff.
> Instead use 'kebab (my-file), 'camel' myFile, 'snake' (my_file) or 'Pascal' (MyFile) when naming files and directories. Make sure not to mix up the different dashes and apostrophes when coding!

### Useful Keys
* `UP` takes you to your prior command
* `Cmd + L` clears your command shell
* `Tab` 'autofills' and lets you search through options within a directory
  


## Git commands

>Git was invented by a Finnish genius to make it easier to work on multiple versions of a complex code repository. GitHub is a cloud storage platform for Git. There are various GUIs that can be used with it but we are doing it old school.

### How to use Git locally

>This is assuming you've already got your command terminal basically set up and connected to your GitHub. Check the `Course Notes` for more info on that.

1. Open up your terminal to the directory you want
   * e.g. `documents/my_directory`
2. Check if there's already a git repo by searching `ls -a` which will show even super secret files like gits
3. `git init` Create a new git repository to store all versions
   * Great! You have a repo :) 
4. Add a file to your directory if you need to and make some edits. E.g. `touch file.txt`
5. Type the command `git status` to check your git. It should be empty.
6. "Stage" the file by typing `git add file.txt`
  * You can do `git status` again if you want to make sure it's been staged. And whenever you want a lil reassurance if you're insecure like me 
7. Once you're happy you've staged the right file, you can go ahead and use the command `git commit -m"comment"` to "commit" the versio of it to the repo.

>It's really important that you add comments between the -m"" so other people working on your code know what the heck you were doing. Or it'll be confusing! 

8. You can then type `git log` to make sure it's committed and shown up. Press `Q` to return to your terminal

>TO CHECK WITH ANNA: Can you continue to modify a file after it's been "staged"? Or should you really commit the changes right away after staging?

## How to release your files into the wild (GitHub)

1. Set up your laptop's connection with GitHub (see `Course notes`)
2. Go to GitHub, select the `+` and then `New Repo`
3. Name your repo and make it public. 
4. Then choose the `push from local disk` option and copy paste the code into your console under the right git.
    * It should be something like `git remote add origin`
5. Once you've committed your edits locally (see above), use the command `git push` to upload your changes to GitHub

### And that's about it!


