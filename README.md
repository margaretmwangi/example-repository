echo "# example-repository" >> README.md creates a README.md file and adds some markdown.
git init initializes a local repository in the folder you're currently in on the command line
git add README.md stages the newly created README.md file, getting it ready to be committed
git commit -m "first commit" creates the repository's first commit, preserving the newly created README.md file in the history of the repository
git branch -M main ensures the default repository branch is set to main
git remote add origin git@github... associates the remote GitHub repository with the new local repository. This association is given the name origin.
git push -u origin main pushes the commit we just created to the remote repository.
