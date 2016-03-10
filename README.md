# phase-0-gps-1
* git clone <URL>
	* clones repository from the URL (remote) to your local
	* git clone <URL> .
		* Doesn't create a separate folder within a folder for repo
		* clones files from the repo to the current directory
* git add awesome_page.md
	* staging the file for a commit
* git commit -m "message"
	* committing the file with a detailed message
* git status
	* shows if all files have been staged or modified within that repo
	* so if "nothing to commit" is displayed, all files are up to date
* git push origin master
	* Pushed changed files to master
* git checkout -b add-command-log
	* Created and switched to a new feature-branch