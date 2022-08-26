* Stashing - Storing Something in Secret Place (Hiding)
* Its Save the Changes as Array.
* Only Tracking Files are added to Stash by Default

<h4>Commands:<h4>
git stash   #Stash All Changes 
git stash push -m "custom stash Message"
git stash list
git stash show 0
git stash show 0 --patch
git stash apply 0
git stash drop 0 
or
git stash pop 0
git stash clear
git stash push -am "custom stash message" # It will add the unsaved local change Untracking file also

