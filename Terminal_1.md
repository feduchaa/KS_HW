# terminal 
Environment: MacOS
1. Посмотреть где я
```bash
pwd
```
2. Создать папку
```bash
mkdir meal
```
3. Зайти в папку
```bash
cd meal
```
4. Создать 3 папки
```bash
mkdir morning afternoon evening
```
5. Зайти в любую папку
```bash
cd morning
```
6. Cоздать 5 файлов (3 txt, 2 json)
```bash
touch breakfast.txt brunch.json lunch.txt snack.json dinner.txt
```
7. Создать 3 папки
```bash
mkdir utensils ingredients menu
```
8. Вывести список содержимого папки
```bash
ls -la
# ls -a (горизонтальное отображение)
```
9. Открыть любой txt файл
```bash
cat morning.txt
```
10. Написать туда что-нибудь, любой текст
```bash
nano breakfast.txt
```
11. Сохранить и выйти
```bash
control+O control+X Eneter
```
12. Выйти из папки на уровень выше
```bash
cd ..
```
13. Переместить любые 2 файла, которые вы создали, в любую другую папку
```bash
mv morning/brunch.json morning/lunch.txt afternoon
```
14. Скопировать любые 2 файла, которые вы создали, в любую другую папку
```bash
cp morning/snack.json morning/dinner.txt evening
```
15. Найти файл по имени
```bash
find . -name breakfast.txt
```
16. Просмотреть содержимое в реальном времени
```bash
tail -F morning/breakfast.txt
```
17. Вывести несколько первых строк из текстового файла
```bash
head -2 placement-list morning/breakfast.txt
```
18. Вывести несколько последних строк из текстового файла
```bash
tail -3 placement-list morning/breakfast.txt
```
19. Просмотреть содержимое длинного файла (команда less) изучите как она работает
```bash
less morning/breakfast.txt
```
20. Вывести дату и время
```bash
date
```
Задание *
1. Отправить http запрос на сервер.
http://162.55.220.72:5005/terminal-hw-request
```bash
curl http://162.55.220.72:5005/terminal-hw-request
curl “http://162.55.220.72:5005/get_method?name=Kris&age=28”
```
2. Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13
```bash
cd ssskr
mkdir morning afternoon evening
cd morning
touch breakfast.txt brunch.json lunch.txt snack.json dinner.txt
mkdir menu utensils ingredients
ls -la
cd ..
mv morning/snack.json morning/dinner.txt evening
```





