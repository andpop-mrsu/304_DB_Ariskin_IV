# Task02

## Требования к окружению

- Python 3
- SQLite (утилита `sqlite3` в PATH)
- bash (Git Bash / WSL / Linux)

## Запуск

./db_init.bat

Скрипт генерирует `db_init.sql` и создаёт заполненную базу `movies_rating.db`.

## Файлы

- `make_db_init.py` — генератор SQL-скрипта
- `db_init.bat` — запуск генератора и загрузка скрипта в БД
- `db_init.sql` — сгенерированный SQL
- `movies_rating.db` — итоговая база данных

## Исходные данные

- `movies.csv` — фильмы (movieId, title, genres)
- `ratings.csv` — оценки (userId, movieId, rating, timestamp)
- `tags.csv` — теги (userId, movieId, tag, timestamp)
- `users.txt` — пользователи (userId, name, email, gender, birthdate, occupation)