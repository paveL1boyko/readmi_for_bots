[![Static Badge](https://img.shields.io/badge/Telegram-Channel-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/hidden_coding)

[![Static Badge](https://img.shields.io/badge/Telegram-Chat-yes?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/hidden_codding_chat)

[![Static Badge](https://img.shields.io/badge/Telegram-Bot%20Link-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/GenkiMinerBot/GenkiMiner?startapp=7V_OoUyrXXX0)

# Бот для [GenkiMinerGame](https://t.me/GenkiMinerBot/GenkiMiner?startapp=7V_OoUyrXXX0)

![image](.github/images/img_1.png)

# Что делает этот бот?
1. Копает
2. Крутит спины
3. Открывает сундуки дневыне
4. Собирает золото

## Функционал


| Функция                               | Поддерживается |
|---------------------------------------|:--------------:|
| Многопоточность                       |       ✅        |
| Привязка прокси к сессии              |       ✅        |
| Задержка перед запуском каждой сессии |       ✅        |
| Автоматические копает                 |       ✅        |
| Автоматические спины                  |       ✅        |
| Авто открытие сундуков                |       ✅        |
| Docker                                |       ✅        |

## Настройки

| Опция                   | Описание                                                                                  |
|-------------------------|-------------------------------------------------------------------------------------------|
| **API_ID / API_HASH**   | Данные платформы для запуска сессии Telegram                                              |
| **TAPS_ENABLED**        | Тапы включены дефолт `True` возможно(`False`)                                             |
| **RANDOM_SLEEP_TIME**   | Время сна после завершения всех действий бота дефолт `[1300, 1700]`                       |

**API_ID** и **API_HASH** вы можете получить после создания приложения
на [my.telegram.org/apps](https://my.telegram.org/apps)

## Быстрый старт
## Предварительные условия

Прежде чем начать, убедитесь, что у вас установлено следующее:

- [Python](https://www.python.org/downloads/) **версии 3.10**

## Получение API ключей

1. Перейдите на сайт [my.telegram.org](https://my.telegram.org) и войдите в систему, используя свой номер телефона.
2. Выберите **"API development tools"** и заполните форму для регистрации нового приложения.
3. Запишите `API_ID` и `API_HASH` в файле `.env`, предоставленные после регистрации вашего приложения.

## Установка

Вы можете скачать [**Репозиторий**](https://github.com/paveL1boyko/GenkiBot.git) клонированием на вашу систему и
установкой необходимых зависимостей:

```shell
git clone https://github.com/paveL1boyko/GenkiBot.git
cd GenkiBot
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
~/GenkiBot >>> python3 main.py --action (1/2)
# Or
~/GenkiBot >>> python3 main.py -a (1/2)

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
~/GenkiBot >>> python main.py --action (1/2)
# Или
~/GenkiBot >>> python main.py -a (1/2)

# 2 - Запускает кликер
# 1 - Создает сессию
```
