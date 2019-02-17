# githubdetails
Command line instructions

Git global setup
git config --global user.name "Chaitanya"
git config --global user.email "csenapati12@gmail.com"

Create a new repository
git clone git@chaitanya-Inspiron-5521:csenapati12/gittag.git
cd gittag
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master

Existing folder
cd existing_folder
git init
git remote add origin git@chaitanya-Inspiron-5521:csenapati12/gittag.git
git add .
git commit -m "Initial commit"
git push -u origin master

Existing Git repository
cd existing_repo
git remote rename origin old-origin
git remote add origin git@chaitanya-Inspiron-5521:csenapati12/gittag.git
git push -u origin --all
git push -u origin --tags





one time authentication
==========================
set the remote url \n
git remote set-url origin git@github.com:username/repo.git \n
git remote set-url origin git@http://chaitanya-inspiron-5521:csenapati12/gittag.git
