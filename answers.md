Answer One:
git version 2.17.1

--------------------------------------------------------------

Answer Two:
user.name=BrysonFPalmer
user.email=bp509821@ohio.edu

--------------------------------------------------------------

Answer Three:
GIT-ADD(1)                        Git Manual                        GIT-ADD(1)

NAME
       git-add - Add file contents to the index

SYNOPSIS
       git add [--verbose | -v] [--dry-run | -n] [--force | -f] [--interactive |
 -i] [--patch | -p]
                 [--edit | -e] [--[no-]all | --[no-]ignore-removal | [--update |
 -u]]
                 [--intent-to-add | -N] [--refresh] [--ignore-errors] [--ignore-
missing] [--renormalize]
                 [--chmod=(+|-)x] [--] [<pathspec>...]

DESCRIPTION
       This command updates the index using the current content found in the
       working tree, to prepare the content staged for the next commit. It
       typically adds the current content of existing paths as a whole, but
       with some options it can also be used to add content with only part of
       the changes made to the working tree files applied, or remove paths
       that do not exist in the working tree anymore.

       The "index" holds a snapshot of the content of the working tree, and it
 Manual page git-add(1) line 1 (press h for help or q to quit)

--------------------------------------------------------------

Answer Four:
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	README.md
	answers.md

nothing added to commit but untracked files present (use "git add" to track)

--------------------------------------------------------------

Answer Five:
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	answers.md

--------------------------------------------------------------

Answer Six:
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md
	new file:   answers.md

--------------------------------------------------------------

Answer Seven:
On branch master
nothing to commit, working tree clean

--------------------------------------------------------------

Answer Eight:
commit 61bc9623a14b147aa09220ada8460a032bf820e3 (HEAD -> master)
Author: BrysonFPalmer <bp509821@ohio.edu>
Date:   Tue Aug 31 16:19:17 2021 -0400

    Initial commit

--------------------------------------------------------------

Answer Nine:
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

--------------------------------------------------------------

Answer Ten:
No, the changes I made online were not reflected in my local copy

--------------------------------------------------------------

Answer Eleven:
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 452 bytes | 226.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/BrysonFPalmer/git-lab.git
   61bc962..678d09f  main -> main
bpalmer@odd31:~/2400/git-lab$ ls
answers.md  README.md
bpalmer@odd31:~/2400/git-lab$ ls README.md
README.md
bpalmer@odd31:~/2400/git-lab$ open README.md
Couldn't get a file descriptor referring to the console
bpalmer@odd31:~/2400/git-lab$ git push
Username for 'https://github.com': BrysonFPalmer
Password for 'https://BrysonFPalmer@github.com': 
To https://github.com/BrysonFPalmer/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/BrysonFPalmer/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

--------------------------------------------------------------

Answer Twelve: 
Yes, the changes I made online reflected in my local copy.

--------------------------------------------------------------

Answer Thirteen:
.  ..  .git  .gitignore  README.md

--------------------------------------------------------------