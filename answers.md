Answer 1: version 2.17.1
Answer 2: user.name=Chase Wilson
	  user.email=cw034119@ohio.edu
Answer 3: after issuing the command, the terminal pulls up a new screen that details all pertinent information about the command and its uses.
Answer 4: Generated output is: No commits yet 

nothing to commit (create/copy files and use "git add" to track)
Answer 5:
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	         answers.md
Answer 6:
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md
	new file:   answers.md

Answer 7: 
On branch master
nothing to commit, working tree clean

Answer 8:
[master (root-commit) b08723e] Initial commit
 2 files changed, 11 insertions(+)
 create mode 100644 README.md
 create mode 100644 answers.md
cwilson@odd17:~/2400/git-Lab$ git status
On branch master
nothing to commit, working tree clean
cwilson@odd17:~/2400/git-Lab$ git log
commit b08723e8590f5235f0edcc95433cb8e2315164ae (HEAD -> master)
Author: Chase Wilson <cw034119@ohio.edu>
Date:   Thu Sep 2 15:35:47 2021 -0400

    Initial commit
Answer 9:
Counting objects: 4, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 513 bytes | 171.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/cw034119/git-lab.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
After git status command:
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Answer 10: No, the local copy did not update.
	
Answer 11: 
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

Answer 12:
warning: no common commits
remote: Enumerating objects: 13, done.
remote: Counting objects: 100% (13/13), done.
remote: Compressing objects: 100% (11/11), done.
remote: Total 13 (delta 1), reused 3 (delta 0), pack-reused 0
Unpacking objects: 100% (13/13), done.
From https://github.com/cw034119/git-lab
 * [new branch]      main       -> origin/main
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main
Answer 13:
.  ..  git-Lab	git-lab-2  Labs
