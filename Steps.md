Git tips
========
Overview
These steps summarize what will be done from the cloning of remote part to your team as well as the realization of changes in both remote and local.

 1. Git clone
	`git clone https://github.com/gustavonecore/wiki.wiki.git`
 2. Creation new branch
 `git checkout -b feature/1 master`
 3. Change your code here...	
 4. Status archives 
    Lookup modified/added files from your local work
	`git status`
 5. Add archives 
 Add files to the commit `git add file1 file2 file4` or you can `add all git add .`
`git add file 1` `git add .`
 6.  Save changes
`git commit -m "#{ISSUE_NUMBER} :: commit wiki"`
 7. Syncronize local branch
 `git pull origin master`
 8. Upload changes
`git push origin feature/1`
 9. View change history
 `git log`
 10. Go to github and create your PR!
