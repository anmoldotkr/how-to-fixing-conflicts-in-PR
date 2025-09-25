# how-to-fixing-conflicts-in-PR

========================How to resolved Conflicts======================

step 1: git fetch origin
	
step 2: Checkout your branch
	checkout to fetaure-branch (where your latest changes)
 
step 3: Merge the target branch (staging) into your branch
	git merge origin/target_branch

	
step 4: Resolve conflicts manually check you want to accept current changes or incoming changes (option)

step 5: git status

Step 6: git add .

step 7: git commit -m "fixing conflicts"

step 8: git push origin <feature_branch>

step 9: check PR on (github or bitbucket)
