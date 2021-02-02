### Please note step by step your action with git at here
From the begining :
#1 : Clone repository on your machine
     Command line : Git clone URL
#2 : Check out working branch to dev on that.
     Command line : Git checkout [branch name]
#3 : Create a new branch from dev 
     Command line : Git checkout -b [new brand name]
#4 : Create any change in Readme.md file 
     command line :
     a. command line : vi [file docs name]
     b. press [i] for insert
     c. change file follow requirement
     d. press [esc] and [:wq]
#5 : Commit your change with a new message
     a. command line : git add .
     b. command line : git commit -m "message"
#6 : Push your branch on the remote repository
     command line : git push
#7 : Create Merge request from your branch to dev branch
     a. Open github
     b. in "Pull request" section, click "create new pull request"
     c. Sellect "compare" and "base" branch and add message for change. Click "create pull request"
     d. Review and click "Merge request"
     
Merge code from another branch to your branch

#1 : Dev branch has some new change
    a. Switch branch : git checkout dev
    b. Add code "landscape page" to folder "scr"
    
#2 : Pull code change and merge to your branch
    a. Pull change code to dev local : git pull
    b. Commit code : git add .
                     git commit -m "message"
                     git push
    c. Go into "Pull request" , click "new pull request"
    d. sellect : base : working
                 compare : dev
       insert : pull request message
       click "create pull request"
    e. Review and click "Merge pull request"
