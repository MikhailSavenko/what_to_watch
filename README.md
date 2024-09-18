### Что посмотреть?

**what_to_watch** — это проект, написанный в рамках изучения библиотеки Flask. Он реализует RESTful API с использованием только Flask, а для работы с базой данных использованы `flask-sqlalchemy` и `Flask-Migrate`, которые используют Alembic для миграций. Для фронтенда применяются HTML, CSS и шаблонизатор Jinja.

Проект предоставляет возможность:
- Получить случайное название и описание фильма.
- Выбрать другой фильм(следующий случайный).
- Создать свой отзыв на фильм.

### Шаги для запуска проекта

1. **Клонируйте репозиторий и перейдите в директорию проекта:**

    ```bash
    git clone git@github.com:MikhailSavenko/what_to_watch.git
    ```

    ```bash
    cd what_to_watch
    ```

2. **Создайте и активируйте виртуальное окружение:**

    Для пользователей macOS/Linux:

    ```bash
    python3 -m venv venv
    ```

    ```bash
    source venv/bin/activate
    ```

    Для пользователей Windows:

    ```bash
    python -m venv venv
    ```

    ```bash
    venv\Scripts\activate
    ```

3. **Установите зависимости из файла `requirements.txt`:**

    ```bash
    python -m pip install --upgrade pip
    ```

    ```bash
    pip install -r requirements.txt
    ```
4. **Переменные окружения**  
   Создайте файл `.env` и скопируйте в него данные из файла `env_file.txt`. Для этого выполните следующие шаги:

   ```bash
   cp env_file.txt .env
   ```

5. **Запустите проект:**

    ```bash
    flask run
    ```

Теперь приложение должно быть доступно по адресу `http://localhost:5000`.