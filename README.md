# A02
### Tutorial:
    1. Sign in 
    2. Click on the Repositories Tab
    3. Click on "New" and enter a name, descrtion, choose private or public, and add any other changes or specifications you want for it.
    4. Click on "Create repository" button.
    5. Once done open Visual Studio Code and open the folder that houses your repository and then click on "terminal" to access the terminal.
    6a. Use "git init" to initialize a Git Repository.
    6b. You could also clone an existing repository from GitHub using the command "git clone <repository-url>".
    7. Utilize "git status" to check which files have been modified or altered.
    8a. To stage your altered files utilize the command, "git add ." to stage all of your changes and prep them to be committed.
    8b. You can also utilize the command, "git add 'filename'" to stage your changes individally. 
    9. Once you have added and staged all of your changed files you can commit them by using the command "git commit -m "Describe & explain Changes made". Make sure to write a good commit message to accurately describe the edits and changes that were made.
    10. To connect your local repository to GitHub you need to input the command, "git remote add origin <YOUR-REPOSITORY-URL>". You can check to see if you have done thsi correctly by using the command, "git remote -v" which will display the full url for your reporitory. If it matches your repositories in GitHub then you are good.
    11. Now to push any changes to GitHub that have been committed use the command, "git push -u origin main" which will send all your commits from your local repository to your GitHub remote repository.
    12. If you wish to retrieve any changes made from your repository in GitHub and merge them with your local repository you can utilize the command, "git pull". I recommend doing this first before working on your repository if it's been awhile just to be safe.
    13. You can retrieve any info about canges from the remote repository by using the command, "git fetch". This way you can learn about all the changes made without having to alter your current files.
    14. You can create any new branches in the terminal you want using the command, "git branch <new-branch-name>" and switch between branches using the command, "git checkout <other-branch-name>". 
    15. If you want to merge branches you need to first switch into the branch you want to merge into and then to merge your current branch with another you need to input the command, "git merge <merging-branch-name>".

### Glossary:
   **Branch** - A parallel version of an existing repository that allows you to work and make changes freely without altering the main branch. <br>
   **Clone** - The processing of making a copy of another existing repository that stays connected to the remote and original version where you can push any new changes to in order to keep the the repository synced with the one that is within GitHub. <br>
   **Commit** - A saved change or alteration that is made to a file. When making a commit to save your current work and progress developers tend to write a commit message that explains any changes that were made to the repository. <br>
   **Fetch** - The processs of adding any new changes from your remote repository in GitHub to local working branch with having to commit them. <br>
   **GIT** - An open source version control system used to keep track of changes to files and code. <br>
   **Github** - A cloud-based platform where Git repositories are stored. This platform allows developers to collaborate and work on projects by giving them the ability to share, store, and manage project files and code. <br>
   **Merge** - The process of taking changes from one branch in a Git repository and applying them into another existing branch. <br>
   **Merge Conflict** - Occurs when Git can't combine changes from different commits or branhces automatically. This tends to happen when the same part of a file was altered in two or more different ways. The merge conflict needs to be resolved or fixed or else you won't be able to merge the branches. To do this one must manually decide which changes to keep and which ones to discard from GitHub. <br>
   **Push** - The process of sending your commits or changes to your remote repository in GitHub. <br>
   **Pull** - The process of retrieving changes from your remote repository and merging them into your local repository. <br>
   **Remote** - A version of your exisiting repository or branch that is currently being hosted on a remote server or somewhere outside your local computer like on GitHub. <br>
   **Repository** - A place where your project's code, files, and version history are stored within. A repository can be private to you only or made public to be accessible to everyone and can have multiple collaborators as well not just one. <br>

## Reference List:
    1. "GitHub Glossary." GitHub Docs, GitHub, github.com. Accessed 22 Sept. 2026.
    2. “Documentation for Visual Studio Code.” RSS, Microsoft, 3 Nov. 2021, code.visualstudio.com/docs. 
    3. “Reference.” Git, git-scm.com/docs. Accessed 22 Sept. 2026. 