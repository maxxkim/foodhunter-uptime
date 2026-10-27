# foodhunter-uptime

Внешний пинг Фудхантера: GitHub Actions каждые 5 минут проверяет `https://api.foodhunter.moscow/api/v1/health` и `https://foodhunter.moscow/` и пишет в Telegram-чат алертов, когда что-то перестало отвечать и когда снова ответило (секреты `TELEGRAM_BOT_TOKEN`, `TELEGRAM_CHAT_ID`).
Репозиторий публичный, чтобы Actions были бесплатными. **GitHub отключает расписание после 60 дней без коммитов:** раз в полтора-два месяца нужен любой коммит (или включить workflow снова во вкладке Actions).
