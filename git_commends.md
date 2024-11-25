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


![3](https://github.com/user-attachments/assets/c6b042b3-10b5-4852-9921-6585c63f9cc3)

git checkout -b %USERNAME-new_feature

![4](https://github.com/user-attachments/assets/b88a43d0-6726-43d1-8ef2-f31c9744f421)

touch README.md

