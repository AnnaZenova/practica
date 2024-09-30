# Список основных команд и понятий

1. pwd - показывает рабочую папку, выводит путь к текущей директории
2. cd -  позволяет сменить директорию
3. ls - выводит содержимое директории
4. touch - создает файл
5. mkdir - создает директорию
6. cp - копирует файлы
7. mr - удаляет файл в одном месте и удаляет в другом
8. cat - позволяет прочитать файл
9. rm - уаляет файл
10. rmdir - удаляет директорию
11. rm -r - рекурсивно удаляе файлы и саму директорию
12. && - позволяет указывать команды списком


*При использовани различных флагов основные команды меняют свою функциональность и позволяют эффективнее работать с консолью*

-----

##Список команд для работы с Git-репозиториями
- git init - создать локальный репозиторий
- git add - запоминает текущее состояние файла
- git commit -m - сохраняет текущую версию файла с комментарием
- git log - позволяет посмотреть историю коммитов
- git push - отправляет изменения на удаленный репозиторий
- git clone - клонирует репозиторий (удаленный)
- fork - создает копию удаленного репозитория

----------

###Список статусов, получаемых через git status
- untracked - не отслеживаемый файл
- staged - после git add файл попадает в staging area
- tracked - файлы, в которых Git отслеживает изменения
- modified - Git сравнил версии файлов и нашел различия