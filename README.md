# Practica2Softca
ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2
$ git clone https://github.com/guerraman/Practica2Softca.git
Cloning into 'Practica2Softca'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2
$ git status
fatal: not a git repository (or any of the parent directories): .git

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2
$ cd Practica2Softca

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git add .

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git commit -m "commit inicial"
[main 5f8b21c] commit inicial
 1 file changed, 2 insertions(+), 1 deletion(-)

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 314 bytes | 314.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/guerraman/Practica2Softca.git
   517bffa..5f8b21c  main -> main

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

nothing added to commit but untracked files present (use "git add" to track)

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git add .

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore


ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git commit -m " añadido fichero .gitignore"
[main 8a395f2]  añadido fichero .gitignore
 1 file changed, 2 insertions(+)
 create mode 100644 .gitignore

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        1.txt

nothing added to commit but untracked files present (use "git add" to track)

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git add .

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   1.txt


ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git commit -m "añadido fichero 1.txt"
[main 8573edf] añadido fichero 1.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 1.txt

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git tag v0.1

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git push --tag origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 613 bytes | 306.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/guerraman/Practica2Softca.git
   5f8b21c..8573edf  main -> main
 * [new tag]         v0.1 -> v0.1

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git branch v0.2

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git checkout v0.2
Switched to branch 'v0.2'

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (v0.2)
$ touch 2.txt

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (v0.2)
$ git status
On branch v0.2
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        2.txt

nothing added to commit but untracked files present (use "git add" to track)

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (v0.2)
$ git add .

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (v0.2)
$ git status
On branch v0.2
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   2.txt


ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (v0.2)
$ git commit -m " se agrego 2.txt"
[v0.2 054e235]  se agrego 2.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 2.txt

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (v0.2)
$ git push origin v0.2
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 237 bytes | 237.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'v0.2' on GitHub by visiting:
remote:      https://github.com/guerraman/Practica2Softca/pull/new/v0.2
remote:
To https://github.com/guerraman/Practica2Softca.git
 * [new branch]      v0.2 -> v0.2

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (v0.2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git merge v0.2 -m "merge de v0.2"
Updating 8573edf..054e235
Fast-forward (no commit created; -m option ignored)
 2.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 2.txt

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git add .

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   1.txt


ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git commit -m " hola en 1.txt"
[main 20a38c4]  hola en 1.txt
 1 file changed, 1 insertion(+)

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git checkout v0.2
Switched to branch 'v0.2'

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (v0.2)
$ git status
On branch v0.2
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   1.txt

no changes added to commit (use "git add" and/or "git commit -a")

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (v0.2)
$ git add .

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (v0.2)
$ git commit -m "adios en 1.txt "
[v0.2 49f9061] adios en 1.txt
 1 file changed, 1 insertion(+)

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (v0.2)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git merge v0.2
Auto-merging 1.txt
CONFLICT (content): Merge conflict in 1.txt
Automatic merge failed; fix conflicts and then commit the result.

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main|MERGING)
$ git add .

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main|MERGING)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

All conflicts fixed but you are still merging.
  (use "git commit" to conclude merge)

Changes to be committed:
        modified:   1.txt


ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main|MERGING)
$ git commit -m "arreglado el conflicto en 1.txt"
[main 1da783f] arreglado el conflicto en 1.txt

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git branch --merged
* main
  v0.2

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git branch --no-merged

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git tag v0.2

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git branch -d v0.2
Deleted branch v0.2 (was 49f9061).

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git config --global alias.list 'log --oneline --decorate --graph --all'

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$ git list
*   1da783f (HEAD -> main, tag: v0.2) arreglado el conflicto en 1.txt
|\
| * 49f9061 adios en 1.txt
* | 20a38c4  hola en 1.txt
|/
* 054e235 (origin/v0.2)  se agrego 2.txt
* 8573edf (tag: v0.1, origin/main, origin/HEAD) añadido fichero 1.txt
* 8a395f2  añadido fichero .gitignore
* 5f8b21c commit inicial
* 517bffa Initial commit

ingen@DESKTOP-SKSCDO7 MINGW64 ~/practica2/Practica2Softca (main)
$


