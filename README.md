# branchtest


harun.m@TA21117 MINGW64 ~/Desktop/Kalai
$ git clone https://github.com/harundevops-repo/testing_ks.git
Cloning into 'testing_ks'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

harun.m@TA21117 MINGW64 ~/Desktop/Kalai
$ cd testing_ks/

harun.m@TA21117 MINGW64 ~/Desktop/Kalai/testing_ks (main)
$ git checkou dev
git: 'checkou' is not a git command. See 'git --help'.

The most similar command is
        checkout

harun.m@TA21117 MINGW64 ~/Desktop/Kalai/testing_ks (main)
$ git checkout dev
Switched to a new branch 'dev'
branch 'dev' set up to track 'origin/dev'.

harun.m@TA21117 MINGW64 ~/Desktop/Kalai/testing_ks (dev)
$ git add Testing.txt

harun.m@TA21117 MINGW64 ~/Desktop/Kalai/testing_ks (dev)
$ git commit -m "Empty file added for testing"
[dev a72ae1d] Empty file added for testing
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Testing.txt

harun.m@TA21117 MINGW64 ~/Desktop/Kalai/testing_ks (dev)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 294 bytes | 294.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/harundevops-repo/testing_ks.git
   2d2dfe6..a72ae1d  dev -> dev

harun.m@TA21117 MINGW64 ~/Desktop/Kalai/testing_ks (dev)
$
