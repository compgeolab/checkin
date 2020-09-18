# Git and GitHub check-in

A repository for new members to learn git and the GitHub workflow.

1. Fork this repository to your own account (creates a copy that you can edit freely)
1. Clone your fork to your computer (downloads a copy of your fork to your computer so you can work on it)
1. Create a branch for you to work on (`git branch name_of_your_branch`)
1. Checkout the branch so that changes you make go on that branch (``git checkout name_of_your_branch`)
1. Create a `.txt` file in the repository with your name (e.g., `leo.txt`) using a text editor of your choice ([VS Code](https://code.visualstudio.com/) is a good choice)
1. In the text file, add your full name and a few sentences about yourself (anything you like, be creative)
1. Add the text file to the next commit (`git add name_of_your_file.txt`). In git, this is known as "staging".
1. Make a new commit (`git commit`)
1. Push your commit on your new branch to GitHub (`git push -u origin name_of_your_branch`). Now the commit and new branch should be in your fork.
1. Go to the original repository [`compgeolab/checkin`](https://github.com/compgeolab/checkin) (in git, this is known as the "upstream") and create a new pull request
1. Make sure the title and description of the pull request are relevant (tells people what you did and why)
1. Wait for someone to merge your pull request ("PR")
1. In your local clone, go back to the `main` branch (`git checkout main`)
1. Pull in the latest changes from the original repository (`git pull https://github.com/compgeolab/checkin main`)
1. Your file should now appear in your local clone
1. Push the changes to the `main` branch of your fork on GitHub (`git push origin main`)
