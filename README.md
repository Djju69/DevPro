# DevPro Portfolio Website

Портфолио сайт для разработчика Telegram-ботов и веб-приложений.

## Развертывание на Railway

1. Подключите репозиторий к Railway
2. Railway автоматически определит Python приложение
3. Сайт будет доступен по сгенерированному URL

## Локальный запуск

```bash
pip install -r requirements.txt
python app.py
```

Сайт будет доступен по адресу: http://localhost:5000

## Структура проекта

- `index.html` - основной HTML файл с портфолио
- `app.py` - Flask сервер для развертывания
- `requirements.txt` - зависимости Python

## Настройка контактов

В файле `index.html` замените:
- `https://t.me/yourusername` на ваш Telegram
- `https://wa.me/yourphone` на ваш WhatsApp
- `your@email.com` на ваш email
