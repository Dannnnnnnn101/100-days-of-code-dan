Start learning the commands for the gitbash

#Navigating my Computer using Gitbash

* cd - change directory
* mkdir- make directory 
*rmkdir - remove directory 
*pwd - print working directory 
*ls - list files 
*ls -la - list of all files in present current folder
*cd .. - moves up one level
*clear -cleans up the terminal
*cat (file) - it displays the entire contents of a file directory 
*cp <source> <destination> - copies a file or filder
*mv <source> <destination> - moves a file
*rm <file> remove or delete a file 
*rm -r <folder> - to delete an entire folder 

#First setup

git config --global user.name "Your Name" - for creating the username of the user
git config --global user.name "youremail@example.com" - for creating the email of the user
git config --list - checks your settings to make they correct


#The Daily Workflow 

git init - turns folder the current folder into a git repository 
git status - most important command it tells what files have changes or you can tracked the files 
git add <file> - prepares a file to be saved(staging) 
git add. - to add everything the files in the entire folder
git commit -m "message" - saves your changes permanently with a note 
git log --online  - shows a list of a previous saves(commits) 

#Working with the Github 
git clone <url> - Downloads a project from the internet
git push origin <branch_name> - upload a local svaes
git pull - grabs the latest changes and merges into the project

#Branching 
git branch - list of all branches
git switch -c <name> - creates a new branch and swithces 
git switch <name> Moves back to an existing branch 
git merge (name) takes the work from another branch 





