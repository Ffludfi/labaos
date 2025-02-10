
(C) Корпорация Майкрософт (Microsoft Corporation). Все права защищены.

Установите последнюю версию PowerShell для новых функций и улучшения! https://aka.ms/PSWindows

(.venv) PS C:\work programs\pypy> git init
Initialized empty Git repository in C:/work programs/pypy/.git/
(.venv) PS C:\work programs\pypy> git add . 
warning: in the working copy of '.idea/inspectionProfiles/profiles_settings.xml', LF will be replaced by CRLF the next time Git touches it
(.venv) PS C:\work programs\pypy> git init
Reinitialized existing Git repository in C:/work programs/pypy/.git/
(.venv) PS C:\work programs\pypy> git add . 
(.venv) PS C:\work programs\pypy> gir commit -m "10.02.2025 laba 1"
gir : Имя "gir" не распознано как имя командлета, функции, файла сценария или выполняемой программы. Проверьте правильность написания имени, а также наличие и правильность пути, после чего повторите попытку.
строка:1 знак:1
+ gir commit -m "10.02.2025 laba 1"
+ ~~~
    + CategoryInfo          : ObjectNotFound: (gir:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

(.venv) PS C:\work programs\pypy> git commit -m "10.02.2025 laba 1"
[master (root-commit) 674bad6] 10.02.2025 laba 1
 8 files changed, 48 insertions(+)
 create mode 100644 .idea/.gitignore
 create mode 100644 .idea/inspectionProfiles/profiles_settings.xml
 create mode 100644 .idea/misc.xml
 create mode 100644 .idea/modules.xml
 create mode 100644 .idea/pypy.iml
 create mode 100644 .idea/vcs.xml
 create mode 100644 abobus.py
 create mode 100644 main.py
(.venv) PS C:\work programs\pypy> git remote add origin https://github.com/Ffludfi/labaos.git
(.venv) PS C:\work programs\pypy> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Ffludfi/labaos.git'
(.venv) PS C:\work programs\pypy> git push -u origin master
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 12 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (12/12), 1.54 KiB | 788.00 KiB/s, done.
Total 12 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Ffludfi/labaos.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.
(.venv) PS C:\work programs\pypy> ls


    Каталог: C:\work programs\pypy


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        11.02.2025      0:00                labaos1


(.venv) PS C:\work programs\pypy> git init
Reinitialized existing Git repository in C:/work programs/pypy/.git/
(.venv) PS C:\work programs\pypy> git add . 
warning: in the working copy of 'labaos1/.idea/inspectionProfiles/profiles_settings.xml', LF will be replaced by CRLF the next time Git touches it
(.venv) PS C:\work programs\pypy> git commit -m "laba 1 10.02.2025"
[master d029fc7] laba 1 10.02.2025
 8 files changed, 0 insertions(+), 0 deletions(-)
 rename {.idea => labaos1/.idea}/.gitignore (100%)
 rename {.idea => labaos1/.idea}/inspectionProfiles/profiles_settings.xml (100%)
 rename {.idea => labaos1/.idea}/misc.xml (100%)
 rename {.idea => labaos1/.idea}/modules.xml (100%)
 rename {.idea => labaos1/.idea}/pypy.iml (100%)
 rename {.idea => labaos1/.idea}/vcs.xml (100%)
 rename abobus.py => labaos1/abobus.py (100%)
 rename main.py => labaos1/main.py (100%)
(.venv) PS C:\work programs\pypy> git push origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (1/1), done.
Writing objects: 100% (2/2), 231 bytes | 231.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Ffludfi/labaos.git
   674bad6..d029fc7  master -> master
(.venv) PS C:\work programs\pypy>    
