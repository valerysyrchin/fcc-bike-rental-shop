# FreeCodeCamp: Build a Bike Rental Shop

[Русское описание ниже](#описание-проекта-на-русском)

An educational project created as part of the freeCodeCamp "Relational Database" course. In this workshop, an interactive Bash program was developed to manage rental information, inventory, and customer data for a bike rental shop using a PostgreSQL database.

### Tech Stack
* **Database:** PostgreSQL
* **Query Language:** SQL
* **Automation & Logic:** Bash (used for interactive CLI application and database queries)

### Key Achievements & Skills Learned:
* Designed and implemented a relational database schema for a bike rental business from scratch.
* Established table relationships using primary keys (`PRIMARY KEY`) and foreign keys (`FOREIGN KEY`) across tables like `bikes`, `customers`, and `rentals`.
* Developed an interactive Bash script utilizing loops, conditional statements (`if/else`), and functions to capture user input.
* Leveraged the `psql` CLI utility within Bash to dynamically query and update database states in real-time.
* Wrote complex SQL queries, including `INNER JOIN` with `USING` clauses and handling `NULL` values to track active bike rentals.
* Practiced database administration basics, including generating logical database dumps using `pg_dump` for project porting.

### Project Structure
* `bikes.sql` - database dump file containing the complete table structures, constraints, and initial data.
* `bike-shop.sh` - interactive Bash script that serves as the main command-line interface for renting and returning bikes.

---

## Описание проекта на русском

Учебный проект, созданный в рамках воркшопа от freeCodeCamp по курсу Relational Database. В ходе выполнения этого проекта была разработана интерактивная консольная программа на Bash, которая взаимодействует с базой данных PostgreSQL для управления арендой велосипедов, клиентами и доступным инвентарем.

### Технологический стек
* **СУБД:** PostgreSQL
* **Язык запросов:** SQL
* **Автоматизация и логика:** Bash (использовался для создания интерактивного CLI-приложения и выполнения запросов к БД)

### Чему я научился в этой части:
* Проектировать и разворачивать схему реляционной базы данных для учета аренды с нуля.
* Настраивать связи между таблицами с помощью первичных (`PRIMARY KEY`) и внешних ключей (`FOREIGN KEY`) для таблиц `bikes`, `customers` и `rentals`.
* Писать интерактивные Bash-скрипты с использованием циклов, условий (`if/else`) и функций для обработки ввода пользователя.
* Использовать утилиту `psql` внутри Bash для динамического чтения и обновления данных в таблицах в реальном времени.
* Составлять сложные SQL-запросы, включая объединение таблиц (`INNER JOIN` с оператором `USING`) и фильтрацию по отсутствующим значениям (`IS NULL`) для отслеживания активных аренд.
* Работать с инструментами администрирования баз данных, в частности, создавать дампы базы данных через `pg_dump` для переноса проекта.

### Структура проекта
* `bikes.sql` - дамп базы данных, содержащий всю структуру таблиц, связи, ограничения и начальные данные.
* `bike-shop.sh` - основной интерактивный Bash-скрипт, представляющий собой консольный интерфейс для оформления аренды и возврата велосипедов.
