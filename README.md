# Домашнее задание к занятию "`Защита хоста`" - `Стрекозов Владимир`

### Задание 1
Установите eCryptfs.  
Добавьте пользователя cryptouser.  
Зашифруйте домашний каталог пользователя с помощью eCryptfs.  
В качестве ответа пришлите снимки экрана домашнего каталога пользователя с исходными и зашифрованными данными.   
До:  
![](https://github.com/Svalker1989/Host_protection/blob/main/Z1_1.PNG)    
После:  
![](https://github.com/Svalker1989/Host_protection/blob/main/Z1_2.PNG)   
### Задание 2
Установите поддержку LUKS.  
Создайте небольшой раздел, например, 100 Мб.  
Зашифруйте созданный раздел с помощью LUKS.  
В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.  
Проверяем установку `cryptosetup --version`  
![](https://github.com/Svalker1989/Host_protection/blob/main/Z2_2.PNG)  
Шифруем раздел:  
![](https://github.com/Svalker1989/Host_protection/blob/main/Z2_3.PNG)    
Открываем раздел, форматируем, создаем ФС, монтируем раздел в /tmp/.secret  
![](https://github.com/Svalker1989/Host_protection/blob/main/Z2_4.PNG)  
