# Домашнее задание к занятию «Работа с данными (DDL/DML)» - Николай Копосов


### Задание 1
1.1. Поднимите чистый инстанс MySQL версии 8.0+. Можно использовать локальный сервер или контейнер Docker.

1.2. Создайте учётную запись sys_temp. 

1.3. Выполните запрос на получение списка пользователей в базе данных. (скриншот)

1.4. Дайте все права для пользователя sys_temp. 

1.5. Выполните запрос на получение списка прав для пользователя sys_temp. (скриншот)

1.6. Переподключитесь к базе данных от имени sys_temp.

Для смены типа аутентификации с sha2 используйте запрос: 
```sql
ALTER USER 'sys_test'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';
```
1.6. По ссылке https://downloads.mysql.com/docs/sakila-db.zip скачайте дамп базы данных.

1.7. Восстановите дамп в базу данных.

1.8. При работе в IDE сформируйте ER-диаграмму получившейся базы данных. При работе в командной строке используйте команду для получения всех таблиц базы данных. (скриншот)

*Результатом работы должны быть скриншоты обозначенных заданий, а также простыня со всеми запросами.*


### Задание 2
Составьте таблицу, используя любой текстовый редактор или Excel, в которой должно быть два столбца: в первом должны быть названия таблиц восстановленной базы, во втором названия первичных ключей этих таблиц. Пример: (скриншот/текст)
```
Название таблицы | Название первичного ключа
customer         | customer_id
```




### Решение 1:

#### 1.1. Поднимите чистый инстанс MySQL версии 8.0+. Можно использовать локальный сервер или контейнер Docker.
![1.1](/files/1-1.png)

#### 1.2. Создайте учётную запись sys_temp.

![1.2](/files/1-2.png)

#### 1.3. Выполните запрос на получение списка пользователей в базе данных. (скриншот)

![1.3](/files/1-3.png)

#### 1.4. Дайте все права для пользователя sys_temp. 
![1.4](/files/1-4.png)

#### 1.5. Выполните запрос на получение списка прав для пользователя sys_temp. (скриншот)
![1.5](/files/1-5.png)

#### 1.7. Восстановите дамп в базу данных.
![1.7](/files/1-7.png)

#### 1.8. При работе в IDE сформируйте ER-диаграмму получившейся базы данных. При работе в командной строке используйте команду для получения всех таблиц базы данных. (скриншот)
![1.8](/files/1-8.png)

### Решение 2:
Составьте таблицу, используя любой текстовый редактор или Excel, в которой должно быть два столбца: в первом должны быть названия таблиц восстановленной базы, во втором названия первичных ключей этих таблиц. Пример: (скриншот/текст)
```
Название таблицы | Название первичного ключа
customer         | customer_id
```

![2](/files/2.png)

![2-1](/files/2-1.png)

[Сформированная таблица](/files/new_table_202401182155.xlsx)

