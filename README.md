# Домашнее задание к занятию "`Работа с данными (DDL/DML)`" - `Спиридонов Сергей`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1
1.2 create user 'sys_temp'@'localhost' identified by 'password';  
1.3 select user from mysql.user;  
[Скриншот](https://github.com/sergeysprdnv/screenshots/blob/main/1.3.png)  
1.4 grant all privileges on *.* to 'sys_temp'@'localhost';  
1.5 show grants for 'sys_temp'@'localhost';  
[Скриншот](https://github.com/sergeysprdnv/screenshots/blob/main/1.5.png)  
1.8
[Скриншот](https://github.com/sergeysprdnv/screenshots/blob/main/1.8.png)  


### Задание 2
Название таблицы | Название первичного ключа  
customer         | customer_id  
payment			 | payment_id  
rental			 | rental_id  
store			 | store_id  
staff			 | staff_id  
address			 | address_id  
city			 | city_id  
country 		 | country_id  
inventory		 | inventory_id  
nicer_but_slower_film_list  
staff_list  
customer_list  
film_category	 | film_id, category_id  
actor			 | actor_id  
category_id		 | category_id  
film_category	 | film_id  
language		 | language_id  
film_list  
sales_by_film_category  
film_text  
sales_by_store  
actor_info  



