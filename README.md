# Hello-World
This repo is for practicing github flow - Happy practice

It is interesting 

BRANCHING
1. First main creared as a default branch and then
2. I created a readme-edits branch.Now,I am doing changes in readme ...- and
3. This change is only applied to this readme branch alone and not affects the main branch
   
COMMIT
Then click on commit(to save changes)

PULL
After commiting the change - open pull request (heart of collaboration)

COMPARE 
you can compare the branches before pulling 

then review the pull request

MERGE
merging the edits made in the readme-edits to the main branch - the chnages made in the readme-edits will reflect in the main branch

Can alos create a new branch to so the chnages 

can also delete the readme-edits  

***If you want to make a new changes - repeat the same process

**********************************************************************************************************

**This is a new change by following the same process**

Create a repository.
Start and manage a new branch.
Change a file and commit those changes to GitHub.
Open and merge a pull request.
------------------------------------------------------------------------------------------------------------
**Ignore commits in the blame view**
All revisions specified in the .git-blame-ignore-revs file, which must be in the root directory of your repository, are hidden from the blame view using Git's git blame --ignore-revs-file configuration setting. For more information, see git blame --ignore-revs-file in the Git documentation.

In the root directory of your repository, create a file named .git-blame-ignore-revs.

Add the commit hashes you want to exclude from the blame view to that file. We recommend the file to be structured as follows, including comments:

# .git-blame-ignore-revs
# Removed semi-colons from the entire codebase
a8940f7fbddf7fad9d7d50014d4e8d46baf30592
# Converted all JavaScript to TypeScript
69d029cec8337c616552756310748c4a507bd75a
Commit and push the changes.

Now when you visit the blame view, the listed revisions will not be included in the blame. You'll see an Ignoring revisions in .git-blame-ignore-revs banner indicating that some commits may be hidden:





