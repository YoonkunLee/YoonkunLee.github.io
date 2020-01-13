---
title: "How to use Git Ignore"
date: 2020-01-13 
categories: Programming study 
---

Why we using Git Ignore?

-The purpost of the .gitignore is to ignore specific files which are backup files, build products or ID, password 
that we never want to commit into a repository. 

How we can create .gitignore file using Git Bash? 

1. Go to git repository of the project 
2. Write "touch gitignore" to create a .gitignore file 
3. Go to current github repository and open .gitignore file 
4. Write specific file name that you want to ignore when upload/push 
Example)
![gitignore](https://user-images.githubusercontent.com/53284444/72234901-28dd1c00-3634-11ea-929e-0068dfd138b5.png)

How to commit Git ignore 

1. Write "git rm -r --cached ."
2. Write "add ."
3. Write "commit -m "Apply .gitignore"

How to push to repository

1. Write "git push origin master" (may different when push to other branch)
