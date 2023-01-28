git status
git init
git add *file.name*
git add . (все файлы)
git remote add awesomeapp https://github.com/someurl.. (удаленная папка)
git remote -v (удаленные файлы)
git remote show origin (подробные сведения об удалённом репозитории)
git commit -m "New commit"
git commit -a (коммит с добавлением)
git commit --amend -m "Updated message for the previous commit"
git push origin main (Отправка изменений в удалённый репозиторий)
git push -u origin new_branch (Отправка новой ветки в удалённый репозиторий)
git push --delete origin existing_branch (Удаление удалённой ветки)
git pull (Для загрузки изменений из удалённого репозитория)
git pull --verbose (подробные сведения о загруженных файлах )
git diff
git diff --staged
git diff *file.name*
git checkout *number.log*
git log -p
git log
git log --all
git log --all --oneline (в одну строку)
git show *commit*
git rm dirname/somefile.js (remove)
git rm dirname/*.html
git mv dir1/somefile.js dir2 (move)
git reset (восстановление файлов)
git reset HEAD somefile.js (reset)
git reset HEAD (all reset)
git revert *commit*(отменить изменения по коммиту)
git revert HEAD (отменить изменения)
git branch new_branch_name (новая ветка)
git checkout -b new_branch_name (переход к новой ветке)
git branch (display all branch)
git branch -a (display remove branch)
git branch -d existing_branch_name (delete branch)
git branch -D existing_branch_name (принудительный delete)
git push origin --delete existing_branch_name (удалить удаленную ветку)
git merge existing_branch_name (объединение веток)
git merge --no-ff existing_branch_name (выполнить коммит слияния)
git merge --abort (отмена слияния)
git merge origin (Слияние удалённого репозитория с локальным)
git log --graph --oneline --decorate (история коммитов в виде графика для текущей ветки)
git log --all --graph --oneline --decorate (всех веток)