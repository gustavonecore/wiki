Git tips
========
Overview
These steps summarize what will be done from the cloning of remote part to your team as well as the realization of changes in both remote and local.

 1. Git clone
	`git clone https://github.com/gustavonecore/wiki.wiki.git`
 2. Create a new branch from the master branch. Replace master with your custom requirements (e.g: develop, feature/1, etc)
 	`git checkout -b feature/1 master`
 3. Update your code at this point...	
 4. Review your local changed files
	`git status`
 5. Add files to the commit with:
 	`git add file1 file2 file4` or you can add all with `git add .`
 6. Create the respective commit with your changed files an a message. Take a look to the {ISSUE_NUMBER}, should be replaced with the number of the N° of the ticket:
	`git commit -m "#{ISSUE_NUMBER} :: commit wiki"` , e.g: git commit -m "#10 :: My message here"
 7. Syncronize your local branch with the tarjet branch (optional)
 	`git pull origin {tarjet_branch}`
 8. Push your local changes to the remote repository/branch
	`git push origin feature/1`
 9. View the history of commits in your local branch
 	`git log`
 10. If your ticket it's done, go to github and create your Pull Request!
 
 *Tips: If your branch was created from master the PR should go to master. The same rule for any child branch who wants to get merged.*
