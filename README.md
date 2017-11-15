# gitworkflow

I created gitworkflow repo from the LocalList Organization. 
Then I forked the gitworkflow repo.
Then I cloned that repo to my local machine (pairing station). 
I added https://github.com/LocalList/gitworkflow as an upstream remote. This is what each of us is supposed to do after we have each forked the original. 

Before we make changes, we should be in sync with the master. git pull --rebase upstream master
Now leave your local master as an up-do-date copy of the organization's master. 
To make changes, create a specific branch for those changes.
Make your changes and commit frequently to this branch. 
Now since other people have likely made changes to master, we need to pull those down first and resolve conflicts before we push our changes. So do git pull --rebase upstream master AGAIN. 


Then I added these changes to this readme file. 
Then I saved the changes and committed them as Test1.  
Then I made some more changes and saved them. 
Then I committed the other changes as Test2. 
Then I switched to the 'dev' branch by typing git checkout -b dev
Then I made some more changes and saved them (lines 10-12).
Then I committed the changes as "Test3, dev branch."
Then I pushed the dev branch to master. 