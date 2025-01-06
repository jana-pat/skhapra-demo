S C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops> git clone https://github.com/1ds22cb031/fazan.git
Cloning into 'fazan'...
info: please complete authentication in your browser...
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 4 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (4/4), done.
PS C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops> git status
fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops> cd fazan
PS C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops\fazan> git branch 
* main
PS C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops\fazan> git add a.html
PS C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops\fazan> git statuss
git: 'statuss' is not a git command. See 'git --help'.

The most similar command is
        status
PS C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops\fazan> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   a.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        xyz.html

PS C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops\fazan> git branch
* main
PS C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops\fazan> git commit -m ahkjagdasgkd
[main b9e830f] ahkjagdasgkd
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 a.html
PS C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops\fazan> git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 314 bytes | 157.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/1ds22cb031/fazan.git
   d845e2f..b9e830f  main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops\fazan> git branch
* main
PS C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops\fazan> git branch devtest
PS C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops\fazan> git checkout devtest 
Switched to branch 'devtest'
PS C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops\fazan> git branch 
* devtest
  main
PS C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops\fazan> git add .
PS C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops\fazan> git commit -m sfhkshfhads
[devtest 4c14531] sfhkshfhads
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 xyz.html
PS C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops\fazan> git push  origin devtest
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 258 bytes | 258.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'devtest' on GitHub by visiting:
remote:      https://github.com/1ds22cb031/fazan/pull/new/devtest
remote:
To https://github.com/1ds22cb031/fazan.git
 * [new branch]      devtest -> devtest
PS C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops\fazan> git branch 
* devtest
  main
PS C:\Users\Fazan shariff\AppData\Local\Microsoft\Windows\INetCache\IE\4U8TFFCQ\devops\fazan>
