
# Инструкция по работе с GIT
Данная инструкция составлена для помощи себе в работе с системами контроля версий
## Создание репозитория

Для создания репозитория (говорят инициализация) нужно ввести в терминал комманду:

    git init

### Добавление версионности
    git add
Чтобы создать "сохранение" нужно сначала добавить файл котслеживанию версионности, а потом зафиксировать это изменение.

Для добавления комментария и фиксации изменения в файле, нужно ввести в терминал команду:

     git commit -m "comment"

## Создание веток

Для создание новой ветки используется команда 

    git branch "name branch"

## переход между ветками

Для перехода на другую ветку Используйте команду 
Git chechout "Name branch"

## Удаление веток
Для удаление ветки используйте команду:

    git branch -d "name branch"

## Логи и статус

### Для вызова журнала с коммитами нужно ввести команду:

    git logs

### Для того чтобы посмотреть статус и изменения в файле нужно ввести команду:

    git status

###  Чтобы показатьизменения между двумя коммитами, рабочими деревьями или файлами на диске нужно ввести команду:
    git diff -w

## Удалённые репозитории
