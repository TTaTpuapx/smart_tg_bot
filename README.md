🤖 Telegram AI Bot (Mistral + Search + Web Reader)

Умный Telegram-бот с поддержкой LLM, поиска в интернете и чтения сайтов.

🚀 Возможности
🧠 AI-ассистент
•	Общение через Mistral AI
•	Понимание контекста (память диалога)
•	Ответы на любые вопросы
🔍 Поиск в интернете
•	Автоматический поиск через Apify
•	Используется, если вопрос требует актуальной информации
🌐 Чтение сайтов
Просто отправь ссылку
Бот:
откроет сайт
извлечёт текст
кратко перескажет
🌦 Погода
•	Получение текущей погоды через Yandex API
•	Команда: /weather Москва
💬 Удобство
•	Inline кнопки
•	Авто-режим (сам решает: искать или отвечать)
🧱 Архитектура
Telegram → Bot → Логика → API:
                        ├── Mistral AI (ответы)
                        ├── Apify (поиск)
                        ├── Website parser (чтение сайтов)
                        └── Yandex Weather (погода)
📦 Установка
git clone https://github.com/TTaTpuapx/your_repo.git
cd your_repo
pip install -r requirements.txt
🔑 Настройка

Создай файл .env в корне проекта:

BOT_TOKEN=your_telegram_token
MISTRAL_API_KEY=your_mistral_api_key
APIFY_API_KEY=your_apify_api_key
YANDEX_WEATHER_API_KEY=your_weather_api_key
▶️ Запуск (локально)
python chat.py
👨‍💻 Автор

Кирилл
👉 https://t.me/s_usser
