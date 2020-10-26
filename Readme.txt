this is just test

this is a second commit 

git log

git status
----------------------------------
git remote -v

git branch -r ==> lists the connection between the local and remote branch 

---------------------------------------

jumping back to the different head

git checkout  [commit hash here ] 

note we can't start editing from here and committing because its no longer a part of the the branch


cmd to jump back 'git master'

or git checkout master

--------------------------------------------------

reverting the last changes

git reset --hard [commit id]


------------------------------------------------------
commands  to revert the  staged changes 

like reverting  all the  changes wihich are uncommited

git checkout -- .


---------------------------------------------------------

creating a new branch 'git checkout -b branch_name'

edit something in htat branch and commit the changes

--------- marging the branch with the master 

  switch to the master and  and issue the cmd 'git merge [branch name]'

now to delete the bhanch 'git branch -D [branch name]'


some usefull cmd >  git merge --abort


after the merge commit it and then push it to the remote



--------------------------------------------------
  GIT PULL AND FETCH

   git pull get's the remote changes and merges automatically

git fetch will gets the remote chanes but will not merge we have to merge manually

  steps 1  : to check the remote changes  'git checkout origin/master'
====> switch back to the master branch

 step 2 : to merge 'git merge origin/master'

------------------------------------------------------

REMOVING THE REMOTE ORIGINE

git remote -rm origin























































