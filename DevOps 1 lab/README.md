# DevOps. Лабораторная работа №1.

## Состав команды
- Волжева Мария Ильинична (Капитан)
- Морозов Артём Андреевич
- Красюк Карина Александровна
- Зотов Михаил Дмитриевич

## Ход работы
1. Подсоединяем 3 компьютера(устройства A, B, C) к одной локальной сети
2. На устройствах В и С выполняем команду по определению их IP-адреса

![Скрин с устройства В 1](https://github.com/Ermack241/White---maned-horses/blob/main/DevOps%201%20lab/pic/photo_2023-10-06_18-45-52.jpg)

Рис 1. - Скрин с устройства В

3. С устройства A удаленно заходим на устройство В:

![Скрин с устройства A 1](https://github.com/Ermack241/White---maned-horses/blob/main/DevOps%201%20lab/pic/photo_2023-10-06_18-46-13.jpg)

Рис 2. - Скрин с устройства A

4. Теперь мы удаленно находимся на устройстве B и с удаленного устройства B заходим на удаленное устройство С. 

![Скрин с устройства A 2](https://github.com/Ermack241/White---maned-horses/blob/main/DevOps%201%20lab/pic/photo_2023-10-06_18-46-16.jpg)

Рис 3. - Скрин с устройства A

5. На устройстве С выбираем/находим файл, который хотим скопировать и запоминаем его путь. Мы выбрали файл 1_1.py (его путь на устройстве С -  /tmp/1_1.py)

![Скрин с устройства A 3](https://github.com/Ermack241/White---maned-horses/blob/main/DevOps%201%20lab/pic/photo_2023-10-06_18-46-21.jpg)

Рис 4. - Скрин с устройства A

6. Выходим с удаленного устройства С и оказывается на удаленном устройстве B

![Скрин с устройства A 4](https://github.com/Ermack241/White---maned-horses/blob/main/DevOps%201%20lab/pic/photo_2023-10-06_18-46-24.jpg)

Рис 5. - Скрин с устройства A

7. Скрин, как доказательство, что в текущем каталоге на устройстве B не было файла, который мы будем копировать

![Скрин с устройства A 5](https://github.com/Ermack241/White---maned-horses/blob/main/DevOps%201%20lab/pic/photo_2023-10-06_18-46-27.jpg)

Рис 5. - Скрин с устройства A

8. Выполняем копирование файла С на устройство В + проверяем, что копирование прошло успешно

![Скрин с устройства A 6](https://github.com/Ermack241/White---maned-horses/blob/main/DevOps%201%20lab/pic/photo_2023-10-06_18-46-30.jpg)

Рис 6. - Скрин с устройства A


## Операционные системы устройств:
1. Устройство A - Ubuntu 22.04.1 LTS
2. Устройство B - openSUSE Leap 15.4 (IP: 192.168.1.50)
3. Устройство C - Ubuntu precise (12.04.5 LTS) (IP: 192.168.1.10 - name:usrv)

## Команды, используемые в лабораторной работе:
1. Определение IP-адреса устройства в данной локальной сети (ip a)

![Пример команды 1](https://github.com/Ermack241/White-maned-horses/blob/main/DevOps%201%20lab/pic/%D0%A0%D0%B8%D1%81%D1%83%D0%BD%D0%BE%D0%BA1.png)

Рис 7. - Пример команды

2. Подключение по ssh к удаленному устройству 
(ssh remote_username@remote_host)

![Пример команды 2](https://github.com/Ermack241/White-maned-horses/blob/main/DevOps%201%20lab/pic/%D0%A0%D0%B8%D1%81%D1%83%D0%BD%D0%BE%D0%BA2.png)

Рис 8. - Пример команды

3. Выход с локального устройства (logout)

![Пример команды 3](https://github.com/Ermack241/White-maned-horses/blob/main/DevOps%201%20lab/pic/%D0%A0%D0%B8%D1%81%D1%83%D0%BD%D0%BE%D0%BA3.png)

Рис 9. - Пример команды

4. Передача файла по SSH-ключу
(scp remote_username@remote_host: path_of_file_src path_of_file_dst)

![Пример команды 4](https://github.com/Ermack241/White-maned-horses/blob/main/DevOps%201%20lab/pic/%D0%A0%D0%B8%D1%81%D1%83%D0%BD%D0%BE%D0%BA4.png)

Рис 10. - Пример команды

5. Просмотр файлов текущего каталога (ll  path_of_catalog)

![Пример команды 5](https://github.com/Ermack241/White-maned-horses/blob/main/DevOps%201%20lab/pic/%D0%A0%D0%B8%D1%81%D1%83%D0%BD%D0%BE%D0%BA5.png)

Рис 11. - Пример команды

6. Информация о версии операционной системы (cat /etc/os-release)

![Пример команды 6](https://github.com/Ermack241/White-maned-horses/blob/main/DevOps%201%20lab/pic/%D0%A0%D0%B8%D1%81%D1%83%D0%BD%D0%BE%D0%BA6.png)

Рис 12. - Пример команды

## Просто жираф

![Просто жираф 1](https://github.com/Ermack241/White-maned-horses/blob/main/DevOps%201%20lab/pic/zhiraf1.png)
