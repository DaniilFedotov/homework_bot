# Homework bot

### Описание
Учебный проект представляет собой telegram-бота, написанного с использованием python. Проверка домашнего задания и функционирование telegram-бота осуществляется посредством API.

### Как запустить проект
Для локального запуска необходимо клонировать репозиторий и перейти в него в командной строке:
```sh
git clone https://github.com/DaniilFedotov/homework_bot.git
```
```sh
cd homework_bot
```

Cоздать и активировать виртуальное окружение:
```sh
python3 -m venv venv
```
```sh
source venv/bin/activate
```

Установить зависимости из файла requirements.txt:
```sh
python3 -m pip install --upgrade pip
```
```sh
pip install -r requirements.txt
```

После этого нужно создать файл .env и заполнить его в соответствии с примером .env.example.
Затем бот запускается командой:
```sh
python3 homework.py
```
