# git mv

> Перемещение или переименование файлов и обновление индекса git.

- Переместить файл в РЕПО и добавить перемещение в следующий коммит:

`git mv {{path/to/file}} {{new/path/to/file}}`

- Переименовать файл и добавить переименование в следующий коммит:

`git mv {{filename}} {{new_filename}}`

- Перезаписать файл в целевом пути, если он существует:

`git mv --force {{file}} {{target}}`
