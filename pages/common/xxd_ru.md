# xxd

> Создать шестнадцатеричный дамп бинарных данных, либо получить бинарные данные из дампа.

- Получить шестнадцатеричный дамп из бинарного файла и вывести результат на стандартный вывод:

`xxd {{input_file}}`

- Получить шестнадцатеричный дамп из бинарного файла и сохранить в файл:

`xxd {{input_file}} {{output_file}}`

- Вывести результат `xxd` в виде колонки по 8 байт в строке (со служебной информацией в виде отступов и предпросмотра байт):

`xxd -c {{8}} {{input_file}}`

- Вывести шестнадцатеричный дамп в "сыром виде" – без служебной информации:

`xxd -p {{input_file}}`

- Получить бинарные данные из файла {{input_file}} с дампом и сохранить в файл {{output_file}}:

`xxd -r -p {{input_file}} {{output_file}}`
