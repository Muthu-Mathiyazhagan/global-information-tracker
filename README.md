<h4><i>Rebase </i> </h4>

You can abort while doing merge only;
git merge --abort

When the REPO age grows we will have lot of Branches and Divergence,
To Reduce the Divergence and Maintain Linear History/Path we will use this.
We need to be very Consious while rebasing.

--------
If you are only person working on that BRANCH, you can do.
Can anyone tell me Why ?

---------
git rebase master
git rebase --continue
git rebase --skip
git rebase --abort
---------
git config --global mergetool.keepBackup flase

