# AssistantQA_bot
Бот генератор номеров тестовых банковских карт

Бота можно запустить на https://colab.research.google.com/, для этого нужно:

1. Иметь токен бота или создать любого бота (например generator_card_bot) в Telegram через бот botFather, чтобы получить токен (UUID)
2. Вставить токен в файл card_bot из проекта в код бота (token='вставить токен')
3. Перейти на https://colab.research.google.com/
4. Нажать +код и загрузить по очереди две библиотеки: !pip install pyTelegramBotAPI и !pip install Faker
5. Нажать +код и загрузить код бота
6. Нажать 'запустить код'
7. Перейти в Телеграм и открыть там нужного бота
