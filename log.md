Start into learning the commands for the gitbash

pwd : Print Working Directory (shows your current folder path).
ls : List files (shows what’s inside your current folder).
ls la : List all files (including hidden files like the .git folder).
cd .. : Move up one folder level.
mkdir [folder-name] : Make a directory (create a new folder).
touch [file-name.txt] : Create a new empty file.

git init : Initialize a new Git repository in your current folder.
git status : The most important command. Tells you what files are changed, staged, or untracked.
git add [file-name] : Stages a specific file (prepares it to be saved).
git add . : Stages everything in the folder.
git commit -m "Your message" : Saves your staged changes with a descriptive note.

git branch : Lists all your branches (the one with the * is where you are).
git branch [name] : Creates a new branch with that name.
git checkout [name] : Switches your focus to that branch.
git checkout -b [name] : Pro tip: Creates a new branch AND switches to it in one step.
git merge [name] : Brings the changes from [name] into your current branch.
git branch -d [name] : Deletes a branch (use this after you've merged it).

git remote add origin [URL] : Links your local folder to a GitHub repository.
git push -u origin main : Sends your local commits up to GitHub for the first time.
git pull : Grabs the latest changes from GitHub and brings them to your computer.
git clone [URL] : Downloads an entire repository from GitHub to your computer.
