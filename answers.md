# Answer 1
git version 2.17.1

# Answer 2
user.name=Gabrielle Miller
user.email=gm993814@ohio.edu

# Answer 3
When I typed git --help, I received common Git commands information and how they are used in various situations like add, mv, reset, etc.

What was shown:

usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.

# Answer 4
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	README.md
	answers.md


# Answer 5
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	answers.md

# Answer 6 
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md
	new file:   answers.md

# Answer 7
On branch master
nothing to commit, working tree clean

# Answer 8 
commit 9c67c9767312619d9c5b7e5156cd41601e8657b7 (HEAD -> master)
Author: Gabrielle Miller <gm993814@ohio.edu>
Date:   Fri Sep 6 16:30:17 2019 -0400

    Initial commit

# Answer 9
On branch master
Your branch is up to date with 'orgin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   answers.md

# Answer 10
No, the file did not update with my changes I made on github. 

commit ec0af2520f2443ba88a4ee55dc3d31a246c35860 (HEAD -> master, orgin/master)
Author: Gabrielle Miller <gm993814@ohio.edu>
Date:   Fri Sep 6 16:40:11 2019 -0400

    Added my email and location on where answers for lab 2 are

commit 9c67c9767312619d9c5b7e5156cd41601e8657b7
Author: Gabrielle Miller <gm993814@ohio.edu>
Date:   Fri Sep 6 16:30:17 2019 -0400

# Answer 11
This command was rejected because this git push command is sending infomation to GIThub and changes have been made to the file already located there,

warning: redirecting to https://github.com/gabbym2015/git-lab.git/
To http://github.com/gabbym2015/git-lab.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'http://github.com/gabbym2015/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

# Answer 12
Yes, the class section I added is shown in the README.md file. 

From the README.md file
Gabrielle Miller
gabbym2015
gm993814@ohio.edu
Answers located in answers.md file
cs 2400, section 113


From the terminal:
warning: redirecting to https://github.com/gabbym2015/git-lab.git/
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From http://github.com/gabbym2015/git-lab
   ec0af25..854b7bc  master     -> orgin/master
Updating ec0af25..854b7bc
Fast-forward
 README.md | 1 +
 1 file changed, 1 insertion(+)

# Answer 13
.  ..  .git  .gitignore  README.md
