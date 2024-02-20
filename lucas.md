# Teste do Luquinha

- Qualquer Coisa
- Ocarina of Time
<input type = "checkbox">
<input type = "checkbox">
<input type = "image">
<input type = "password">
<input type = "image">
<input type = "search">
<input type = "radio">
<input type = "color">
<input type = "email">
- qualquer coisa
<input type = "number">
<input type = "file">

<input type = "date">
<input type = "month">
PS C:\Users\L309_SUPER_15\GitTeste> git branch
  back_end
  front_end
* main
PS C:\Users\L309_SUPER_15\GitTeste> git checkout back_end
Switched to branch 'back_end'
Your branch is up to date with 'origin/back_end'.
PS C:\Users\L309_SUPER_15\GitTeste> git branch
* back_end
  front_end
  main
PS C:\Users\L309_SUPER_15\GitTeste> git push
Everything up-to-date
PS C:\Users\L309_SUPER_15\GitTeste> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\L309_SUPER_15\GitTeste> git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\Users\L309_SUPER_15\GitTeste> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   lucas.md

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\L309_SUPER_15\GitTeste> git add .
PS C:\Users\L309_SUPER_15\GitTeste> git commit -m "alteração"
[main 8224e68] alteração
 1 file changed, 6 insertions(+), 1 deletion(-)
PS C:\Users\L309_SUPER_15\GitTeste> git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 347 bytes | 347.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:Lukarelly/GitTeste.git
   25cc541..8224e68  main -> main
PS C:\Users\L309_SUPER_15\GitTeste>