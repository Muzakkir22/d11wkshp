# Workshop 11 Instruction

### Maven commands
1.mvn
2.mvn compile
3.mvn package
4.mvn clean package
5.mvn clean
6.mvn clean package spring-boot:run
7.mvn spring-boot:run

### Git commands
git init

git remote add origin https://github.com/Muzakkir22/d11wkshp.git

git add *

git status

git commit -m "commit message details"

git push -u origin master

git pull

git branch -a

git branch -delete <branch name>

git checkout -b develop master

git add * (add to develop branch)

git commit -m "add readme file" (add to develop branch)

git push -u origin develop (push to remote git develop branch)

git checkout master

git merge develop (merge changes done in develop branch into master branch)

git push -u origin master

// make changes in master, and need to synchronise this change to develop branch
// assume changes hass already been checked into master branch
git checkout develop

git merge master (merge change done in master branch into develop branch)

git push -u origin develop
