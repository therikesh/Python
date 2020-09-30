# -------------STEPS TO CREATE A REPO-----------------

In this document we took a deep look at git clone. The most important takeaways are:

1. git clone is used to create a copy of a target repo

2. The target repo can be local or remote

3. Git supports a few network protocols to connect to remote repos

4. There are many different configuration options available that change the content of the clone



# Python
# ------------------STEPS TO HOW TO CLONE ------------------

git clone https://github.com/Yonv1943/Python

git config --global user.email "178320049@qq.com"

git config --global user.name "Yonv"



git init

git add README.md

git commit -m "first commit"



git remote add origin git@github.com:Yonv1943/Python.git

git push -u origin master


