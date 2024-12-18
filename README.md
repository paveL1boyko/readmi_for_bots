[![Static Badge](https://img.shields.io/badge/Telegram-Channel-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/hidden_coding)

[![Static Badge](https://img.shields.io/badge/Telegram-Chat-yes?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/hidden_codding_chat)

[![Static Badge](https://img.shields.io/badge/Telegram-Bot%20Link-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/GoblinMine_bot/start?startapp=1092379081)

# Бот для [GoblinMinerBot](https://t.me/GoblinMine_bot/start?startapp=1092379081)

![img1](.github/images/img.png)

# Делает все

## Функционал

| Функция                                 | Поддерживается |
|-----------------------------------------|:--------------:|
| Многопоточность                         |       ✅        |
| Привязка прокси к сессии                |       ✅        |
| Задержка перед запуском каждой сессии   |       ✅        |
| Получение ежедневной награды            |       ✅        |
| Получение награды за друзей             |       ✅        |
| Получение награды за выполненные квесты |       ✅        |
| Сбор монте в шахтах                     |       ✅        |
| Улучшение шахт                          |       ✅        |
| Авто прокачка                           |       ✅        |
| Docker                                  |       ✅        |

## Настройки

| Опция                 | Описание                                     |
|-----------------------|----------------------------------------------|
| **API_ID / API_HASH** | Данные платформы для запуска сессии Telegram |

## Быстрый старт 📚

Для быстрой установки и последующего запуска - запустите файл run.bat на Windows или run.sh на Линукс

## Предварительные условия

Прежде чем начать, убедитесь, что у вас установлено следующее:

- [Python](https://www.python.org/downloads/) **версии 3.10**

## Получение API ключей

1. Перейдите на сайт [my.telegram.org](https://my.telegram.org) и войдите в систему, используя свой номер телефона.
2. Выберите **"API development tools"** и заполните форму для регистрации нового приложения.
3. Запишите `API_ID` и `API_HASH` в файле `.env`, предоставленные после регистрации вашего приложения.

## Установка

Вы можете скачать [**Репозиторий**](https://github.com/paveL1boyko/GoblinMinerBot.git) клонированием на вашу систему и
установкой необходимых зависимостей:

```shell
git clone https://github.com/paveL1boyko/GoblinMinerBot.git
cd GoblinMinerBot
```

Затем для автоматической установки введите:

Windows:

```shell
run.bat
```

Linux:

```shell
run.sh
```

# Linux ручная установка

```shell
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Здесь вы обязательно должны указать ваши API_ID и API_HASH , остальное берется по умолчанию
python3 main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:

```shell
~/GoblinMinerBot >>> python3 main.py --action (1/2)
# Or
~/GoblinMinerBot >>> python3 main.py -a (1/2)

# 2 - Запускает кликер
# 1 - Создает сессию
```

# Windows ручная установка

```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Указываете ваши API_ID и API_HASH, остальное берется по умолчанию
python main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:

```shell
~/GoblinMinerBot >>> python main.py --action (1/2)
# Или
~/GoblinMinerBot >>> python main.py -a (1/2)

# 2 - Запускает кликер
# 1 - Создает сессию
```
