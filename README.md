##### 04a-Atividade-1
Repositório criado com a finalidade de responder a atividade proposta pelo SENAI-SP em seu curso “Programador Full-Stack” que, dentre vários assuntos, aborda o tema “Versionamento”.
---

# Histórico das ações/comandos inseridos no terminal (prompt de Comando)

```
User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1
$ git clone https://github.com/thaumodan/04a-Atividade-1.git
Cloning into '04a-Atividade-1'...
warning: You appear to have cloned an empty repository.

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1
$ cd 04a-Atividade-1/

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (main)
$ git remote -v
origin  https://github.com/thaumodan/04a-Atividade-1.git (fetch)
origin  https://github.com/thaumodan/04a-Atividade-1.git (push)

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Index.txt

nothing added to commit but untracked files present (use "git add" to track)

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (main)
$ git add Index.txt

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Index.txt


User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (main)
$ git commit -m "Primeiro Commit na branch main"
[main (root-commit) 5e53081] Primeiro Commit na branch main
 1 file changed, 8 insertions(+)
 create mode 100644 Index.txt

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (main)
$ git push origin -u main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 308 bytes | 308.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/thaumodan/04a-Atividade-1.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (main)
$ git checkout -b feature1
Switched to a new branch 'feature1'

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (feature1)
$ git status
On branch feature1
nothing to commit, working tree clean

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (feature1)
$ git push origin feature1
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'feature1' on GitHub by visiting:
remote:      https://github.com/thaumodan/04a-Atividade-1/pull/new/feature1
remote:
To https://github.com/thaumodan/04a-Atividade-1.git
 * [new branch]      feature1 -> feature1

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (feature1)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Index.txt

no changes added to commit (use "git add" and/or "git commit -a")

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (main)
$ git add Index.txt

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (main)
$ git commit -m "Segundo Commit na branch main"
[main 1547caa] Segundo Commit na branch main
 1 file changed, 1 insertion(+), 1 deletion(-)

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 334 bytes | 334.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/thaumodan/04a-Atividade-1.git
   5e53081..1547caa  main -> main

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (main)
$ git checkout feature1
Switched to branch 'feature1'

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (feature1)
$ git status
On branch feature1
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Index.txt

no changes added to commit (use "git add" and/or "git commit -a")

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (feature1)
$ git add Index.txt

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (feature1)
$ git commit -m "Segundo Commit na branch feature1"
[feature1 ea66bfc] Segundo Commit na branch feature1
 1 file changed, 1 insertion(+), 1 deletion(-)

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (feature1)
$ git push origin feature1
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 301 bytes | 301.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/thaumodan/04a-Atividade-1.git
   5e53081..ea66bfc  feature1 -> feature1

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (feature1)
$ git merge main
Auto-merging Index.txt
CONFLICT (content): Merge conflict in Index.txt
Automatic merge failed; fix conflicts and then commit the result.

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (feature1|MERGING)
$ git status
On branch feature1
You have unmerged paths.
  (fix conflicts and run "git commit")
  (use "git merge --abort" to abort the merge)

Unmerged paths:
  (use "git add <file>..." to mark resolution)
        both modified:   Index.txt

no changes added to commit (use "git add" and/or "git commit -a")

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (feature1|MERGING)
$ git add Index.txt

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (feature1|MERGING)
$ git commit -m "Resolvendo Conflitos pela branch feature1"
[feature1 ab46f92] Resolvendo Conflitos pela branch feature1

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (feature1)
$ git push origin feature1
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 326 bytes | 326.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/thaumodan/04a-Atividade-1.git
   ea66bfc..ab46f92  feature1 -> feature1

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (feature1)
$ git status
On branch feature1
nothing to commit, working tree clean

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (feature1)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

User@NotebookTeA MINGW64 ~/Desktop/Programador FullStack/Versionamento/git/04a-Atividade-1/04a-Atividade-1 (main)
$
```

