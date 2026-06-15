# Django Sprint 1

Проект Django Sprint 1 для Яндекс Практикума.

## Структура проекта

```
django_sprint1/
├── html/              # HTML-вёрстка для страниц и статика
├── tests/             # Тесты Яндекс Практикума
├── blogicum/          # Рабочая папка с кодом проекта
├── blog/              # Приложение blog
├── pages/             # Приложение pages
├── templates/         # Шаблоны
├── .flake8            # Настройки тестов Практикума
├── .gitignore         # Список файлов, которые не отслеживает Git
├── LICENSE            # Лицензия
├── pytest.ini         # Конфигурация тестов Практикума
├── README.md          # Описание проекта
└── requirements.txt   # Зависимости проекта
```

## Установка и запуск

1. Создайте виртуальное окружение:
```bash
python -m venv venv
```

2. Активируйте виртуальное окружение:
```bash
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate
```

3. Установите зависимости:
```bash
pip install -r requirements.txt
```

4. Запустите тесты:
```bash
pytest
```