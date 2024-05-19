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

Клонируем удалённый репозиторий на локальную машину:

```markdown
git clone git@github.com:German-D/tg_dictionary.git
```
Создать бота и через [@BotFather](https://t.me/BotFather) и вставить в проекте свой токен от бота

Создаём виртуальное окружение внутри папки проекта.
Далее команды для MacOS (для windows инуструкция [есть вот тут](https://realpython.com/python-virtual-environments-a-primer/#create-it))

``` markdown
python3 -m venv venv
```

``` markdown
source venv/bin/activate
```
Устанавливаем библиотеки

``` markdown
python3 -m pip install pyTelegramBotAPI
```

Запускаем
``` markdown
python3 dict_bot.py
```

## Автор

Герман Дольников ([@dolnikov](https://t.me/dolnikov))

