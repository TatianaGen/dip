ТРЕКЕР ЗАДАЧ СОТРУДНИКОВ

Описание проекта

Трекер задач позволит компании эффективно управлять заданиями, назначенными сотрудникам, и обеспечивать прозрачность процессов выполнения задач. Это поможет в равномерном распределении нагрузки между сотрудниками и своевременном выполнении ключевых задач.

    python 3.11
    django 4.2.2
    djangorestframework 3.14.0
    gunicorn
    PostgreSQL
    Docker

Инструкция для развертывания проекта с использованием Docker:

    Клонирование
    Создание и активация виртуального окружения
    Установка зависимостей
    Запуск проекта

Клонирование проекта:

https://github.com/TatianaGen/Diplom.git

Запуск:

Для запуска проекта необходимо создать .env в директории (тут корневая директория вашего проекта), скопировать в него содержимое файла .env.example

Запустить команду, указанную ниже из директории.

docker-compose up -d --build

