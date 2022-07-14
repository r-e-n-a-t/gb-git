# Руководство по работе с Git

## Инициализация репозитория
*git init*

---

## Посмотреть все установленные настройки 
*git config --list*

---

## Настройка пользователя
*git config --global user.name "name"*

*git config --global user.email email*

---

## Проверить статус репозитория 
*git status*

---

## Посмотреть изменения 
*git diff*

---

## Добавить изменения в индекс 
*git add*

---

## Просмотр истории коммитов
*git log*

---

## Создать коммит
*git commit -m 'commit text'*

---

## Перейти в коммит
### По номеру
*git checkout commit №*
### В последний
*git checkout master*

---

## Создать новую ветку
*git branch name

---

## Перенос основания ветки
*git rebase name
<<<<<<< HEAD
### послеразрешения всех конфликтов ввести 
*git rebase --continue
=======
### для отмены переноса ввести
*git rebase --abort
>>>>>>> new-feature

---

## вливание одной ветки в другую
*git marge name

---

