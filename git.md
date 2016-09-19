# Git


## Intialize a project

Initialize on github

	git clone https://github.com/lowderchris/blah.git

Initialize locally

	git init
	git add files
	git commit -m “Initial commit”
	git remote add origin https://github.com/lowderchris/blah.git
	git push origin master

## Synchronize remote / local

Pushing changes

	git add files
	git commit -m “Commit message”
	git push origin master

Pulling changes

	git fetch
	git merge

Force pulling changes

	git pull

Pull changes, applying local changes atop remote

	git pull --rebase
