git clone https://github.com/fatimazahraa00/devops1.git

cd github

git branch -m master

![1](https://github.com/user-attachments/assets/595981f2-bdd8-4c03-9eae-c26c9603ffb9)

mkdir Task1

touch Task1/README.md

git add .

git commit -m "adding Task1 folder and the README file on the master branch"

git push origin master

![2](https://github.com/user-attachments/assets/ee3206db-8e66-4886-a119-73bb92cac640)

git checkout -b dev

touch test

git add .

git commit -m "adding test file to the dev branch"

git push --set-upstream origin HEAD
