# Git exercises
## Bundle 1
### Exercise 1 hey
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

 