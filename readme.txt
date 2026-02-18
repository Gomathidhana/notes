>git config --global user.name "Gomathidhana"

git config --global user.name "Gomathidhana"

C:\Users\Cistron IT 3>git config --global user.email "gomathideveloper@gmail.com"

D:\Git>git init
D:\Git>git add readme.txt

D:\Git>git commit -m "I did second change"
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        First Project/

nothing added to commit but untracked files present (use "git add" to track)

D:\Git>git add "readme.txt"

D:\Git>git add .
warning: adding embedded git repository: First Project
D:\Git>git commit -m "my first comment"
[main 19cbdd3] my first comment
 1 file changed, 1 insertion(+)
 create mode 160000 First Project

D:\Git>git remote add origin https://github.com/Gomathidhana/notes.git
error: remote origin already exists.

D:\Git>git branch -M main

D:\Git>git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 519 bytes | 519.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Gomathidhana/notes.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

D:\Git>git add "readme.txt"

D:\Git>git commit -m "added second lines"
[main 7a8bb07] added second lines
 1 file changed, 5 insertions(+), 1 deletion(-)

D:\Git>git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 392 bytes | 392.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Gomathidhana/notes.git
   19cbdd3..7a8bb07  main -> main
branch 'main' set up to track 'origin/main'.