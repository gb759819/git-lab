1. git version 2.24.3 (Apple Git-128)

2. credential.helper=osxkeychain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
user.name=Garrett Barringer
user.email=gb759819@ohio.edu

3. When you type "git --help", the first thing that pops up is "These are common Git commands used in various situations:." It then goes on to inform you about all the commands the user can use and what they are for.

4. On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	README.md
	answers.md

nothing added to commit but untracked files present (use "git add" to track)

5. On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	answers.md

6. On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md
	new file:   answers.md

7. gbarringer@Garretts-MacBook-Pro git-lab % git commit -m"Initial commit" 

[master (root-commit) 82ee9dd] Initial commit
 2 files changed, 38 insertions(+)
 create mode 100644 README.md
 create mode 100644 answers.md

// Then once instructed to commit again I got this:
gbarringer@Garretts-MacBook-Pro git-lab % git commit -m"Issuing the status again as instructed"

On branch master
Changes not staged for commit:
	modified:   answers.md

no changes added to commit

8. commit 82ee9dd10bdcc6a5ee8e151a84a2949a0151acb2 (HEAD -> master)
Author: Garrett Barringer <gb759819@ohio.edu>
Date:   Wed May 19 14:24:29 2021 -0400

    Initial commit

9. On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")

10. No the changes were not reflected.

11. error: failed to push some refs to 'https://github.com/gb759819/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

12. Yes, my file was the same locally, and online.

13. .		..		.git		.gitignore	README.md
