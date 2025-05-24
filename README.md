Напишите тренировочный код для задания. Код (ВЕСЬ) в одном файле:
Выберите из таблицы products все товары в порядке возрастания цены (price).

CREATE TABLE products (
  id INT UNSIGNED NOT NULL PRIMARY KEY,
  name VARCHAR(100),
  count INT UNSIGNED,
  price INT UNSIGNED
);

INSERT INTO products (id, name, count, price)
VALUES 
(1, 'Стиральная машина', 5, 10000),
(2, 'Холодильник', 0, 10000),
(3, 'Микроволновка', 3, 4000),
(4, 'Пылесос', 2, 4500),
(5, 'Вентилятор', 0, 700),
(6, 'Телевизор', 7, 31740),
(7, 'Тостер', 2, 2500),
(8, 'Принтер', 4, 3000);

![image](https://github.com/user-attachments/assets/b6571673-014d-41fa-adbf-bbbd3f1a4eaf)

![image](https://github.com/user-attachments/assets/95efca67-3254-4ea5-8ac1-11dc5b0a30b5)

SELECT * FROM products 
ORDER BY price;

![image](https://github.com/user-attachments/assets/1834b964-a06d-4c74-9a48-d2c6f8526fe7)

