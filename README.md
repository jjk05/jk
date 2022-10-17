#jk
Жумангалиева Карина 031, группа Валеры Ухова тестировщик
сколько таблиц в базе данных?
Вводим SQL-запрос: SELECT COUNT(*) FROM information_schema.tables WHERE table_schema = 'p518238_lyc'
вывести все из таблицы с пользователем
Вводим SQL-запрос: SELECT * FROM users
вывести все оценки
Вводим SQL-запрос: SELECT * FROM grades
вывести пользователей и их оценки
Вводим SQL-запрос: SELECT * FROM users JOIN grades on users.user_id=grades.user_id
найти количество зписей с именем Олег
Вводим SQL-запрос: SELECT * FROM users WHERE name='Олег'
