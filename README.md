"# Restaurant-ch73" 

# Git
Everytime we start working on a new project, we have to create a repository on Github.
We will use Git to have a control on out project and connect our local project to an 
online Github repository. (Like an online copy of our project, it mirrors the ceontent)

We have two workflows on consiseration: 
1. Starting from scratch
When we create an empty repo, on out local project we have to open a termonal and run the 
following: 
    - git init
    - git add -A or git add .
    - git commit -m "ADD A MESSAGE"
    - git branch -M main
    - git remote add origin https://github.com/YOUR_GITHUB_USER/YOUR_REPO_NAME.git
    - git push -u origin main
Plwase execute these commands one by one, and make sure there's at least one file in your project

2. Once it's connected. continue working with git
    - git add -A
    - git commit -m 'ADD A MESSAGE" 
    - git push -u origin main
Please execute these commands one by one, and make sure there's at least one file in your project