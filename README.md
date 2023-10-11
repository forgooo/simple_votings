# Проект "Simple votings".

### Цель
Предоставить пользователю сервис, на котором можно быстро создать голосование и собрать мнения пользователей кассательно какого-либо вопроса

### Технологичекий стек:
- python 3
- django
- sqlite

### Инструкция по настройке проекта:
1. Склонировать проект
2. Создать проект в PyCharm с наcтройками по умолчанию
3. Создать виртуальное окружение
4. Подключить это виртуальное окружение к проекту (через settings -> project "simple votings" -> project interpreter)
5. Активировать виртуальное окружение
6. Обновить pip: 
```bash
pip install --upgrade pip
```
7. Установить в виртуальное окружение необходимые пакеты: 
```bash
pip install -r requirements.txt
```
8. Синхронизировать базу данных с кодом: 
```bash
python manage.py migrate
```
9. Создать конфигурацию запуска в PyCharm (файл `manage.py`, опция `runserver`)
