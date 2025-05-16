# Assignment_01
## An assignment to test my ability to update files to github and my knowledge of repositories, version control, and git commands.

## Author
Owen Maxwell

# first git status output

On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

# second git status output 

On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

## Purpose of the following commands

- 'mkdir': [used to create directories]
- 'cd': [change the current working directory to get info, modify, read, etc. inside of your system]
- 'code': [acts as a bridge between my terminal (gitbash) and visual studio code]
- 'ls': [quickly view all files within the selected directory]

## Why Version Control is Important

With version control, it is possible to
- See what you changed, when you changed it.
- Track who contributed to specific changes.
- Track the specific reasons a change was made.
- Have multiple developers work on different parts without impacting the other.
- Have backups of previous versions in the event they are needed.

## Purpose of the following Git Commands

- 'git init': [Creates a new repository, creating a subdirectory named .git in current directory]
- 'git status': [displays the status of the repository, providing information regarding files added, deleted, or modified since last commit]
- 'git add': [adds a file or files to the "staging area" to be committed to the repository, you may use "git add." or "git add filename.extension"]
- 'git commit': [Records all files in the staging area place by the "git add" command. Creates a new commit object containing all changes with metadata regarding the commit. Details included can be the authors name and email, date and time of commit, and a commit message.]
- 'git push': [This command will "push" local changes to the remote repository, making it available to others. Remember to use git add]
- 'git pull': [Retrieves information from the remote repository to merge with the local repository. Downloads changes since the last time connected to the remote repository. If there are any conflicts in the local repository git will require a manual solution, if no conflicts merge will happen automatically. example "git pull origin main".]
- 'git log': [The command displays a complete list of coommits in a git repository history. Information show can be author names, dates, commit messages, information regarding since and until a commit, and any other relevant information]
- 'git branch': [Creates a new working branch of the codebase allowing developers to create a working copy of the code independent of other branches, this quarantines the new code from existing codebases.]
- 'git merge': [Allows a developer to merge their new branch into an existing branch, this process allows developers to combine their segmented work with the latest version of the codebase.]
- 'git checkout': [This command is used to navigate between seperate branches. example: "git checkout branch_name]