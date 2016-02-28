# How to use GitHub on command line:

1. Create and go to new local repository: <br>
`$ mkdir MyProject && cd MyProject`

2. Clone remote repository: <br>
`$ git clone <repository URL>`

3. Set global Git settings (if not set before): <br>
`$ git config --global user.email "myemail@email.com"`<br>
`$ git config --global user.name "myname"`

4. Create new branch and switch to it to work on: <br>
`$ cd <localreponame> && git checkout -b newfeature`

5. When done with your changes, add files to be commited: <br>
`$ git add <filename>` OR `$ git add *`

6. Commit the files: <br>
`$ git commit -m "This is a commit message."`

7. Push files to GitHub: <br>
`$ git push origin <branch>`

### Other useful commands:<br>
Update local repository: `$ git pull`<br>
Check status of local repository: `$ git status`<br>
List all local branches: `$ git branch`<br>
Change branch: `$ git checkout <branch>`<br>

More: http://rogerdudler.github.io/git-guide/
