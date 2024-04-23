# Личный ИИ бот для Телеграма

## Описание

Личный ИИ бот для Телеграма, основанный на модели deepseek.coder. Этот бот может помогать в написании кода, предоставляя простые и понятные рекомендации по синтаксису, составлению структуры, алгоритмов и др.

## Установка и использование

Для установки и использования этого бота, вам необходимо:

1. Установить необходимые библиотеки. Вы можете использовать следующую команду для установки:

```bash
pip install openai telebot
```

2. Зарегистрировать своего бота на Telegram, используя [@BotFather](https://t.me/BotFather) и получить токен для доступа к API Telegram.

3. Получить API key deepseek <https://platform.deepseek.com/>.

4. Пример файла config.py:

```python
telegram_bot_token = "ваш токен доступа к API Telegram"
deepseek_api_key = "ваш deepseek API token"
```

6. Так же можно в main.py сменить модель ИИ с deepseek.coder на deepseek.chat, если требуется просто бот ИИ:

```python
chat_completion = client.chat.completions.create(
        model="deepseek-chat",
        messages=conversation_history
    )
```

## Как пользоваться

После установки и запуска бота, вы можете начать диалог с ним в Telegram. Он будет отвечать на ваши запросы, помогая вам писать код. Просто напишите ему свой код и он даст вам соответствующие рекомендации.

## Контакты

Если у вас есть вопросы или проблемы, вы можете со мной связаться через мой профиль на GitHub или по электронной почте: <arkanoidalex@gmail.com>
