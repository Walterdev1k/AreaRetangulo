# AreaRetangulo

walter-domiciano:~/development/Exercicios/AreaRetangulo(git:main)$ echo "# AreaRetangulo" >> README.md
walter-domiciano:~/development/Exercicios/AreaRetangulo(git:main)$ git init
Reinitialized existing Git repository in /home/walter-domiciano/development/Exercicios/AreaRetangulo/.git/
walter-domiciano:~/development/Exercicios/AreaRetangulo(git:main)$ git add README.md
walter-domiciano:~/development/Exercicios/AreaRetangulo(git:main)$ git status
On branch main
No commits yet
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   .gitignore
	new file:   .idea/.gitignore
	new file:   .idea/misc.xml
	new file:   .idea/modules.xml
	new file:   .idea/vcs.xml
	new file:   AreaRetangulo.iml
	new file:   README.md
	new file:   src/CalculaAreaRetangulo.java
	new file:   src/Main.java

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   src/CalculaAreaRetangulo.java

walter-domiciano:~/development/Exercicios/AreaRetangulo(git:main)$ git commit -m "first commit"
[main (root-commit) f67276b] first commit
 9 files changed, 83 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 .idea/.gitignore
 create mode 100644 .idea/misc.xml
 create mode 100644 .idea/modules.xml
 create mode 100644 .idea/vcs.xml
 create mode 100644 AreaRetangulo.iml
 create mode 100644 README.md
 create mode 100644 src/CalculaAreaRetangulo.java
 create mode 100644 src/Main.java
walter-domiciano:~/development/Exercicios/AreaRetangulo(git:main)$ git branch -M main
walter-domiciano:~/development/Exercicios/AreaRetangulo(git:main)$ git remote add origin https://github.com/Walterdev1k/AreaRetangulo.git
walter-domiciano:~/development/Exercicios/AreaRetangulo(git:main)$ git push -u origin main
Enumerating objects: 13, done.
Counting objects: 100% (13/13), done.
Delta compression using up to 4 threads
Compressing objects: 100% (11/11), done.
Writing objects: 100% (13/13), 2.13 KiB | 727.00 KiB/s, done.
Total 13 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Walterdev1k/AreaRetangulo.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
