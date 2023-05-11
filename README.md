# Terminal
### Задание 1

01. Посмотреть где я:  `pwd`
02. Создать папку: `mkdir group_30_free`
03. Зайти в папку: `cd !$`
04. Создать 3 папки: `mkdir QA_1 QA_2 QA_3`
05. Зайти в любоую папку: `cd QA_1/`
06.  Создать 5 файлов (3 txt, 2 json): `touch / Text1.txt Text2.txt Text3.txt Json1.json Json2.json`
07. Создать 3 папки: `mkdir QA_10 QA_11 QA_12`
08. Вывести список содержимого папки: `ls -la`
09. Открыть любой txt файл: `cat Text1.txt`
10. Написать туда что-нибудь, любой текст: `cat >> Text1.txt`
11. Cохранить и выйти: окончив ввод текста - `click Enter -> Ctrl + C`	
12. Выйти из папки на уровень выше: `cd ..`
13. Переместить любые 2 файла, которые вы создали, в любую другую папку: `mv Json1.json Json2.json QA_2/`
14. Cкопировать любые 2 файла, которые вы создали, в любую другую папку: `cp Text1.txt Text2.txt QA_3/`
15. Найти файл по имени: `find . -name "Text1.txt"`	
16. Просмотреть содержимое в реальном времени: `tail -f Text3.txt`
17. Вывести несколько первых строк из текстового файла: `head -4 Text1.txt`
18. Вывести несколько последних строк из текстового: `tail -3 Text2.txt`
19. Просмотреть содержимое длинного файла (команда less) изучите как она работает: `less Text1.txt`
20. Вывести дату и время: `date`
***
### Задание 2 *
1. Отправить http запрос на сервер http://162.55.220.72:5005/terminal-hw-request: 
   `curl http://162.55.220.72:5005/object_info_3?name=Alexander&age=31&salary=500`

2. Написать скрипт который выполнит автоматически пункты *3, 4, 5, 6, 7, 8, 13* из  Задания 1:
   
    Запуск скрипта:` ./newscript.sh`

#### Скрипт:

    >#!/bin/bash
    cd group_30_free 
    mkdir QA_4 QA_5 QA_6
    cd QA_4/
    pwd
    touch Text4.txt Text5.txt Text6.txt Json3.json Json4.json
    mkdir QA_7 QA_8 QA_9
    ls -la
    mv Text4.txt Text5.txt QA_7/
    echo "Done"
___
					

