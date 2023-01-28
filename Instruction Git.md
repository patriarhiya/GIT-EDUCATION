# Инструкция GIT
## Введение
**Коммит** - слепок изменений. Чтобы закоммитить - сначала необходимо добавить подготовленные файлы к коммиту командой *add*

## Локально
| Команда | Описание |
|-|-|
| git status | Проверить статус файлов |
| git init | Инициализация нужной папки - если ранее не проводилась, то будет создана папка .git |
|git add *file.name*|-|
|git add . (все файлы)|-|
|git commit -m "New commit"|-|
|git commit --amend -m "Updated message for the previous commit"|-|
|git diff|-|
|git diff --staged|-|
|git diff *file.name*|-|
|git checkout *number.log*|-|
|git log|-|
|git log -p|-|
|git log --all --oneline|-|
|-|-|

## Удаленно
| Команда | Описание |
|git remote add awesomeapp https://github.com/someurl..|-|
|git remote -v|-|
|git remote show origin|-|
|git push origin main (Отправка изменений в удалённый репозиторий)|-|
|git push -u origin new_branch (Отправка новой ветки в удалённый репозиторий)|-|
|git push --delete origin existing_branch (Удаление удалённой ветки)|-|
|git pull (Для загрузки изменений из удалённого репозитория)|-|
|git pull --verbose (подробные сведения о загруженных файлах )|-|
|-|-|
|-|-|
|-|-|
|-|-|
