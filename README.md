# PLPBasicGitAssignment

$ cd desktop

ann muthoni@DESKTOP-THL8GRP MINGW64 ~/desktop (main)
$ cd plpgitbasics
bash: cd: plpgitbasics: No such file or directory

ann muthoni@DESKTOP-THL8GRP MINGW64 ~/desktop (main)
$ mkdir plpgitbasics

ann muthoni@DESKTOP-THL8GRP MINGW64 ~/desktop (main)
$ cd plpgitbasics

ann muthoni@DESKTOP-THL8GRP MINGW64 ~/desktop/plpgitbasics (main)
$ git init
Initialized empty Git repository in C:/Users/ann muthoni/Desktop/plpgitbasics/.git/

ann muthoni@DESKTOP-THL8GRP MINGW64 ~/desktop/plpgitbasics (master)
$ git remote add origin <https://github.com/Yuniskim/PLPBasicGitAssignment.git>
bash: syntax error near unexpected token `newline'

ann muthoni@DESKTOP-THL8GRP MINGW64 ~/desktop/plpgitbasics (master)
$ git remote add origin https://github.com/Yuniskim/PLPBasicGitAssignment.git

ann muthoni@DESKTOP-THL8GRP MINGW64 ~/desktop/plpgitbasics (master)
$ touch hello.text

ann muthoni@DESKTOP-THL8GRP MINGW64 ~/desktop/plpgitbasics (master)
$ code .

ann muthoni@DESKTOP-THL8GRP MINGW64 ~/desktop/plpgitbasics (master)
$ git add hello.text

ann muthoni@DESKTOP-THL8GRP MINGW64 ~/desktop/plpgitbasics (master)
$  git commit -m "Add hello.txt with a greeting"
[master (root-commit) e43e4dd] Add hello.txt with a greeting
 1 file changed, 1 insertion(+)
 create mode 100644 hello.text

ann muthoni@DESKTOP-THL8GRP MINGW64 ~/desktop/plpgitbasics (master)
$    git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Yuniskim/PLPBasicGitAssignment.git'

ann muthoni@DESKTOP-THL8GRP MINGW64 ~/desktop/plpgitbasics (master)
$ git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


ann muthoni@DESKTOP-THL8GRP MINGW64 ~/desktop/plpgitbasics (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Yuniskim/PLPBasicGitAssignment.git'

ann muthoni@DESKTOP-THL8GRP MINGW64 ~/desktop/plpgitbasics (master)
$  git push --set-upstream origin master
fatal: unable to access 'https://github.com/Yuniskim/PLPBasicGitAssignment.git/': Recv failure: Connection was reset

ann muthoni@DESKTOP-THL8GRP MINGW64 ~/desktop/plpgitbasics (master)
$  git push --set-upstream origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 239 bytes | 239.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/Yuniskim/PLPBasicGitAssignment/pull/new/master
remote:
To https://github.com/Yuniskim/PLPBasicGitAssignment.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

ann muthoni@DESKTOP-THL8GRP MINGW64 ~/desktop/plpgitbasics (master)
$
