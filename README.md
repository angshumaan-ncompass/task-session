Latest Task

Scene 1: Simulate the following (Realized before committing)
1. Remote has 3 branches: main,branch1,branch2.
2. Pull from the remote.
3. Checkout to branch2 and work something inside branch2. Do not commit those
changes.
4. Half way through the task you realize you were working on the wrong branch, you
were supposed to be working in branch1.
5. Find a way to carry these changes to branch1, while branch2 is left unchanged.



Scene 2: Simulate the following (Realized after committing)
1. Remote has 3 branches: main,branch1,branch2.
2. Pull from the remote.
3. Checkout to branch2 and work something inside branch2.
4. Commit those changes.
5. You realize you were working on the wrong branch, you were supposed to be
working in branch1.
6. Find a way to undo these changes made to branch2, and do the changes inside
branch1.



Scene 3:Simulate the following (Realized after pushing)
1. Remote has 3 branches: main,branch1,branch2.
2. Pull from the remote.
3. Checkout to branch2 and work something inside branch2.
4. Commit those changes.
5. Push those changes.
6. You realize you were working on the wrong branch, you were supposed to be
working in branch1.
7. Find a way to undo these changes made to branch2, and do the changes inside
branch1. Both local and remote



-----------------------------------------------------------------------------








Task 1

- Clone this branch
- Create your own branch
- push your branch to remote

- create another branch in your name
- delete the second branch in remote and in local

NOTE : Do not merge your local branch with main branch

------------------------------------------------------------


Scenario 1:
1. Create a repository, add one text file.
2. Add one line into the text file, and commit
3. After first commit, add another line to the same file, then commit
4. After second commit, add one more line to the same file and commit.
5. Move back to first commit, view the file’s content
6. Come back to the latest commit.


Scenario 2:
1. Create repository, add one file.
2. Add 3 lines into the file and commit
3. Create another branch and switch to it
4. Edit that file’s 3rd line, and add 3 more lines to the file.
5. Merge two branches.
6. Finally the file should have 6 lines.


Scenario 3:
1. Create a repository and add few files.
2. Checkout to a new branch, edit those files.
3. Switch back to master branch and delete the newly created branch.
4. Try bringing back the deleted branch, along with the files


Scenario 4:
1. Create a repository
2. Add 3 files.
3. Commit
4. Delete 2nd file.
5. Commit.
6. Bring back the 2nd file


Scenario 5:
1. Create a repository
2. Add 3 files
3. Commit
4. Delete 2nd file
5. Bring back the 2nd file


Scenario 6:
1. Create a repository with 2 branches
2. Rename the master branch


Scenario 7:
1. Create a repository and add 2 files.
2. Commit
3. Edit the 2nd file
4. Don’t commit, checkout to new branch
5. Make some changes to the 2nd file in new branch
6. When switching back to the 1st branch, those uncommitted changes should be there