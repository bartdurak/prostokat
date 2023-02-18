# prostokat
fed@fed-Komputer MINGW64 ~
$ cd ~/Pictures/
desktop.ini  pytanie_2/

fed@fed-Komputer MINGW64 ~
$ cd ~/Pictures/pytanie_2/

fed@fed-Komputer MINGW64 ~/Pictures/pytanie_2
$ pwd
/c/Users/fed/Pictures/pytanie_2

fed@fed-Komputer MINGW64 ~/Pictures/pytanie_2
$ ls
CMakeLists.txt  Sources/            main.cpp     pytanie.h
Headers/        cmake-build-debug/  pytanie.cpp

fed@fed-Komputer MINGW64 ~/Pictures/pytanie_2
$ eecho "# prostokat" >> README.md
bash: $'\302\226echo': command not found

fed@fed-Komputer MINGW64 ~/Pictures/pytanie_2
$echo "# prostokat" >> README.md

fed@fed-Komputer MINGW64 ~/Pictures/pytanie_2
$ ls
CMakeLists.txt  README.md  cmake-build-debug/  pytanie.cpp
Headers/        Sources/   main.cpp            pytanie.h

fed@fed-Komputer MINGW64 ~/Pictures/pytanie_2
$ git add README.md
fatal: not a git repository (or any of the parent directories): .git

fed@fed-Komputer MINGW64 ~/Pictures/pytanie_2
$ git init
Initialized empty Git repository in C:/Users/fed/Pictures/pytanie_2/.git/

fed@fed-Komputer MINGW64 ~/Pictures/pytanie_2 (master)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

fed@fed-Komputer MINGW64 ~/Pictures/pytanie_2 (master)
$ ls
CMakeLists.txt  README.md  cmake-build-debug/  pytanie.cpp
Headers/        Sources/   main.cpp            pytanie.h

fed@fed-Komputer MINGW64 ~/Pictures/pytanie_2 (master)
$ git commit -m "pierwszy comint"
[master (root-commit) ca57c87] pierwszy comint
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

fed@fed-Komputer MINGW64 ~/Pictures/pytanie_2 (master)
$ git branch -M main

fed@fed-Komputer MINGW64 ~/Pictures/pytanie_2 (main)
$ git remote add origin https://github.com/bartdurak/prostokat.git

fed@fed-Komputer MINGW64 ~/Pictures/pytanie_2 (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 227 bytes | 227.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/bartdurak/prostokat.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

fed@fed-Komputer MINGW64 ~/Pictures/pytanie_2 (main)
