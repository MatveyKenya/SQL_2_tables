# SQL_2_tables

Задача Две таблицы
---
табл CUSTOMERS

содержит в себе 5 столбцов - id, name, surname, age, phone_number
первичным ключом будет поле id, который инкрементируется каждый раз, при создании пользователя

табл ORDERS

содержит в себе 4 столбца - id, date, customer_id,product_name, amount

первичным ключом будет поле id, который инкрементируется каждый раз, при создании заказа
внешним ключом на поле id таблицы пользователей будет customer_id

скрипт
---
возвращать из таблиц поля product_name для пользователей с именем alexey независимо от регистра ввода имени.
