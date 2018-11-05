---
title: Bash Cat
localeTitle: Bash Cat
---
## Bash Cat

Cat является одной из наиболее часто используемых команд в операционных системах Unix.

cat используется для последовательного чтения файла и печати его на стандартный вывод. Название происходит от его функции к кон**кат**енации файлов.

### использование

```bash
cat [options] [file_names] 
```

Наиболее часто используемые опции:

*   `-b` , нумеровать только непустые строки
*   `-n` , нумеровать все строки
*   `-s` , сжать несколько смежных пустых строк
*   `-v` , отображать непечатаемые символы, за исключением отступов и символа конца строки

### пример

Вывести в терминал содержимое файла file.txt:

```bash
cat file.txt 
```

Соединить содержимое двух файлов и вывести результат в терминал:

```bash
cat file1.txt file2.txt 
```

#### Дополнительная информация:

*   Википедия: https://en.wikipedia.org/wiki/Cat_(Unix)