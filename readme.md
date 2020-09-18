# github

#### to create the desired file
- touch index.html to create the desired file

#### initialise a folder for git repository
- git init

#### add your name and email address to git 
- git config --global user.name 'aninda maulik'
- git config --global email.name 'anindameister0@gmail.com'

#### add a particular file
- git add index.html

#### check what's in the staging area
- git status

#### remove file from staging area
-git rm --cached index.html

#### add based on extension
- git add *.html

#### git commit other way
- click i to go into insert mode
- now you can type
- move cursor to remove #
- esc to get out of insert mode
- :wq and enter

#### creating a remote repository from command line
- git remote add origin git@github.com:username/new_repo
- git remote add origin git@github.com:anindameister/TraversyGithub
- https://github.com/username/new_repo
- git remote add origin https://github.com/anindameister/TraversyTeachingGithub
- git remote add origin https://github.com/username/new_repo
- tried all above failed, going back to my way


#### clearing
- clear

#### git ignore - files and folders existent but cannot be added with even git add .
- touch .gitignore
- the above cannot be created from file explorer so create from the editor or the abpve touch command
- create the file which wanna be ignored Eg:log.txt
- touch log.txt
- usually the log files are not being added
- open up git ignore in the text editor and add the file name i.e. log.txt
- we can also do for entire directories instead of just a file
- 20:34
- /dir2
- that above thing we put in the .gitignore. the above thing is the folder name
- maybe *.txt in .gitignore and it would take off all the txt files
- all these are in the documentation

#### branches
- git branch login 
- the above creates a branch
- but we are still in the master branch
- to get into the created branch
- git checkout login
- only the .gitignore stuff goes off all the rest of the files just gets replicated to the new branch
- touch login.html creating a new file



