## Friend is editing the Git

- Happens to be the same line.

-git init -> Initialize the project with local git
-git status -> Track the changes made
-git add . or git add <filename> -> Pushes the changes into local repo
-git commit -m <yourStringOfMessage>
-git log -> See the versions of the repo *Important is the Hash given by git
-git checkout <hash> -> To switch where the HEAD is pointing at the local repo

-git branch -M main -> Switch branch from master to main
-git remote add <yourString> <remote repo URL> -> 
-yourString standard is = origin

-origin = to the URL

-Branching & Merging
-git branch <branchName>
-git checkout <branchName>
-git checkout -b <branchName> -> Creates a new branch then immediately checkout to that branch
-*Whenever we create a branch we are copying the HEAD of the branch that we are currently in.
-git branch <branchName> <branchReference>

-git commit message = imperative -> If applied to the codebase, this commit will ________
-What will happen if I merge the branch containing this commit.

-Adding this line to test merge and pull