<h2>Телеграм бот «Словарик». С расшифровкой аббревиатур</h2>

> **Статус проекта:**
>
> 🟢 Поддерживается (активный) 

## Цели и Задачи
Помочь новым сотрудника запоминть местные аббревиатуры или определения по тестированию. Аналог https://t.me/BankAcronymBot

## 🖼 Скриншоты

Стартовое меню:

![image](https://raw.githubusercontent.com/German-D/tg_dictionary/main/static/menu.png)

После отправки запроса:

![image](https://raw.githubusercontent.com/German-D/tg_dictionary/main/static/answer.png)

## 💻 Технологии

* Python
* Библиотека `telebot`

## ⚙️ Как добавить новые определения или аббревиатуры
В файле dict_bot.py в объекте DEFINITOINS необходимо добавить новые определения в формате 'ключевая фраза': 'соответствующее ей определение'

## ⏬ Установка на локальном компьютере

1. Скачать проект

2. Создать бота и через [@BotFather](https://t.me/BotFather) и вставить в проекте свой токен от бота

3. Создаём виртуальное окружение внутри папки проекта.
Далее команды для MacOS (для windows инуструкция [есть вот тут](https://realpython.com/python-virtual-environments-a-primer/#create-it))

``` markdown
python3 -m venv venv
```

``` markdown
source venv/bin/activate
```
4. Устанавливаем библиотеки

``` markdown
python3 -m pip install pyTelegramBotAPI
```

5. Запускаем
``` markdown
python3 dict_bot.py
```

## Автор

Герман Дольников ([@dolnikov](https://t.me/dolnikov))

