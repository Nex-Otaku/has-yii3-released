# Бот для проверки статуса разработки Yii 3

## Установка

- Скопировать `env.example.json` в `env.json`, прописать там ключ бота и ID чатов.

### Добавить в cron
```
30 09 * * * php test /path/to/index.php
10 10 * * * php /path/to/index.php
00 * * * * php /path/to/events.php
```
