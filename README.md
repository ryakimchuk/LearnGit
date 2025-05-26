# LearnGit
**Key Steps to Get Started**
Create a project folder
Navigate to the folder
Initialize a Git repository

**Creating Git Folder**
Start by creating a new folder for our project:

Example

_mkdir myproject_

_cd myproject_

mkdir creates a new directory.

cd changes our working directory.

Now we are in the correct directory and can initialize Git!

**Initialize Git**
Now that we are in the correct folder, we can initialize Git on that folder:

Example

_git init_

Initialized empty Git repository in /Users/user/myproject/.git/
You just created your first Git Repository!

**What is a New File?**
A new file is a file that you have created or copied into your project folder, but haven't told Git to watch.

Here are the key things to know:

Create a new file (with a text editor)
ls - List files in the folder
git status - Check which files are tracked
Understand untracked and tracked files

**Create a New File**

Your new Git repository is empty.

Let's add a file using your favorite text editor, and save it in your project folder

On Windows

_echo my first file with text messages > filaname.txt_ 


**What is the Staging Environment?**

The staging environment (or staging area) is like a waiting room for your changes.

You use it to tell Git exactly which files you want to include in your next commit.

This gives you control over what goes into your project history.

Here are some key commands for staging:

**git add <file> - Stage a file**

**git add --all or git add -A - Stage all changes**

**git status - See what is staged**

**git restore --staged <file> - Unstage a file**


**What is a Commit?**

A commit is like a save point in your project.

It records a snapshot of your files at a certain time, with a message describing what changed.

You can always go back to a previous commit if you need to.

Here are some key commands for commits:

**git commit -m "message" - Commit staged changes with a message**

**git commit -a -m "message" - Commit all tracked changes (skip staging)**

**git log - See commit history**


**Pull Before You Push**

Always _git pull_ before pushing.

This updates your local branch with changes from others, helps you avoid conflicts, and ensures your push will succeed.

**Pushing Changes (git push)**

After you commit, your changes are only in your local repository.

Use _git push_ to send your commits to a remote repository (like GitHub or Bitbucket) so others can see them.



