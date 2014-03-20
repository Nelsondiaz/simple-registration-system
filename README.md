simple-registration-system
==========================

github.com is a pretty good git repository server for open source projects. If you have an account you can add easily a project to your github repo. At first generate the git project by executing this line in your project root:

git init
than add all files from your project to your local git repo:

git add .
Than commit everything to your local git repo:

git commit -m "init"
OK. Now you can connect your local git repo with your remote git repo by github.com

git remote add origin git@github.com:<username>/<projectname>.git
Just replace “username” with your github username and “projectname” with your projectname on github. Now you can push your changes to the github repo.

git push
