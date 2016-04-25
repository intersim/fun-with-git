# Best git workflow for doing workshops:
* fork repository: makes your own remote copy of the repository
* `git clone` to make a local repository
* add your teammate as a collaborator, and they can clone as well
* work on one computer, doing `git add` and `git commit` when you reach a nice checkpoint (don't have to push after every commit)
* when you're ready to switch computers, `git push origin master`
* from your partner's computer: `git pull` (or `git fetch` then `git merge`)
* keep working on your partners computer, doing `git add` and `git commit` as you make progress
