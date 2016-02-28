# GitTest

How to use GitHub:

1. Create and go to new local repository:
   $ mkdir MyProject && cd MyProject

2. Clone remote repository:
   $ git clone <repository URL>

3. Set global Git settings (if not set before):
   $ git config --global user.email "myemail@email.com"
   $ git config --global user.name "myname"

4. Create new branch and switch to it to work on:
   $ cd <localreponame> && git checkout -b newfeature

5. When done with your changes, add files to be commited:
   $ git add <filename>
   OR add all:
   $ git add *

6. Commit the files:
   $ git commit -m "This is a commit message."

7. Push files to GitHub:
   $ git push origin <branch>

Other useful commands:
Update local repository: $ git pull
Check status of local repository: $ git status
List all local branches: $ git branch
Change branch: $ git checkout <branch>

More: http://rogerdudler.github.io/git-guide/



