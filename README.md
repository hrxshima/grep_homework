# Лабораторная работа по команде grep

## Введение

Команда grep (Global Regular Expression Print) является мощным инструментом для поиска текстовых шаблонов в файлах. Она позволяет находить строки, содержащие определенные слова или регулярные выражения, что делает её незаменимой для анализа логов, обработки текстовых данных и многих других задач.

## Разминка (не включается в отчёт)

##### Цель: научиться использовать команду grep для поиска строк в текстовом файле.

1. Создайте текстовый файл с именем example.txt и добавьте в него несколько строк текста. Например:
```
Привет, мир!
Это пример файла.
grep - мощный инструмент.
Используйте grep для поиска.
```

2. Откройте терминал и выполните команду:
```
grep "пример" example.txt
```
Вывод должен показать строку, содержащую слово "пример".

3. Попробуйте выполнить поиск без учета регистра:
```
grep -i "GREP" example.txt
```
Это должно вернуть строки, содержащие "grep", независимо от регистра.

4. Чтобы увидеть номера строк, где найдено совпадение, используйте ключ -n:
```
grep -n "Используйте" example.txt
```

5. Для поиска нескольких слов используйте опцию -e:
```
grep -e "мир" -e "инструмент" example.txt
```
## Задача на выполнение
Теперь, когда вы ознакомились с основами работы команды grep, выполните следующее задание:
1. Создайте файл data.txt и заполните его данными о ваших любимых книгах (название, автор, год издания).
2. Напишите команду, которая найдет все книги, изданные в 20-м веке.
3. Посчитайте количество книг, написанных автором, имя которого начинается на букву "Д".
4. Напишите команду, которая выведет все книги в формате:
```
Название книги (Год издания)
```
## Ссылки на материалы
1. [Grep Command Tutorial with Examples for Beginners. ](https://ostechnix.com/the-grep-command-tutorial-with-examples-for-beginners/)
2. [Linux Grep Command Examples. ](https://linuxblog.io/grep-command-in-linux-w-examples/)
3. [How to Use the Grep Command in Linux. ](https://www.hostinger.com/tutorials/grep-command-in-linux)

