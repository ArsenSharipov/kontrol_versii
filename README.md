# Инструкция по GIT

* Для создания репозитория используется команда *init*
```sh
git init
```
* Для добавления изменений в сохранение используется команда *add*
```sh
git add <filename>
```
* Для создания сохранения используется команда *commit -m "название сохранения"*
```sh
git commit -m "commitname"
```
* Для просмотра статуса изменений используется команда *status*
```sh
git status
```
* Для просмотра истории сохранений используется команда *git log*, ее укороченный вид *git log --oneline* и отображение слияния и появления веток команддой *git log --oneline -- graph*
```sh
git log
```
```sh
git log --oneline
```
```sh
git log -- oneline --graph
```
* Ддя переключения между сохрагениями используется команда *checkout*
```sh
git checkout <code>
```
* Для удаления файлов используется команда *restore*
```sh
git restore <filename>
```
* Для просмотра изменений в сохраниниях используется команда *diff*
```sh
git diff <code1> <code2>
```
* Для просмотра изменений необходимого коммита, хеш код которого известен, используется команда *show*
```sh
git show <hash>
```
* Для создания новой ветки используется команда *branch*
```sh
git branch new_branch_name
```
* Для перехода на необходимую ветку используется команда *checkout -b*
```sh
git checkout -b new_branch_name
```
* Для слияния основной ветки с нужной можно использовать команду *merge*
```sh
git merge branch_name
```
* Для подключения удаленного сервера используется команда *remote add origin*
```sh
git remote add origin https://github.com/.../repo_name.git
```
* Для переноса изменений на удаленный сервер используется команда *push -u*
```sh
git push -u origin branch_name
```