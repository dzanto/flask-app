### Тестирование Docker, Flask и GitHub Workflow
#### Описание
В репозитарии подключен GitHub Action и настроен workflow в файле `.github/workflows/main.yml`
- При пуше в ветку `master` проходят тесты flake8 и `tests.py`
- Пушится образ(dzanto/flask_ya) на DockerHub
- Подключаемся к хосту и запускаем docker контейнер
- Отправляем сообщение через Telegram бота об успешном выполнении
