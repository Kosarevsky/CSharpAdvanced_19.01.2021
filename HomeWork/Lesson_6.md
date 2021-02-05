Теория:
1. Просмотрите презентацию по LINQ и ADO.NET. (Кому необходимо, напомните себе про основы БД в презентации DatabaseEssentials)

Практика:
1. Используя коллекцию персонажей из проекта LINQ, создайте LINQ запрос, в котором выберите анонимный тип который будет содержать в себе свойство PersonDescription - это должна быть строка, в которой прописаны значения всех свойств персонажа.
2. С помощью LINQ сделайте left join колекций персонажей и историй. Создайте структуру данных, которая будет содежать нужные после объединения поля. Т.е. запрос должен быть выполнен без использования анонимного объекта.
3. С помощью ADO.NET создайте в БД таблицу Stories. Заполните ее несколькими значениями. Выведите данные из таблицы. Строка подключения должна быть указана в app.config.

В проект добавлены примеры с left join и GroupJoin().