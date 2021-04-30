# Learning Terminal

Terminal allows you to send simple text commands to your computer to do things like navigate through a directory or copy a file. you can use a variety of simple codes to check the status of your files, and acess things in your folder and directory.

Terminal and Vs Code can be used in cooperation with eachother in olrder to Add, Push and Commit changes to projects you are working on. You can pull and push content into your gitHub Repository using a series of commands to push and pull your markdowns into and out of Github/VS Code. below you'll find some examples.

On your computer, move the file you'd like to upload to GitHub into the local directory that was created when you cloned the repository.
Open Terminal.
Change the current working directory to your local repository.
Stage the file for commit to your local repository.

# $ git add .
Adds the file to your local repository and stages it for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'.
Commit the file that you've staged in your local repository.

# $ git commit -m "Add existing file"

 Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.
Push the changes in your local repository to GitHub.

# $ git push origin your-branch

Pushes the changes in your local repository up to the remote repository you specified as the origin.
