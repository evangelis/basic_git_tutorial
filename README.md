This is the README. 
A simple git workflow 

#1(a). Create a git repo on github :https://github.com/evangelis/basic_git_tutorial
#1(b) Clone it or manually add the remote repo as follows
git clone https://github.com/evangelis/basic_git_tutorial 
git remote -v
sudo rm -rf basic_git_tutorial
mkdir basic_git_tutorial_manual && cd basic*
git init
git remote add origin https://github.com/evangelis/basic_git_tutorial
mkdir source-code && 
touch README.md source-code/index.html
#2.Work on index.html & README files 
git add README.md source-code/index.html
git status # Changes to be commited (git rm --cached <file> to unstage)
git commit -m "Add files"
#Push committed changes upstream
git push origin master

