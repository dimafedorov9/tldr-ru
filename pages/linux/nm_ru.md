# nm

> Выводит список содержащихся в объектном файле идентификаторов.

- Вывести список содержащихся в файле глобальных(внешних) функции(с префиксом T):

`nm -g {{file.o}}`

- Вывести идентификаторы C++ в удобочитаемом виде(раздекорированные - demangle):

`nm --demangle {{file.o}}`

- Вывести список содержащихся в файле неопределённых символов:

`nm -u {{file.o}}`

- Перечислить все символы, в том числе и отладочные:

`nm -a {{file.o}}`
