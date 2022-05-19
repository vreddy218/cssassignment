# cssassignment
vredd218@LIN33003674 MINGW64 ~ (master)
$ mkdir css-assignments

vredd218@LIN33003674 MINGW64 ~ (master)
$ cd css-assignments

vredd218@LIN33003674 MINGW64 ~/css-assignments (master)
$ git Readme.txt
git: 'Readme.txt' is not a git command. See 'git --help'.

vredd218@LIN33003674 MINGW64 ~/css-assignments (master)
$ git add Readme.txt

vredd218@LIN33003674 MINGW64 ~/css-assignments (master)
$ git init
Initialized empty Git repository in C:/Users/VREDD218/css-assignments/.git/

vredd218@LIN33003674 MINGW64 ~/css-assignments (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Readme.txt

nothing added to commit but untracked files present (use "git add" to track)

vredd218@LIN33003674 MINGW64 ~/css-assignments (master)
$ git add Readme.txt

vredd218@LIN33003674 MINGW64 ~/css-assignments (master)
$ git commit -m 'Readme.txt file comited'
[master (root-commit) 4389889] Readme.txt file comited
 Committer: Reddy Muppana <venkata-sataya-sai-ram.reddy@capgemini.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Readme.txt

vredd218@LIN33003674 MINGW64 ~/css-assignments (master)
$ git status
On branch master
nothing to commit, working tree clean

vredd218@LIN33003674 MINGW64 ~/css-assignments (master)
$ touch css assignments

vredd218@LIN33003674 MINGW64 ~/css-assignments (master)
$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> master


vredd218@LIN33003674 MINGW64 ~/css-assignments (master)
$ git branch css-assignments

vredd218@LIN33003674 MINGW64 ~/css-assignments (master)
$ git switch css-assignments
Switched to branch 'css-assignments'

vredd218@LIN33003674 MINGW64 ~/css-assignments (css-assignments)
$ git checkout master Readme.txt
Updated 0 paths from 4825bf4

vredd218@LIN33003674 MINGW64 ~/css-assignments (css-assignments)
$ git status
On branch css-assignments
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        assignments
        css

nothing added to commit but untracked files present (use "git add" to track)

vredd218@LIN33003674 MINGW64 ~/css-assignments (css-assignments)
$ touch file.txt

vredd218@LIN33003674 MINGW64 ~/css-assignments (css-assignments)
$ git add -A

vredd218@LIN33003674 MINGW64 ~/css-assignments (css-assignments)
$ git status
On branch css-assignments
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   assignments
        new file:   css
        new file:   file.txt


vredd218@LIN33003674 MINGW64 ~/css-assignments (css-assignments)
$ git switch master
Switched to branch 'master'
A       assignments
A       css
A       file.txt

vredd218@LIN33003674 MINGW64 ~/css-assignments (master)
$ touch file.css

vredd218@LIN33003674 MINGW64 ~/css-assignments (master)
$ git add -A

vredd218@LIN33003674 MINGW64 ~/css-assignments (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   assignments
        new file:   css
        new file:   file.css
        new file:   file.txt


vredd218@LIN33003674 MINGW64 ~/css-assignments (master)
$ git switch master
Already on 'master'
A       assignments
A       css
A       file.css
A       file.txt

vredd218@LIN33003674 MINGW64 ~/css-assignments (master)
$ git merge css-assignments
Already up to date.

vredd218@LIN33003674 MINGW64 ~/css-assignments (master)
$ git branch -d css-assignments
Deleted branch css-assignments (was 4389889).

vredd218@LIN33003674 MINGW64 ~/css-assignments (master)
$
