# Git exercises
## Bundle 1
### Exercise 1
Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/onedrive/desktop/github exercises/bunE1 (master)
$ git branch -m main

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/onedrive/desktop/github exercises/bunE1 (main)
$ git add .

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/onedrive/desktop/github exercises/bunE1 (main)
$ git commit -m 'Added new Files'
[main (root-commit) f9d3bdc] Added new Files
 4 files changed, 4 insertions(+)
 create mode 100644 file1.js
 create mode 100644 file2.js
 create mode 100644 index.html
 create mode 100644 readme.md

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/onedrive/desktop/github exercises/bunE1 (main)
$ git fetch

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/onedrive/desktop/github exercises/bunE1 (main)
$ git remote add origin https://github.com/kamufozi/exercise-1.git

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/onedrive/desktop/github exercises/bunE1 (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (5/5), 367 bytes | 183.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kamufozi/exercise-1.git
 * [new branch]      main -> main

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/onedrive/desktop/github exercises/bunE1 (main)
$ git checkout -b dev
Switched to a new branch 'dev'

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/onedrive/desktop/github exercises/bunE1 (dev)
$ git push origin dev
fatal: unable to access 'https://github.com/kamufozi/exercise-1.git/': OpenSSL SSL_connect: SSL_ERROR_SYSCALL in connection to github.com:443

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/onedrive/desktop/github exercises/bunE1 (dev)
$ git push origin dev
fatal: unable to access 'https://github.com/kamufozi/exercise-1.git/': OpenSSL SSL_connect: SSL_ERROR_SYSCALL in connection to github.com:443

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/onedrive/desktop/github exercises/bunE1 (dev)
$ git push origin dev


Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/onedrive/desktop/github exercises/bunE1 (dev)
$ git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/kamufozi/exercise-1/pull/new/dev
remote:
To https://github.com/kamufozi/exercise-1.git
 * [new branch]      dev -> dev

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/onedrive/desktop/github exercises/bunE1 (dev)
$ git checkout -b test
Switched to a new branch 'test'

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/onedrive/desktop/github exercises/bunE1 (test)
$ git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/kamufozi/exercise-1/pull/new/test
remote:
To https://github.com/kamufozi/exercise-1.git
 * [new branch]      test -> test

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/onedrive/desktop/github exercises/bunE1 (test)
$ git checkout dev
Switched to branch 'dev'

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/onedrive/desktop/github exercises/bunE1 (dev)
$ git branch -d test
Deleted branch test (was f9d3bdc).

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/onedrive/desktop/github exercises/bunE1 (dev)
$ git push --delete test
fatal: --delete doesn't make sense without any refs

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/onedrive/desktop/github exercises/bunE1 (dev)
$ ^C

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/onedrive/desktop/github exercises/bunE1 (dev)
$ git push origin --delete test
To https://github.com/kamufozi/exercise-1.git
 - [deleted]         test

### Exercise 2
PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git add . 
PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git stash home.html
fatal: subcommand wasn't specified; 'push' can't be assumed due to unexpected token 'home.html'
PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git stash push home.html
Saved working directory and index state WIP on B1E2: b3249c1  Redeleted the files
PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git add .
PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git stash push about.html
Saved working directory and index state WIP on B1E2: b3249c1  Redeleted the files
PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git add .
PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git stash push team.html 
Saved working directory and index state WIP on B1E2: b3249c1  Redeleted the files
PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git stash list
stash@{0}: WIP on B1E2: b3249c1 Redeleted the files
stash@{1}: WIP on B1E2: b3249c1 Redeleted the files
stash@{2}: WIP on B1E2: b3249c1 Redeleted the files
PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git stash pop 'stash@{1}'
On branch B1E2
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (7b734f6f3b19691c5e38d5ab88fd28a3759a6993)
PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git add .
PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git stash pop 'stash@{2}'
fatal: log for 'stash' only has 2 entries
PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git stash pop 'stash@{1}'
On branch B1E2
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Dropped stash@{1} (5dac81a1712d92d891c8d7f17d781fa4d988653c)
PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git add .
PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git status
On branch B1E2
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git commit -m " Added the files " 
[B1E2 d1d6bec]  Added the files
 2 files changed, 28 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html
 PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git remote add origin https://github.com/kamufozi/Gym-Git-Exercise-Solution.git
PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git push origin 
fatal: The current branch B1E2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin B1E2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git push origin B1E2
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 8 threads
Compressing objects: 100% (11/11), done.
Writing objects: 100% (15/15), 1.94 KiB | 180.00 KiB/s, done.
Total 15 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'B1E2' on GitHub by visiting:
remote:      https://github.com/kamufozi/Gym-Git-Exercise-Solution/pull/new/B1E2
remote:
To https://github.com/kamufozi/Gym-Git-Exercise-Solution.git
 * [new branch]      B1E2 -> B1E2
PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git stash list
stash@{0}: WIP on B1E2: b3249c1 Redeleted the files
PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git stash pop
On branch B1E2
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped refs/stash@{0} (d5a1c77aa9bbf5606635c16f4b099dffe18c49a7)
PS C:\Users\Fozi Chris\OneDrive\Desktop\Github exercises\B1E2> git reset --hard
HEAD is now at d1d6bec  Added the files