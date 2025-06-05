📁 Название проекта: WeatherCLI
🌦 WeatherCLI — CLI-инструмент для прогноза погоды

WeatherCLI — это простой и удобный командный инструмент, написанный на Python, который позволяет получать текущую погоду и прогноз на несколько дней прямо в терминале. Использует открытое API (например, OpenWeatherMap) для получения данных о погоде.
🚀 Возможности

    Получение текущей погоды по городу

    Прогноз на 3 дня

    Поддержка нескольких единиц измерения (Цельсий, Фаренгейт)

    Цветной вывод в терминале

    Кэширование последнего запроса для оффлайн-доступа

🛠️ Установка

git clone https://github.com/your-username/WeatherCLI.git
cd WeatherCLI
pip install -r requirements.txt

🌐 Настройка

    Получите API-ключ на https://openweathermap.org/api

    Создайте .env файл в корне проекта и добавьте туда свой ключ:

API_KEY=your_api_key_here

📈 Примеры использования

# Получить текущую погоду в Москве
python weather.py --city Moscow

# Получить прогноз на 3 дня в Париже
python weather.py --city Paris --forecast

# Использовать Фаренгейты
python weather.py --city New York --unit imperial

📦 Зависимости

    requests

    python-dotenv

    colorama

    argparse

Устанавливаются автоматически через requirements.txt.
📄 Лицензия

Этот проект распространяется под лицензией MIT. Подробнее — в LICENSE.
🤝 Контакты

    Автор: Ваше Имя

    Email: your.email@example.com