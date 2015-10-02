# git-commands

sudo git —version
which git


##configuration
git config —system

sh-3.2# git config --global user.name "Goran”  
sh-3.2# git config --global user.email "goran.rad@website.com“  
sh-3.2# git config --list

cd ~    - go to user directory  
ls -la  - list with details  
cat .gitconfig - editing mode

git config --global core.editor "nano -wl1“ -configure text editor  
git config --global color.ui true - use colors  
curl -OL https://github.com/git/git/raw/master/contrib/completion/git-completion.bash  
sh-3.2# mv ~/git-completion.bash ~/.git-completion.bash  
nano .bash_profile

##docs  
git help  
git help push  
man git-push

##writing commit messages  
git commit -m “message” 

##showing previosly logged messages  
git log  
git log -n 4  - limit to 4 recent logs  
git log —-since=2014-06-15  
git log —-author=gora  
git log —grep=“Init”  

##commings - staging  
git add file.txt  
git rm file2.txt - removing  
git mv file1.txt file2.txt - renaming  
git mv file1.txt dir/file2.txt - renaming and moving  
git update-index --assume-unchanged file.txt - ignore it  

git status - gets current status of head, pending changes  

##changes 
git diff file.txt -one line above another  
git diff --color-words file.tx - side to side diff  
git diff --staged  
git diff --cached  
git commit -am "message"  


