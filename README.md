<div align="center">

🚀 Software Engineer Portfolio & Showcase

Высокопроизводительное веб-решение для презентации навыков и автоматизированной связи.

</div>

📝 О проекте

Vlad_Portfolio — это полноценная визитка инженера, спроектированная с упором на производительность и UX. Сайт служит центральным узлом для демонстрации стека (Java, C++, C#, Python) и реализованных кейсов.

💡 Особенность: Проект построен на Zero-Backend архитектуре. Отправка данных из формы обратной связи происходит напрямую через Telegram Bot API. Это исключает лишние сервера и гарантирует мгновенную доставку уведомлений.

✨ Ключевой функционал

🌓 Интеллектуальный UI: Динамическое переключение тем (Dark/Light) с сохранением выбора в localStorage.

⌨️ Typewriter Engine: Кастомный эффект печатающейся машинки для презентации ключевых тезисов.

📲 Direct-to-Telegram: Прямая интеграция для получения заявок в режиме реального времени.

📱 Адаптивность: Mobile-First подход — идеально выглядит на смартфонах и 4K мониторах.

⏳ Интерактивный таймлайн: Визуализация этапов обучения и роста с использованием плавной анимации.

🛠 Техническая реализация

Архитектура и Стек:

Frontend: Vanilla JavaScript (ES6+), HTML5 и Tailwind CSS.

Анимации: Применение Intersection Observer API для появления элементов при скролле.

Сетевой слой: Асинхронный метод fetch для взаимодействия с Telegram API.

Оптимизация: Кастомные CSS-фильтры (backdrop-blur) для эффекта матового стекла.

🚀 Установка и запуск (Local Setup)

1. Клонирование репозитория

git clone [https://github.com/vladislavligorskij27-crypto/vlad-portfolio.git](https://github.com/vladislavligorskij27-crypto/vlad-portfolio.git)
cd vlad-portfolio


2. Настройка конфигурации

Откройте index.html и вставьте данные вашего бота в секции JavaScript:

const TELEGRAM_BOT_TOKEN = 'ВАШ_ТОКЕН';
const TELEGRAM_CHAT_ID = 'ВАШ_ID';


3. Запуск

Просто откройте файл index.html в браузере. Установка зависимостей не требуется.

📂 Структура проекта

vlad-portfolio/
├── .gitignore          # Исключения для Git
├── index.html          # Основной код (Разметка, стили и JS-логика)
└── README.md           # Техническая документация (вы здесь)


👨‍💻 Автор

Лигорский Владислав | Software Engineer

Telegram: @Whaat1sLove

GitHub: vladislavligorskij27-crypto

Live Demo: portfoliovladislav.netlify.app

<div align="center">

Если этот проект был вам полезен, буду рад вашей звездочке (Star) на GitHub! ⭐

</div>
