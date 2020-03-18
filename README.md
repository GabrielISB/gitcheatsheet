# gitcheatsheet
cd /home/user/my_project            Initializating a repository in an existent directory

git init                            Initializate the git

git add *                           This is for upload things that are in a folder that is already in a repository


git commit -m ""                    This is like the respaldo

git clone https://github.com/libgit2/libgit2 mylibgit  this is to clone a repository and rename the document

git status                          This is to check how your files are doing 

echo "# " >> README.md              This is to create the txt file 

git add README.md                   This is to add the txt file to the repository


git remote add origin https://github.com/GabrielISB/gitcheatsheet.git   we are giving the file a direction to be upload

git push -u origin master           With this command we enter to our username and our password of git

git status -s or git status --short  To see a simplify version of the status of your files

cat .gitignore                       This is to ignore files and don't upload them to github. *.a *.o extension and ~

* . [ao]

* ~

git diff                             This is to see exactly what you have changed

git diff --staged                    This compares your changes to your last commit

git diff --cached                    To see what you have staged

git rm README.md                     To remove a file

git rm \*~                           This removes all the files wit ~

git mv file_from file_to             To rename a file

git log                              To see what has happend to your file

git log -p                           To see the differences between the commits

git log --stat                       To see abreviation of the commits

git log --pretty                      Changes the output

git commit --amend                    To redo a commit

git reset                            To unstage

git checkout                         To see your files

git remote -v                        To see URL

git remote pb                         pb instead of the whole URL

git remote show origin               To see the origin

git remote rename pb                 To rename the remote

git remote rm                        To remove a remote

git tag -l                            Lists the tags 

git tag -a v1.4 -m "my version 1.4"    To create a tag

git tag v1.4-lw                      The commit checksum stored

git tag -a v1.2 9fceb02              If you forgot to tag

git tag -d nameofthetag               To delete a tag

git config --global                  To make changes in the configuration

git fetch                            download changes of the remote

git pull                            Used to download changes of the merce 

git branch testing                  This create a new pointer to the commit

git log --decorate                   To see easily the head poiting to a branch

git checkout testing                To see the new branch

git log --oneline --decorate --graph --all   It will print the history of your commits

git checkout -b iss53                To create a new branch and switch to it at the same time

git checkout master               Switched to branch master

git checkout -b hotfix              Hotfix branch 

git merge hotfix                        the hotfix branch back into your master branch to deploy to production

git branch -d hotfix                

git branch                           This creates and deletes branches

%h-- Abbreviated commit hash

%T--Tree hash

%t--Abbreviated tree hash

%P--Parent hashes

%p--Abbreviated parent hashes

%an--Author name

%ae--Author email

%ad--Author date (format respects the --date=option)

%ar--Author date, relative

%cn--Committer name

%ce--Committer email

%cd--Committer date

%cr--Committer date, relative

%s--Subject*/

/This command takes your preparation area and uses it for confirmation. If you haven't made any changes since your last commit
