<h4><i>Cherry-pick </i> </h4>

These all Merging Rebasing Process are long process,
You should not do any other work till the process complete or abort

----------
We can pick only particular COMMIT to our master branch from another Branch.
Say,
You are working on a branch and that branch not ready to merge but you need a particular COMMIT,
Yes you can use
git cherry-pick ececbe109

----------
you can pick only a file from a commit instead of Full commit

git restore --source=commitID --file.txt
commitID = 37abgd67
commitID = HEAD~5


----
This Chapter acutally ending today not yesterday :)