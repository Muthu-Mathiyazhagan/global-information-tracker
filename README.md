<h3><i>Undoing a Faulty merge </i> </h3>
You can abort while doing merge only;
git merge abort

Say you made mistake with merge,
But you realise after that only you are having two ways to solve that,
One way is reset the mergeCommit like it no where it was EXIST (Remember we can again restore that also with hash)

Reset :
git reset --soft HEAD^ # Removes the last commit, keeps changed staged
git reset --mixed HEAD^ # Unstages the changes as well
git reset --hard HEAD^ # Discards local changes

* Remember you are re-writing History in Reseting.
its fine if only you are working in that REPO

Revert:

git revert 72856ea # Reverts the given commit
git revert HEAD~3.. # Reverts the last three commits

git restore --source=HEAD~2 file.js # Restoring an earlier version of a file
