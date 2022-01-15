git config --global user.name "your-username"
git config --global user.email "your-email"
git config --global user.password "your-password"


echo "# discuss-git-repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/any-user/any-name.git
git push -u origin master

…or push an existing repository from the command line
git remote add origin https://github.com/any-user/any-name.git
git branch -M master
git push -u origin master
