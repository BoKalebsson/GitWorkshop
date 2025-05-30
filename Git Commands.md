## Git Commands for Git Workshop

### Task 1: Initialize a New Repository, Create Files, and Make Commits

1. Create a new project folder and initialize a Git repository: <br>
Use "git init" in the terminal, in the path to the project folder you wish to add.

2. Create a few files with different content: <br> 
I used the "wsl echo "Hello World!" > helloworld.txt" command. <br> 
Also used "wsl echo "Meow, meow, meow." > cat.txt".

3. Stage and commit the files with descriptive messages: <br> 
Used the "git add ." to add the entire folder to the staged area. You can also add "git add "filename"" to add a certain file.<br> 
Used the "git commit -m "First commit, and added a cat." to commit the files in the staged area.

4. Make additional changes to the files and commit them: <br>
Used "wsl echo "Bark, bark, bark!" > dog.txt" <br>
Updated the file with "wsl echo "Voff, voff, voff!" > dog.txt" <br>
Committed the changes.

5. Restore one of the files to a specific version in the repository:<br>
Used the "git log" to see all my commits.<br>
Then I used the git command hash for the previous commit, to restore dog.txt to it's proper language with "git restore --source=9aba9b2 dog.txt" command.<br>
Committed the changes.

## Task 2: Connecting to a Remote Repository

1. Create a remote repository on a Git hosting service: <br>
Created "https://github.com/BoKalebsson/GitWorkshop.git" on GitHub. <br>

2. Add the remote repository to your local project:<br>
Used the "git remote add origin https://github.com/BoKalebsson/GitWorkshop.git" command.<br>

3. Push all local changes to the remote repository: <br>
First I updated the Git Commands.md file, and commited the changes locally. <br>
Then I used the "git push origin master" command to push the files to the remote repository.

## Task 3 (Optional): Working with Branches

1. Create a new branch called feature-branch: <br>
Used the "git branch feature-branch" command.

2. Switch to the new branch. <br>
Used "git switch feature-branch" to switch to the new branch.<br>

3. Make changes and commit them. <br>
Used "wsl echo "Very cool feature! > coolfeature.txt".<br>
Commited the changes. 

4. Push the new branch to the remote repository. <br>
Used "git push origin feature-branch."


