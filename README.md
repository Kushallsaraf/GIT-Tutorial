# GIT-Tutorial
Repository for learning and practising git


Use git clone to copy a repository from the web using the ssh key.

cd is change directory

ls -la is used to ;ist everything in the directory including the hidden files and folders.

when index.html was added and git status command was run it showed the file under "Untracked Files:" section. We need to use git add command (specifically git add .) to fix this. 

to commit we use the command git commit m"type message here". A message is required. 

git commit -m"" -m "". (The second -m is the description part which is optional)

but after executing this commit command we have only saved the changes locally. Next step is to make the changes live. 


git push is used for making the changes live. 


if git push origin master gives and error use this instead:
    git pull --rebase origin main
    git push origin main