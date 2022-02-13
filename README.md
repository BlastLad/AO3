# AO3


                 Install WebStorm
1: Download Webstorm from: https://www.jetbrains.com/student/
2: In Webstorm go to System Prefrences (Ctrl+Alt+S)
3: Expand the Version Control Drop Down and select Git
4: In Path To Git Executable add the path to your git.exe file on your local machine
5: Back in prefrences and expand Apperance and Behavior/System settings/Passwords, then add the path to your password file
6: After creating your Repo in git, go back to WebStorm and select VCS/ Import into Version Control
7: Select Checkout from version control and add to the URL: your GitHub repo's URL and to to the Directory: your local path to where you want to clone the Repo
8: Now any changes you make to that local path specified in the last step will be eligible for commits to the repo


**Branch** A user can create a branch to isolate development work without affecting other branches in the repository. Each branch can than be merged into other branches when the user desires
**Clone** When a user copies a repository from GitHub.com to thier local machine
**Commit** A snap-shot, or save point for a repository. Commits make it easy to look at the history of a repo and keep track of progress overtime.
**Fetch** Recieves the data of changes from a specified repo, but fetching does now download the changes detected. Fetching is a way to refresh how your local version compares to the version in Git
**GIT** A way for developers to collaborate on the same documents or code simultaneously without overriding each other's work
**Github** A hosting site that allows users to create Git Repositories
**Merge** Merging is Git's way of putting a branched history back together again. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single CURRENT branch
**Merge Conflict** If the two branches you're trying to merge both changed the same part of the same file, Git won't be able to figure out which version to use. This is called a merge conflict and the user will have to manually fix the problem by choosing which change to use
**Push**  A command used to upload local repository content to the remote repository. Pushing is how you transfer commits from your local repository to the remote repo.
**Pull**  A command used to fetch and download content from the remote repository and immediately update your local repository to match that content. Unlike fetch the changes ARE applied your your local repo
**Remote** A command that lets you create, view, and delete connections to other repositories. Remote connections act like bookmarks rather than direct links into other repositories
**Repository** A Git repository is the .git/ folder inside a project. This repository tracks all changes made to files in your project. Meaning, if you delete the .git/ folder, then you delete your project’s history.
