# Лабораторная работа №2

## Задача
Написать два Dockerfile – плохой и хороший. Плохой должен запускаться и работать корректно, но в нём должно быть не менее 3 “bad practices”. В хорошем Dockerfile они должны быть исправлены. В Readme описать все плохие практики из кода Dockerfile и почему они плохие, как они были исправлены в хорошем  Dockerfile, а также две плохие практики по использованию этого контейнера.

## Плохие практики
/ см not good/Dokerfile
1.	Использован latest вместо конкретной версии (в последствии может возникнуть ситуация, когда при обновлении используемые методы будут работать иначе, что приведет к ошибкам и сбоям)
2.	Не указана рабочая папка, что приводит к нагромождению команд, за счет повторяющегося текста
3.	Созданы лишние слои, где в этом нет необходимости, что приводит к задействованию лишних ресурсов

## Исправление проблем
/ см good/Dokerfile
1. Использована конкретная версия python:3.9-slim, которая подходит для выполнения наших задач. В будущем это не создаст ситуацию, когда код внутри контейнера будет противоречить версии.
2. Указана рабочаа папка, что позволило сократить некоторые записи внутри Dokerfile
3. Слои объединены в один, что ускоряет работу контейнера

## Плохие практики использования контейнера
1. Запуск процессов от имени root (это может повлечь за собой угрозу безопасности).
2. Хранение данных внутри контейнера (можно использовать docker volumes, если очень хочется)

## Вывод
Ура, мы поняли. что такое Doker и Dokerfile!

## Еще один Просто Жираф
![JustGiraffe](https://github.com/Ulitka-na-sklone/White-maned-horses/blob/main/DevOps%202%20lab/GiraffeTLoA.jpg?raw=true)
