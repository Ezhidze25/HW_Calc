# Решение CTF "Калькулятор"
При переходе на сайт видим поле для ввода:

![Первый заход на сайт](https://github.com/Ezhidze25/HW_Calc/blob/main/Screenshot_134.png?raw=true)

Путём подбора спец. символов получаем, что сервер воспринимает как команду текст, заключённый в данные " ` " символы

Вводим команду `ls`

![Просмотр содержания директории](https://github.com/Ezhidze25/HW_Calc/blob/main/Screenshot_135.png?raw=true)

Просматриваем содержимое файла командой `cat index.php`

![Просмотр содержимого файла](https://github.com/Ezhidze25/HW_Calc/blob/main/Screenshot_136.png?raw=true)

Находим флаг: ***CODEBY{f1lt3r_byp4ss3r}***
