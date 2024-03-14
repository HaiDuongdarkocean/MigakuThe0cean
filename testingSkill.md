gh auth login
gh repo create [name] --public

git config --global user.email "[name]"
git config --global user.name "[name]"

git init
echo "# testskill" >> README.md
git add README.md
git branch -M main
git commit -m  "First commit"
git remote add origin https://github.com/[name repo]
git push -u origin main

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

gh auth login
gh repo create [name] --public

git init
echo "# test" >> README.md
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github/[link repo]
git push -u origin main

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

gh auth login
gh repo create [name] --public

git init
echo "# testingskill" >> README.md
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/[link repo]
git push -u origin main

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

gh auth login
gh repo create <name> --public

git init
echo "# testingskill" >> README.md
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/...
git push -u origin main
