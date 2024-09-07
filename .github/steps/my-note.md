# RESOLVING A CONFLICT FROM THE TERMINAL - https://www.youtube.com/watch?v=FDXSgyDGmho
Looks like most time the changes can be made in the branches not main
==>git switch main
==>git pull origin main --(to pull the changes made remotely)
==>git switch add-new-name
==>git merge main  --(On your editor on VSCODE you will get a message "Resolve in Merge Editor". You will see some conflicts markers. Remove the conflicts then Click on Complete Merge 
Auto-merging index.html
CONFLICT (content): Merge conflict in index.html
Automatic merge failed; fix conflicts and then commit the result.
==>git add .
==>git commit -m "resolve merge conflict"
==>git status 
On branch add-new-name
nothing to commit, working tree clean
==>git push origin add-new-name
Then you go to the Github Pull Request Tab and Click on Pull Merge Request=>Confirm Merge

