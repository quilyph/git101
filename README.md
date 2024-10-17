# git

## general

* ~ - home directory. on Windows it's C:/%USERS%/%USER%

* .. - higher folder

* . - current folder

* pwd - **p**rint **w**riting **d**irectory

* cd (directory)- **c**hange **d**irectory

* ls (-a) (-la) - **l**i**s**t contents

* mkdir (name) (-p) - **m**a**k**e a **dir**ectory

* touch (name) - create a file

* cp (name) (name2) ... (directory) - copy files to a directory

* mv (name) (name2) ... (directory) - move files to a directory

* cat (name) - read file contents

* rm (name) (-r) (-rf)- **r**e**m**ove file

* rmdir (name) - **r**e**m**ove directroy

* *careful! files or directories removed by git commands cannot be restored!*

* clip < (name) - copy contents to **clip**doard

* Tab - press to autocomplete or show options

## git commands

* git init - **init**ialise a git repository (creates a .git file)

* rm -r ./git - undo

* git status - added and not added files

* git add (name) (--all) - add files

* git commit -m "(commit message here)" - commit change

* git remote add (project_name) (SSH) 

* git push -u (project_name) master - connect current project and github repository the first time

* git push - the same afterwards

## initialise connection (cmd)

* ssh-keygen -t ed25519 -C (github email) - create SSH key

_usually keys are stored at ~/.ssh_

_example: _

* id_ed25519.pub - public key

* id_ed25519 - private key

_public keys always end with ".pub". don't share your private keys with anyone._