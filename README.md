# Bot Mini App — Frontend

Фронтенд Telegram Mini App для бота учёта рабочего времени.

## Деплой на GitHub Pages

1. Создайте **публичный** репозиторий на GitHub
2. Загрузите этот файл `index.html` в корень репозитория
3. **Замените** `%%API_BASE%%` в `index.html` на URL вашего бэкенда:
   ```
   const API_BASE = 'https://your-server.com:8000';
   ```
4. Включите GitHub Pages:
   - Settings → Pages → Source: **Deploy from a branch**
   - Branch: `main`, folder: `/ (root)`
   - Save
5. URL будет: `https://<username>.github.io/<repo>/`

## Подключение к боту

Через @BotFather:
1. `/mybots` → выбрать бота
2. `Bot Settings` → `Menu Button`
3. Вставить URL: `https://<username>.github.io/<repo>/`

## Функционал

- 📊 **Статистика** — количество записей, снимков, смен, отработанных часов
- 📋 **Логи** — список записей с пагинацией и удалением
- ⏱ **Время** — записи приходов/уходов с пагинацией и удалением
- 🎨 Автоматическая тема Telegram (светлая/тёмная)
