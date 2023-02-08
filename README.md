# git-learn-repo
repository created for  hands on Git Commands

# Git commands
1. Clone : Bring repo from github to local machine 

        git clone https://github.com/gsraditya2105/git-learn-repo.git
        
2. add : add files to track the changes 

        git add demo.py
        
3. commit : move to staging with a message 

        git commit -m "demo python file" demo.py


so far all these changes will be part of the local machine 
To push on them onto github 

This option is only when we have completely new folder on local machine

4. Add origin

    git remote add origin https://github.com/gsraditya2105/git-learn-repo.git

5. push : upload git commits from local machine to git repo

    git push -u origin main
    
6. status : status of the git folder - lists untracked, modified files 

    git status
    
7. log : shows the history of commits 

    git log <filename:if commit specifice to a file is needed>

8. checkout : to revert the changes done in local machine means file reverts to the original copy on github repo 

    git checkout -- filename
    
9. pull : to pull the latest changes from github to local machine 

    git pull 
