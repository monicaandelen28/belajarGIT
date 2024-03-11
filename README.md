# belajarGIT
Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT

user@Caca MINGW64 ~/Documents/Pemrograman Web (master)
$ git init
Initialized empty Git repository in C:/Users/user/Documents/Pemrograman Web/.git/

user@Caca MINGW64 ~/Documents/Pemrograman Web (master)
$ git clone
fatal: You must specify a repository to clone.

usage: git clone [<options>] [--] <repo> [<dir>]

    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --progress            force progress reporting
    --reject-shallow      don't clone shallow repository
    -n, --no-checkout     don't create a checkout
    --bare                create a bare repository
    --mirror              create a mirror repository (implies bare)
    -l, --local           to clone from a local repository
    --no-hardlinks        don't use local hardlinks, always copy
    -s, --shared          setup as shared repository
    --recurse-submodules[=<pathspec>]
                          initialize submodules in the clone
    --recursive ...       alias of --recurse-submodules
    -j, --jobs <n>        number of submodules cloned in parallel
    --template <template-directory>
                          directory from which templates will be used
    --reference <repo>    reference repository
    --reference-if-able <repo>
                          reference repository
    --dissociate          use --reference only while cloning
    -o, --origin <name>   use <name> instead of 'origin' to track upstream
    -b, --branch <branch>
                          checkout <branch> instead of the remote's HEAD
    -u, --upload-pack <path>
                          path to git-upload-pack on the remote
    --depth <depth>       create a shallow clone of that depth
    --shallow-since <time>
                          create a shallow clone since a specific time
    --shallow-exclude <revision>
                          deepen history of shallow clone, excluding rev
    --single-branch       clone only one branch, HEAD or --branch
    --no-tags             don't clone any tags, and make later fetches not to follow them
    --shallow-submodules  any cloned submodules will be shallow
    --separate-git-dir <gitdir>
                          separate git dir from working tree
    -c, --config <key=value>
                          set config inside the new repository
    --server-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only
    --filter <args>       object filtering
    --also-filter-submodules
                          apply partial clone filters to submodules
    --remote-submodules   any cloned submodules will use their remote-tracking branch
    --sparse              initialize sparse-checkout file to include only files at root
    --bundle-uri <uri>    a URI for downloading bundles before fetching from origin remote


user@Caca MINGW64 ~/Documents/Pemrograman Web (master)
$ git clone https://github.com/monicaandelen28/belajarGIT
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

user@Caca MINGW64 ~/Documents/Pemrograman Web (master)
$ cd belajarGIT

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-git

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-git.txt


user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-git)
$ git commit -m "Tugas-git"
[Tugas-git 95fb0fe] Tugas-git
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git merge T
merge: T - not something we can merge

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-git
Updating 014f319..95fb0fe
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
git push
$ git push
.
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 541 bytes | 270.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/monicaandelen28/belajarGIT
   014f319..95fb0fe  main -> main

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push [Ait push
error: src refspec push does not match any
error: failed to push some refs to '[Ait'

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ $ ggit pgit pushush
bash: $: command not found

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ .
bash: .: filename argument required
.: usage: . filename [arguments]

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git bash
git: 'bash' is not a git command. See 'git --help'.

The most similar command is
        stash

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Everything up-to-date

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git add Tugas-git.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git commit -m "Tugas-git"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-html

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-html.txt


user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-html)
$ git commit -m "Tugas-html"
[Tugas-html bebf6ab] Tugas-html
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-html)
$ get checkout main
bash: get: command not found

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-html)
$ ^C

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Everything up-to-date

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-html
Updating 7cd6e99..bebf6ab
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 318 bytes | 318.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/monicaandelen28/belajarGIT
   7cd6e99..bebf6ab  main -> main

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ get branch T
bash: get: command not found

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ get branch Tugas-css
bash: get: command not found

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-css

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-css.txt


user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-css)
$ git commit -m "Tugas-css"
[Tugas-css 0ec2d4b] Tugas-css
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-css
Updating bebf6ab..0ec2d4b
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 352 bytes | 352.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/monicaandelen28/belajarGIT
   bebf6ab..0ec2d4b  main -> main

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-js

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-js.txt


user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-js)
$ git commit -m  "Tugas-js"
[Tugas-js a5c66c9] Tugas-js
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-js)
$ git marge Tugas-js
git: 'marge' is not a git command. See 'git --help'.

The most similar command is
        merge

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-js)
$ git merge Tugas-js
Already up to date.

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-js
Updating 0ec2d4b..a5c66c9
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 281 bytes | 281.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/monicaandelen28/belajarGIT
   0ec2d4b..a5c66c9  main -> main

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-midProject

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-midProject.txt


user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-midProject)
$ git commit -m "Tugas-midProject"
[Tugas-midProject 6271a8d] Tugas-midProject
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-midProject)
$ git merge Tugas-midProject
Already up to date.

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-midProject
Updating a5c66c9..6271a8d
Fast-forward
 Tugas-midProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 290 bytes | 290.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/monicaandelen28/belajarGIT
   a5c66c9..6271a8d  main -> main

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-php

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-php)
$ git add Tugas-php.txt
fatal: pathspec 'Tugas-php.txt' did not match any files

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-php.txt


user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-php)
$ git commit -m "Tugas-php"
[Tugas-php a6f45c4] Tugas-php
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-php)
$ git merge Tugas-php
Already up to date.

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Everything up-to-date

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-php
Updating 6271a8d..a6f45c4
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 280 bytes | 280.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/monicaandelen28/belajarGIT
   6271a8d..a6f45c4  main -> main

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-finalProject

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-finalProject)
$ gti status
bash: gti: command not found

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-finalProject.txt


user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-finalProject)
$ git commit -m "Tugas-finalProject"
[Tugas-finalProject 354ad11] Tugas-finalProject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-finalProject)
$ git check main
git: 'check' is not a git command. See 'git --help'.

The most similar command is
        checkout

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-finalProject)
$ git checkot main
git: 'checkot' is not a git command. See 'git --help'.

The most similar command is
        checkout

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-finalProject
Updating a6f45c4..354ad11
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 290 bytes | 145.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/monicaandelen28/belajarGIT
   a6f45c4..354ad11  main -> main

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

user@Caca MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push origin --all
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/monicaandelen28/belajarGIT
 * [new branch]      Tugas-css -> Tugas-css
 * [new branch]      Tugas-finalProject -> Tugas-finalProject
 * [new branch]      Tugas-git -> Tugas-git
 * [new branch]      Tugas-html -> Tugas-html
 * [new branch]      Tugas-js -> Tugas-js
 * [new branch]      Tugas-midProject -> Tugas-midProject
 * [new branch]      Tugas-php -> Tugas-php

user@Caca MINGW64 ~/Documents/Pemrograman Web (master)
$ git clone https://github.com/monicaandelen28/TIK2032-Project
Cloning into 'TIK2032-Project'...
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 10 (delta 1), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (10/10), 6.37 KiB | 2.12 MiB/s, done.
Resolving deltas: 100% (1/1), done.

