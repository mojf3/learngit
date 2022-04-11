# Git
Git is a distributed version control system.

Git is free software.

Git has a mutable index called stage.

Git tracks changes of files.


# configure
git config --global user.name "mojf3"

git config --global user.email "mojf3@mail2.sysu.edn.cn"

# create remote repositories (in github)

## in local
ssh-keygen -t rsa -C "mojf3@mail2.sysu.edn.cn"  

cd .ssh

cat id_rsa.pub

## copy it in "SSH Keys" of setting of github

## git clone new repositories


# git common code 
git status

git add 

git commit -m "xx"

git push

## version control
git log

git reflog

git reset --hard commit_id

eg: git reset --hard HEAD^

git checkout -- file

git reset HEAD file


## https://www.liaoxuefeng.com/wiki/896043488029600 help for using git
